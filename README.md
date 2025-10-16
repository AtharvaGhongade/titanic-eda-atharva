# Titanic Survival Prediction (EDA + ML)

Exploratory Data Analysis (EDA) and Machine Learning model to predict Titanic passenger survival using Python.

---

## Overview
- Performed EDA using **Pandas, Seaborn, Matplotlib**
- Cleaned missing values and encoded categorical data
- Trained a **Logistic Regression model** achieving ~80% accuracy
- Visualized key patterns affecting survival (gender, age, fare, class)

---

## Demo

### 1️⃣ Survival Count
<img width="1920" height="1029" alt="README_survival_count" src="https://github.com/user-attachments/assets/f5db3b90-e506-483d-b655-be918adb8fab" />

### 2️⃣ Survival by Gender
<img width="1741" height="726" alt="README_survival_gender" src="https://github.com/user-attachments/assets/783ec4d0-cb9a-47e8-8ab8-a114c9f7bdd8" />

### 3️⃣ Correlation Heatmap
<img width="1748" height="836" alt="README_survival_heatmap" src="https://github.com/user-attachments/assets/f4e21f87-228b-4baa-8a7a-f5738acb637e" />

---

## Setup (local)
1. `python -m venv venv`  
2. `.\venv\Scripts\Activate.ps1`  
3. `pip install -r requirements.txt`  
4. `jupyter notebook titanic_eda.ipynb`

---

## Files
- `titanic_eda.ipynb` – Main notebook with EDA & model  
- `titanic_cleaned.csv` – Cleaned dataset (auto-saved)  
- `model_accuracy.txt` – Final accuracy result  
- `README_assets/` – Graph screenshots for README  

---

## Results
| Metric | Description |
|---------|--------------|
| **Model Used** | Logistic Regression |
| **Accuracy** | ~0.80 |
| **Top Feature** | Gender strongly impacts survival |


