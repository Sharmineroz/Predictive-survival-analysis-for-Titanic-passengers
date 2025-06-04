![Titanic Ticket](https://github.com/Sharmineroz/Predictive-survival-analysis-for-Titanic-passengers/blob/main/Misc/Titanic.png)
# Titanic Survival Prediction 🚢

This project was developed as part of the **Machine Learning** course. Our goal was to apply supervised learning techniques to predict which passengers survived the sinking of the Titanic, using the well-known dataset from [Kaggle](https://www.kaggle.com/competitions/titanic).

## 🔍 Objective

Build a classification model to predict whether a passenger survived, based on features such as age, sex, ticket class, among others.

---

## 🧪 Exploratory Data Analysis (EDA)

We conducted a thorough data analysis to better understand the distributions and relationships between features:

- Distribution visualizations (age, fare, class, etc.)
- Missing values analysis
- Categorical variable impact (sex, class, embarked) on survival
- Feature engineering, including:
  - Grouping titles extracted from names
  - Creating age bins

---

## 🤖 Trained Models

Several classification models were trained and evaluated:

- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**
- **XGBoost**

We used metrics such as *accuracy*, *precision*, *recall*, and *f1-score* to evaluate model performance. Cross-validation was applied for more robust evaluation.

---

## 🧰 Tools and Libraries

- Python 3
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost

---

## 📁 Repository Structure
```
titanic-survival-prediction/
│
├── data/                 # Original dataset (train.csv, test.csv)
├── notebooks/
│   └── EDA_Titanic.ipynb # Exploratory analysis and model training
├── models/               # Trained models (optional)
├── README.md             # This file
└── requirements.txt      # Required libraries

```

---
📌 Contributors
- Valentina Isaza
- Juan José Bonilla
- Nelcy Lucía Zapata
- Ricardo Muñoz




