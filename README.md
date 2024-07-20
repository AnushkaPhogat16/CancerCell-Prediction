# Tumor Malignancy Prediction Using Logistic Regression

## Project Overview
This project aims to build a predictive model to classify tumors as malignant or benign using logistic regression. By leveraging various features from the dataset, we seek to develop a model that aids medical professionals in diagnosing tumors more accurately and making informed treatment decisions.

## Problem Statement
The objective is to classify tumors based on the dataset features into two categories: malignant (1) and benign (0). Accurate classification can help in early detection and treatment planning.

## Dataset
The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) Data Set. It is available from:
- [UCI Machine Learning Repository](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

### About the Dataset
Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. For more details, refer to: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].


## Project Workflow

### Load and Explore the Dataset
- Load the dataset and perform initial exploration to understand its structure and content.
- Display basic statistics and information about the dataset.

### Data Cleaning
- Visualize and handle missing values.
- Drop unnecessary columns that do not contribute to the analysis.

### Encoding Categorical Variables
- Convert categorical values in the `diagnosis` column to numeric values for model compatibility.

### Data Preparation
- Separate the target variable (`diagnosis`) from the feature set.
- Normalize the features to ensure uniform scaling.

### Splitting the Data
- Split the dataset into training and testing sets for model evaluation.

### Building the Logistic Regression Model
- Train a logistic regression model using the training data.
- Make predictions on the test set.

### Model Evaluation
- Evaluate the model’s performance using accuracy and classification metrics.
- Analyze the results to validate the model’s effectiveness.

## Files
- `data.csv`: The dataset used for prediction.
- `notebook.ipynb`: The Jupyter notebook containing the project code and analysis.

## Dependencies
Ensure the following Python libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

# Conclusion
This project successfully demonstrates the use of logistic regression to predict tumor malignancy. The model's performance was evaluated, providing insights into its accuracy and reliability for medical decision-making.
