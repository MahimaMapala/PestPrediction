# Pest Prediction

This project involves building machine learning models to **predict the type of pest** using input features. It uses both **XGBoost** and a **Deep Learning Sequential Model**. The workflow includes:

- Data preprocessing
- Handling class imbalance
- Model training & evaluation
- Reproducible setup using virtual environments

---

## ⚙️ Models Overview

### XGBoost Classifier
- Handles class imbalance using **SMOTE (Synthetic Minority Over-sampling Technique)** before training.
- Effective for structured/tabular datasets.

### Deep Learning Model (Keras Sequential)
- Built using **Keras Sequential API**
- Uses **`class_weight`** during model training to handle class imbalance
- Suitable for more complex feature spaces

---

## 🧪 Virtual Environment Setup (Windows)

### Create Virtual Environment
```bash
python -m venv env
```

### Activate Virtual Environment
```bash
.\env\Scripts\Activate.ps1
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Deactivate Virtual Environment
```bash
deactivate
```
