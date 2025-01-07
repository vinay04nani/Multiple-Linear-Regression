# Student Performance Prediction with Linear Regression

This repository contains Python code for building and evaluating a linear regression model to predict student performance based on various factors.

## Features:

* **Hours Studied**
* **Previous Scores**
* **Sleep Hours**
* **Sample Question Papers Practiced**

## Dependencies:

* pandas
* matplotlib
* scikit-learn

## Usage:

1. **Clone the repository:** `git clone <repository_url>`
2. **Install dependencies:** `pip install pandas matplotlib scikit-learn`
3. **Prepare data:** 
    - Ensure your data is in a CSV file named `Student_Performance.csv` with the following columns:
        - `Hours Studied`
        - `Previous Scores`
        - `Sleep Hours`
        - `Sample Question Papers Practiced`
        - `Performance Index` (target variable)
4. **Run the script:** `python student_performance_prediction.py`

## Script Functionality:

1. **Loads data:** Reads the `Student_Performance.csv` file into a pandas DataFrame.
2. **Handles missing values:** Replaces missing values (if any) with the mean value of the respective column.
3. **Splits data:** Divides the data into training and testing sets using `train_test_split()`.
4. **Trains model:** Trains a LinearRegression model on the training data.
5. **Makes predictions:** Uses the trained model to predict performance on the testing data.
6. **Evaluates model:** Calculates and prints the Mean Squared Error (MSE) and R-squared.
7. **Visualizes results:** Creates a scatter plot to visualize the actual vs. predicted performance.
8. **User input and prediction:** Prompts the user to input values for features and predicts the performance index.

## To improve this project:

* Implement more robust missing value handling techniques.
* Experiment with feature scaling (e.g., standardization).
* Tune hyperparameters of the model.
* Explore more advanced regression models (e.g., Ridge, Lasso).
* Add a user-friendly interface (e.g., using a library like Streamlit).

## Contributing:

Feel free to contribute to this project by submitting pull requests with improvements, bug fixes, or new features.
