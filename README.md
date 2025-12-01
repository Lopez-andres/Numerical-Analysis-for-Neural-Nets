# 🏦 Loan Approval Prediction

[![Python](https://img.shields.io/badge/Python-3.10-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.13-orange.svg)](https://www.tensorflow.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> Bank loan approval prediction using Artificial Neural Networks

**Universidad del Valle** - 2025-II

---

## 📋 Description

Artificial Neural Network to predict loan approval/rejection based on customer features: income, assets, credit score, loan amount, etc.

**Achieved Accuracy:** 97% on validation set

---

## 🚀 Quick Setup

```bash
# 1. Clone repository
git clone https://github.com/Lopez-andres/Loan-Approval-Prediction.git
cd Loan-Approval-Prediction

# 2. Create virtual environment (Anaconda)
conda create -n loan_project python=3.10
conda activate loan_project

# 3. Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow gdown

# 4. Run Jupyter
jupyter notebook

# 5. Open project_1.ipynb and run all cells
```

The dataset downloads automatically from Google Drive when running the notebook.

---

## 🏗️ Model Architecture

```
Input (12 features) → Dense(32, ReLU) + Dropout(0.3) 
                   → Dense(16, ReLU) + Dropout(0.3)
                   → Dense(1, Sigmoid)
```

**Applied Techniques:**
- L2 Regularization (0.001)
- Dropout (30%)
- Data normalization
- Stratified 80/20 validation split

---

## 📊 Results

### Metrics
- **Precision:** 97%
- **Recall:** 97%
- **F1-Score:** 97%

### Confusion Matrix
```
              Rejected  Approved
Rejected         307        16
Approved           8       523
```

**Error Rate:** 2.8% (24/854 cases)

---

## 📁 Project Structure

```
Loan-Approval-Prediction/
├── project_1.ipynb              # Main notebook
├── loan_approval_dataset.csv    # Dataset (auto-download)
├── README.md
└── LICENSE
```

---

## 🎨 Accessibility

Charts use colorblind-friendly palette:
- 🟡 Yellow: Training data
- 🌸 Pink: Validation data
- 🟤 YlOrBr: Heatmaps

---

## 📧 Contact

- **Andres Mauricio Peña:** andres.mauricio.pena@correounivalle.edu.co

---

<div align="center">

**⭐ If this was helpful, give it a star ⭐**

Universidad del Valle - 2025

</div>
