# 💳 Credit Score Analysis

This repository contains a **Credit Scoring project** developed with Python and Jupyter Notebooks.  
The main goal is to explore credit scoring techniques using machine learning and data preprocessing to predict the likelihood of default or creditworthiness.  

---

## 🧠 Project Overview

Credit scoring is an important task in finance and risk management, where a model learns to classify whether a person or entity is likely to repay credit or default. This project focuses on exploring, preparing data, applying models, and evaluating performance. :contentReference[oaicite:0]{index=0}

---

## 📁 Repository Structure
```
credit-score/
├── .ipynb_checkpoints/
├── CREDIT_SCORE_PROJETO_PARTE1.csv
├── X_train_balanced.csv
├── X_test_balanced.csv
├── y_train_balanced.csv
├── y_test_balanced.csv
├── credit-score-base.ipynb
├── credit-score-decision-tree.ipynb
└── README.md
```
---

## 🛠 Technologies Used

- Python  
- Jupyter Notebook  
- pandas, scikit-learn  
- Visualization libraries (matplotlib / seaborn)

---

## 📊 Notebooks

### 📌 `credit-score-base.ipynb`
Contains the initial data exploration, preprocessing, and baseline model evaluation.

### 📌 `credit-score-decision-tree.ipynb`
Explores the Decision Tree model for credit scoring and evaluates its performance.

---

## 🔍 About the Data

The dataset used in this project includes credit features and labels indicating credit status (good/bad / default risk).  
Balanced train and test sets are provided to improve model training quality.

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/Yuri-Alves/credit-score.git
cd credit-score
Create and activate a virtual environment (recommended):
```
```bash
python -m venv venv
# Linux / Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
Install dependencies:
```
```bash
pip install pandas scikit-learn matplotlib seaborn jupyter
Run the notebooks:
```
```bash
jupyter notebook
Open each .ipynb file in the browser to view and run the analysis.
```
📈 What Was Analyzed
 - Inside the notebooks, you will find:

 - Data exploration and visualization

 - Feature preprocessing and balancing

 - Train/test dataset handling

 - Model training (e.g., Decision Tree) and evaluation

 - Performance metrics for classification

📌 Future Improvements
Here are some suggestions for expanding the project:

 - Try additional models (Random Forest, Logistic Regression, XGBoost)

 - Perform cross-validation and hyperparameter tuning

 - Add ROC curves and confusion matrices for better evaluation

 - Write a summary section with key insights and conclusions

👤 Author
 - Yuri Moreira Alves
 - GitHub: https://github.com/Yuri-Alves

 - Computer Engineering student with a focus on Software Development and Data Science.

⚖️ License

 - This project is licensed under the MIT License.
 - Feel free to use, study, and adapt it.

