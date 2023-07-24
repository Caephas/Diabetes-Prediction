# Diabetes Prediction - Machine Learning Project

This is a Machine Learning project to predict whether a patient has diabetes or not, based on certain diagnostic measurements included in the dataset. The datasets consist of several medical predictor variables and one target variable, 'Outcome'. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

## Dependencies

This project is implemented in Python using the following libraries:

* numpy
* pandas
* sklearn

To install these libraries, use pip:

```bash
pip install numpy pandas sklearn
```

## Dataset

The dataset used in this project is the [Pima Indians Diabetes Database](https://www.kaggle.com/uciml/pima-indians-diabetes-database), downloaded from Kaggle. It is named `diabetes.csv`.

The datasets consist of several medical predictor variables and one target variable, 'Outcome'. 

## Implementation

The project follows the following steps:

1. Import the required libraries.
2. Load the dataset using pandas.
3. Conduct exploratory data analysis to understand the data.
4. Separate the data and labels.
5. Standardize the data.
6. Split the dataset into training and testing sets.
7. Train the SVM model on the training data.
8. Evaluate the model on both the training and test data.
9. Implement a prediction system to predict the results for any given input.

## Usage

This project can be used as a base to create a diabetes prediction model and make necessary adjustments according to requirements.

To use this project:

1. Clone the repository:
```bash
git clone <repository_link>
```
2. Install the requirements:
```bash
pip install -r requirements.txt
```
3. Open the Python notebook file in Google Colab, Visual Studio Code or Jupyter Notebook and run the cells sequentially.

Note: Ensure that the `diabetes.csv` file is in the same directory as your Python file.

## Results

The accuracy of the model on the training data is printed, followed by the accuracy on the test data. Finally, the model is used to predict a specific patient's outcome based on a given input. 
