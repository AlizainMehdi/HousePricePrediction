# HousePricePrediction
📊 Project Overview: House Price Prediction

This project focuses on predicting house prices using machine learning, specifically the XGBoost Regressor model.

🎯 Objective

To build a model that can accurately predict house prices based on different features such as income, location, and housing characteristics.

📂 Dataset
Uses California Housing Dataset from Scikit-learn
Contains features like:
Median income
House age
Average rooms
Population
Target variable: House price
⚙️ Project Steps
1. Data Collection & Loading
Dataset loaded using sklearn
Converted into a pandas DataFrame
2. Data Preprocessing
Added target column (price)
Checked:
Shape of data
Missing values
Statistical summary
3. Data Analysis
Correlation matrix created
Heatmap used to understand relationships between features
4. Data Splitting
Features (X) and target (Y) separated
Split into:
Training data (80%)
Testing data (20%)
5. Model Training
Used XGBoost Regressor
Model trained on training data
6. Model Evaluation
Predictions made on:
Training data
Testing data
Performance measured using:
R² Score (accuracy)
Mean Absolute Error (MAE)
7. Visualization
Scatter plot used to compare:
Actual prices vs Predicted prices
📈 Outcome
The model learns patterns from housing data
It predicts house prices with reasonable accuracy
Performance is validated using test data
💡 Conclusion

This project demonstrates how machine learning (XGBoost) can be applied to real-world problems like price prediction by following steps such as data preprocessing, training, and evaluation.
