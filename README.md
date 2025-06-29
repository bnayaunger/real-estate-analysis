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

## 📂 Project Files

- `my_project.ipynb` – Main Jupyter notebook containing data processing, model training and evaluation.
- `train.xlsx` – Raw dataset used for training.
- `ElasticNet_model.pkl` – Saved Elastic Net regression model.
- `decision_tree_model.pkl` – Saved Decision Tree Regressor model.
- `all_params.pkl` – Contains all preprocessing parameters (e.g. scalers, encoders, and statistical values) extracted from the training set. These are used to ensure consistent transformation of the test data, identical to the training pipeline.

- `README.md` – Project overview and documentation.


## 👨‍💻 Author
Bania Unger – Industrial Engineering & Management student, Ariel University

---

Feel free to explore, fork, or contribute!
