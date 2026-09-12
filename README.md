# Concrete Compressive Strength Prediction

## 📌 Project Overview

This project focuses on predicting the compressive strength of concrete using Machine Learning.

The model uses the quantities of concrete ingredients and the age of the concrete to estimate its compressive strength in MPa.

## 🎯 Objective

The main objective is to build a Machine Learning Regression Model that can predict concrete compressive strength based on its input features.

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Linear Regression

## 📊 Dataset

The dataset contains concrete composition information along with the corresponding compressive strength.

### Input Features

- Cement
- Blast Furnace Slag
- Fly Ash
- Water
- Superplasticizer
- Coarse Aggregate
- Fine Aggregate
- Age

### Target Variable

- Concrete Compressive Strength (MPa)

## 🔄 Project Workflow

1. Load the concrete dataset
2. Explore and understand the data
3. Check missing and duplicate values
4. Perform exploratory data analysis
5. Analyze feature correlations
6. Split the data into training and testing sets
7. Train a Linear Regression model
8. Evaluate the model using regression metrics
9. Predict compressive strength for a new sample

## 🤖 Machine Learning Model

A **Linear Regression** model is used to predict the compressive strength of concrete based on its composition and age.

## 📈 Model Performance

The Linear Regression model was evaluated using multiple regression metrics.

| Metric | Result |
|--------|--------:|
| MAE | 8.22 |
| MAPE | 29.55% |
| MSE | 114.27 |
| RMSE | 10.69 |
| R² Score | 0.56 |

The model achieved an R² score of approximately **0.56** on the test data, providing a baseline approach for predicting concrete compressive strength.

## 🔮 Sample Prediction

For a sample concrete mixture with an age of **28 days**, the model predicted a compressive strength of approximately **23.37 MPa**.

## 💡 Key Learning

This project provided hands-on experience with the complete Machine Learning workflow, including:

- Data exploration
- Data visualization
- Data analysis
- Model training
- Model evaluation
- Prediction using new data

## 📁 Project File

- `Concrete_Compressive_Strength_Prediction_(1).ipynb` – Complete Google Colab notebook containing the project code, explanations, visualizations, model evaluation, and predictions.

## 👩‍💻 Author

**Rutuja Ganorkar**
