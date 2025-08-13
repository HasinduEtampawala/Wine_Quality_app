## 🍷 Wine Quality Prediction with Machine Learning

Author: Hasindu Etampawala  
Index : ITBIN-2211-0186  

This project is a Streamlit web application that allows users to explore and analyze the Wine Quality Dataset from the UCI Machine Learning Repository.  
It provides interactive visualizations and prediction functionalities to estimate wine quality based on its physicochemical properties.

## 🖥️ Deployment
The application is designed to run locally in a conda environment using Streamlit.

Streamlit - 
Github Link -

## ✨ Features

📊 Interactive Data Visualization — Histograms, correlation heatmaps, and feature distribution charts.

🔍 Exploratory Data Analysis (EDA) — Analyze relationships between wine features and quality scores.

🤖 Machine Learning Predictions — Predict wine quality using a trained RandomForestRegressor pipeline.

🖱️ User-Friendly Interface — Sliders for each wine feature, prediction displayed instantly.

⚡ Optimized Performance — Cached dataset and model loading for faster execution.


## 📂 Dataset

Attributes:

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

quality (target variable)

## 🛠️ Project Workflow

1. Data Loading & EDA
Loaded the dataset with Pandas (delimiter ;).

Checked for missing values and outliers.

Visualized feature distributions and correlations.

2. Data Preprocessing
Verified no missing values.

Applied StandardScaler to normalize feature ranges.

Wrapped preprocessing + model in a scikit-learn Pipeline for ease of use.

3. Model Training
Selected RandomForestRegressor for robust handling of numeric features and non-linear patterns.

Tuned hyperparameters using RandomizedSearchCV.

Evaluated with RMSE, MAE, and R² score.

4. Model Saving
Saved the trained model pipeline using:

python
Copy
Edit
import joblib
joblib.dump(model, "model.pkl")
5. App Development
Built with Streamlit.

Sliders for feature input.

Predictions displayed via st.metric.

Dataset preview for reference.

## 📦 Project Structure

your-project/
├── app.py
├── requirements.txt
├── model.pkl
├── data/
│   └── dataset.csv
├── notebooks/
│   └── model_training.ipynb
└── README.md

