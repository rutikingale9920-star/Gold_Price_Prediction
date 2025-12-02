# Gold_Price_Prediction
Gold Price Prediction using ML models with historical financial data. Includes regression (Random Forest) to predict actual gold price and classification (Logistic Regression, Decision Tree, XGBoost) to label prices as High/Low. Features preprocessing, visualization, and model evaluation.
-----Features-----

Predicts actual gold price using Random Forest Regressor

Classifies price trend (High/Low) using
✔ Logistic Regression
✔ Decision Tree
✔ XGBoost

Data preprocessing and cleaning

Exploratory Data Analysis (EDA)

Correlation heatmap, distribution plots & line graphs

Accuracy comparison and confusion matrices

-----Dataset-----

Name: gld_price_data.csv

Source: Kaggle

Rows: ~2290

Features: SPX, USO, SLV, EUR/USD, GLD

Derived Column: Price_Class (High = 1, Low = 0)

-----Technologies Used-----

Python

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn

XGBoost

-----Machine Learning Models-----
🔹 Regression

Random Forest Regressor (Predicts actual GLD price)

🔹 Classification

Logistic Regression

Decision Tree Classifier

XGBoost Classifier (Best accuracy)

-----Evaluation Metrics-----
For Regression:

R² Score

Actual vs Predicted Plot

For Classification:

Accuracy Score

Confusion Matrix

Precision, Recall & F1-score

Accuracy comparison chart

-----Future Enhancements-----

Add more financial indicators (interest rates, inflation)

Use LSTM/GRU models for time-series forecasting

Deploy using Flask/Streamlit

Real-time gold price prediction system

Hyperparameter tuning and model stacking
