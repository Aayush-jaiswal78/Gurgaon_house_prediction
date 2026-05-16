🏠 Gurgaon House Price Prediction

A Machine Learning project that predicts house prices using structured housing data. This project builds a complete pipeline including data preprocessing, model training, and inference using Scikit-learn.

📌 Project Overview

This project focuses on predicting median house values based on various features such as income, location, and housing attributes.

It includes:
Data preprocessing pipeline
Feature engineering
Model training using ensemble learning
Model saving & loading
Prediction (inference) system


⚙️ Tech Stack
Python 🐍
NumPy
Pandas
Scikit-learn
Joblib (for model serialization)

📂 Project Structure
📁 Gurgaon-House-Price-Prediction
│── main.py              # Main script (training + inference)
│── housing.csv          # Dataset
│── input.csv            # Test input data (auto-generated)
│── output.csv           # Predictions (auto-generated)
│── model.pkl            # Trained model
│── pipeline.pkl         # Preprocessing pipeline
│── README.md            # Project documentation


🚀 How It Works
1. Data Preprocessing
Missing values handled using median imputation
Numerical features scaled using StandardScaler
Categorical features encoded using OneHotEncoder

2. Pipeline Creation
A full pipeline is created using:
Pipeline
ColumnTransformer

3. Model Training
Model used:
👉 RandomForestRegressor
Data is split using Stratified Sampling
Model is trained and saved as model.pkl

4. Inference
Loads saved model and pipeline
Transforms input data
Generates predictions
Saves results to output.csv

📊 Features Used
Median Income
Housing Attributes
Ocean Proximity (Categorical Feature)
Other numerical features from dataset
📈 Future Improvements
Add Gurgaon-specific dataset 🏙️
Deploy using Flask / FastAPI 🌐
Add visualization dashboard 📊
Hyperparameter tuning 🔧
🤝 Contributing

Feel free to fork this repo and improve it!

📧 Contact

Aayush Jaiswal
📩 jaiswalaayush78@gmail.com
🔗 GitHub: https://github.com/Aayush-jaiswal78

⭐ If you like this project

Give it a star ⭐ on GitHub!
