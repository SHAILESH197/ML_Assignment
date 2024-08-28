# Documentation for Iris Dataset & Linear Regression Code

# Introduction

This code is a Python-based project that demonstrates data exploration using the Iris dataset and the application of linear regression on a mock dataset. It covers basic steps in data science and machine learning, including loading data, splitting data into training and testing sets, and evaluating model performance.

# Code Structure

 1. Importing Libraries

The code begins by importing necessary Python libraries, including:
- `pandas`: For data manipulation.
- `sklearn.datasets`: To load the Iris dataset.
- `sklearn.model_selection`: For splitting data into training and testing sets.
- `sklearn.linear_model`: To create and train a linear regression model.
- `sklearn.metrics`: To evaluate model performance.
- `numpy`: For numerical operations, such as generating random data.

 2. Dataset Exploration

The Iris dataset is loaded and converted into a Pandas DataFrame. Key operations include:
- Displaying the first 5 rows of the dataset.
- Checking the shape of the dataset (number of rows and columns).
- Generating summary statistics (mean, standard deviation, etc.).

 3. Data Splitting

The code selects the first two features of the Iris dataset for simplicity and splits the data into training and testing sets. This prepares the data for model training.

 4. Mock Dataset Generation

A mock dataset is generated to simulate a linear regression scenario:
- **Years of Experience**: Random values between 0 and 10.
- **Salary**: A linear function of `YearsExperience` with added noise to simulate real-world data.

This mock dataset is used in place of an external CSV file to train and test the linear regression model.

 5. Linear Regression Model

A linear regression model is created and trained on the mock dataset:
- **Training**: The model is trained using the training data (80% of the dataset).
- **Prediction**: The model predicts `Salary` values for the test data (20% of the dataset).
- **Evaluation**: The performance of the model is evaluated using Mean Squared Error (MSE).

 6. Output

The code outputs the following:
- Basic exploration results of the Iris dataset.
- The number of samples in the training and testing sets.
- The Mean Squared Error of the linear regression model, indicating its accuracy.

