# 🧠 Obesity Risk - Multiclass Classification

This project aims to predict obesity risk levels using multiclass classification algorithms applied to a dataset containing dietary habits, physical activity, and demographic features. The goal is to build an accurate model capable of classifying individuals into multiple obesity risk levels, contributing to preventive public health strategies.

## 📁 Project Structure

Main file:
- `Obesity_risk_MClassification.ipynb`

Workflow:
1. Dataset loading and inspection
2. Data preprocessing (encoding, scaling)
3. Exploratory Data Analysis (EDA)
4. Feature engineering
5. Model training (baseline)
6. Hyperparameter tuning
7. Performance evaluation
8. Model selection
9. Final conclusions

## 📊 Dataset

- Source: [UCI Machine Learning Repository - Obesity Level Estimation](https://archive.ics.uci.edu/ml/datasets/Obesity+Level+Estimation)
- Records: 2111 entries
- Features: Nutrition habits, physical activity, BMI, age, gender, etc.
- Target: `NObeyesdad` (multiclass target including: Insufficient Weight, Normal Weight, Obesity Type I, and more)

## 🛠️ Tools & Technologies

- Python 3.9+
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Pipeline (Scikit-learn)
- OneHotEncoder, StandardScaler

## 📈 Models Evaluated

- Logistic Regression (Multinomial)
- Random Forest
- XGBoost (best performance after GridSearchCV tuning)

**Main evaluation metric**: accuracy, along with confusion matrix and per-class classification report.

## 🚀 Results

- Best model: **XGBoost**, with accuracy over 90%
- Most predictive features: BMI, physical activity frequency, fast food intake

## 📌 Conclusions

- Multiclass classification is well-suited for this problem, especially using gradient boosting models.
- Preprocessing and feature selection are key for building robust models in healthcare scenarios.

## 💡 Future Work

- Implement stratified cross-validation
- Analyze feature importances in tree-based models
- Deploy the model via a REST API
- Explore fairness metrics to assess model bias

## 📬 Contact

Marcelo Vidal  
[LinkedIn](https://www.linkedin.com/in/marcelo-vidal-bravo)  
