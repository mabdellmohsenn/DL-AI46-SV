# Forest Cover Type Classification

This project uses **Neural Networks (PyTorch)** to classify forest cover types from cartographic data.

The goal is to predict one of **7 forest types** using 55 environmental features.

---

## Dataset
- File: `covtype.csv`  
- 55 input features  
- 7 target classes  
- Data imbalance handled by downsampling majority classes  

---

## Models

### 1. Simple Model
- 1 hidden layer  
- Basic baseline  

### 2. Complex Model
- 3 hidden layers  
- Better performance  

### 3. Regularized Model (Best)
- Dropout  
- Weight decay  
- Learning rate scheduler  
- Early stopping  

This model achieved the best and most stable results.

---

## Evaluation
The models were evaluated using:
- Accuracy  
- Precision / Recall / F1-score  
- Confusion Matrix  
- Classification Report  

A small overfitting test (100 samples) was also done to validate the pipeline.

---

## Saved Models
- `forest_cover_Simplemodel.pth`  
- `forest_cover_Complexmodel.pth`  
- `forest_cover_Regularizedmodel.pth`  

---

## Requirements

Make sure you are using **Python 3.9+**

### Required Libraries & Versions

- torch >= 2.0  
- numpy >= 1.24  
- pandas >= 2.0  
- scikit-learn >= 1.3  
- matplotlib >= 3.7  
- seaborn >= 0.12  

You can install them using the provided `requirements.txt`.

---

## Setup Virtual Environment

### 1️⃣ Create Virtual Environment

```bash
python -m venv venv