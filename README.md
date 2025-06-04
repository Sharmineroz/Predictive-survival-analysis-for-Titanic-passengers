![Titanic Ticket](https://github.com/Sharmineroz/Predictive-survival-analysis-for-Titanic-passengers/blob/main/Misc/Titanic.png)
# Titanic Survival Prediction Project 🚢

This project explores the use of supervised machine learning algorithms to predict passenger survival from the historic Titanic disaster. It was developed as part of a graduate-level data science and AI course and combines exploratory analysis, feature engineering, model training, and interpretation techniques. The project is inspired by educational challenges such as the Titanic Kaggle competition and serves as a learning tool to apply predictive analytics.

## 📌 Objective

To build and evaluate predictive models capable of identifying passengers most likely to survive the Titanic sinking, based on demographic and socio-economic features such as:

- Age
- Sex
- Ticket class (`Pclass`)
- Family relations onboard (`SibSp`, `Parch`)
- Fare
- Embarked port

## 🧪 Exploratory Data Analysis (EDA)

The EDA process included:

- Data cleaning and imputation of missing values
- Ordinal encoding of categorical features (`Sex`, `Embarked`, `Cabin`)
- Correlation analysis (point-biserial) with survival
- Contextual historical interpretation of findings

## ⚙️ Algorithms and Modeling

The following classification models were trained and evaluated:

- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Machines (SVM)
- K-Nearest Neighbors (KNN)
- Naive Bayes

### 🔍 Model Evaluation

Each model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrices
- ROC curves and AUC

XGBoost and SVM provided the best balance between identifying true survivors and minimizing false positives.

## 🔧 Hyperparameter Optimization

GridSearchCV was used to fine-tune key hyperparameters for:

- Logistic Regression
- XGBoost
- SVM

Results showed marginal or no improvements, suggesting optimal performance was already close to the defaults.

## 💡 Interpretability and Insights

SHAP values were used to understand feature importance. Key findings:

- `Sex_female` was the most influential variable (supporting the "women and children first" policy).
- Passengers in 1st class and those paying higher fares had a higher survival rate.
- Large families and lower-class passengers had reduced survival likelihood.

## 📁 Project Structure

```
titanic-survival-prediction/
├── data/                   # Titanic dataset
├── notebooks/              # Jupyter notebooks (EDA and modeling)
├── models/                 # Trained models (optional)
├── README.md               # Project documentation
└── requirements.txt        # Project dependencies
```

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone https://github.com/your_username/titanic-survival-prediction.git
cd titanic-survival-prediction
```

2. Install required libraries:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook notebooks/EDA_Titanic.ipynb
```

## 👨‍💻 Authors

- Juan J. Bonilla
- Ricardo Muñoz
- Valentina Isaza
- Nelcy L. Zapata

Graduate students – Master's in Artificial Intelligence and Data Science  
Universidad Autónoma de Occidente – Cali, Colombia

## 📜 License

This project is licensed under the MIT License.

## 📚 References

Several academic references were consulted, including:

- [Sherlock et al. (2018)](https://arxiv.org/abs/1810.09851)
- [Amalia & Rahayu (2023)](https://journal.binus.ac.id/index.php/ijcshai/article/view/12163)
- [Liao et al. (2023)](https://www.ewadirect.com/proceedings/aemps/article/view/19451)
- [Elements of Statistical Learning – Hastie et al. (2009)](https://web.stanford.edu/~hastie/ElemStatLearn/)
- [Lundberg & Lee (2017) – SHAP](https://github.com/slundberg/shap)
- [Chen & Guestrin (2016) – XGBoost](https://arxiv.org/abs/1603.02754)




