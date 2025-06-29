# real-estate-analysis
predicting apartment prices in Israel using data preprocessing, feature engineering, and machine learning models such as ElasticNet and Decision Trees.
# Real Estate Price Prediction in Israel 🏠🇮🇱

This project analyzes and predicts apartment prices in Israel using real-world housing data. The workflow includes:

## 📊 Data Processing
- Cleaning and filling missing values
- Feature engineering from text descriptions
- Address and neighborhood standardization

## 🧠 Models
Two main models were trained and evaluated:
- **Elastic Net Regression**
- **Decision Tree Regressor**

Both models were compared using RMSE and R² metrics, and feature importance was analyzed.

## 🧪 Evaluation
- 10-fold cross-validation
- Hyperparameter optimization using Grid Search
- Feature selection to improve performance

## 📈 Results
The Decision Tree model showed higher accuracy but was more prone to overfitting. Elastic Net provided more interpretable results and better generalization.

## 📁 Structure
- `notebooks/` – Exploratory Data Analysis and model training
- `preprocessing.py` – All data cleaning and preparation steps
- `train.csv` – Original training data
- `README.md` – Project overview

## 👨‍💻 Author
Bania Unger – Industrial Engineering & Management student, Ariel University

---

Feel free to explore, fork, or contribute!
