
🍷 Wine Quality Prediction
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

A machine learning web application that predicts wine quality (Good / Low) based on chemical composition attributes, built using scikit-learn and deployed with Streamlit Cloud.
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Live Demo
🔗 Streamlit App: https://winequalityapp-itpvyxs5kpbdt6q9pehwgq.streamlit.app/
🔗 GitHub Repo: https://github.com/HasinduEtampawala/Wine_Quality_app

----------------------------------------------------------------------

👤 Author
Name: G R H S C Etampawala || Index No: ITBIN-2211-0186

-----------------------------------------------------------
## Dataset
Source: Wine Quality Dataset (Red Wine) - Kaggle
Samples: 1,599 wine samples
Features: 11 numerical physicochemical properties
Target Variable: Wine quality score (0–10), transformed to binary classification:
1 = Good Quality (score ≥ 7)
0 = Low Quality (score < 7)
Feature	Description
fixed acidity	Fixed acidity in g/dm³
volatile acidity	Volatile acidity in g/dm³
citric acid	Citric acid in g/dm³
residual sugar	Sugar content in g/dm³
chlorides	Salt content in g/dm³
free sulfur dioxide	Free SO₂ (mg/dm³)
total sulfur dioxide	Total SO₂ (mg/dm³)
density	Density (g/cm³)
pH	Acidity level
sulphates	Sulphates in g/dm³
alcohol	Alcohol percentage

-------------------------------------------------

## 🧠 Machine Learning Pipeline
Models Used:
Logistic Regression – Baseline linear model
Random Forest Classifier ✅ (selected model)
Evaluation Metrics:
Accuracy score
Classification report (Precision, Recall, F1-score)
Confusion matrix

--------------------------------------------------------------------------------------------------------------------------------
## 📂 Project Structure
├── app.py ├── requirements.txt ├── model.pkl ├── data/ │ └── dataset.csv ├── notebooks/ │ └── model_training.ipynb └── README.md 

