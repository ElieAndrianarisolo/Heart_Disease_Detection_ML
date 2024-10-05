# Heart Disease Detection using Machine Learning

## Project Overview
This project aims to predict whether a person has heart disease based on several medical factors. The project uses machine learning techniques, specifically logistic regression, to build a predictive model. The dataset used contains various health metrics of individuals and a target variable that indicates whether they are healthy or have heart disease.

## Technologies Used
- **Python**: The programming language used to develop the machine learning model.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **scikit-learn**: For machine learning tasks, including model building and evaluation.

## Dataset
The dataset used in this project is `heart_disease_data.csv`, which contains features like age, blood pressure, cholesterol levels, etc., and a target column:
- **Target = 1**: The individual has heart disease.
- **Target = 0**: The individual is healthy.

## Project Structure
1. **Data Processing**: The dataset is loaded and explored. Features are separated from the target variable to prepare for model training.
2. **Model Training**: A logistic regression model is trained using the provided dataset.
3. **Model Evaluation**: The accuracy of the model is calculated using test data.
4. **Predictive System**: A system is built to predict heart disease based on new input data.
