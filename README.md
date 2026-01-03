# AI Disease Prediction System

A machine learning-based system that predicts diseases based on patient-reported symptoms using supervised learning techniques.

---

## Project Overview
This project aims to assist in early-stage medical decision-making by predicting possible diseases from a given set of symptoms. The system is built using classical machine learning models and demonstrates a complete end-to-end ML pipeline.

---

## Machine Learning Models Used
- Bernoulli Naive Bayes  
- Decision Tree Classifier  
- Random Forest Classifier  

The models were trained and evaluated using a stratified train-test split to preserve class distribution.

---

## Model Performance
| Model | Accuracy |
|------|----------|
| Naive Bayes | 100% |
| Decision Tree | 97.7% |
| Random Forest | 100% |

> Note: High accuracy is achieved due to a clean, well-structured dataset with repeated disease samples.

---

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Joblib  

---

## How to Run
1. Clone the repository  
2. Install dependencies using `pip install -r requirements.txt`  
3. Open the notebook in the `notebook/` folder  
4. Run all cells to train models and test predictions  

