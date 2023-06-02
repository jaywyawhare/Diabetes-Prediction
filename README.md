# Diabetes Diagnosis Classification

This project focuses on classifying diabetes diagnosis using various machine learning models. The dataset contains several features such as glucose level, blood pressure, skin thickness, insulin, BMI, and more.

## Dataset

The dataset used for this project is sourced from the file diabetes.csv. It contains both categorical and numerical features related to diabetes diagnosis.

## Data Preprocessing

- Visual exploration: The distribution of numerical features is visualized using histograms to gain insights into the data.
- Handling missing values: Zero values in features such as glucose, blood pressure, skin thickness, insulin, and BMI are replaced with the mean value.
- Train-test split: The dataset is split into training, test, and validation sets for model evaluation.

## Models and Evaluation

Several classification models are implemented and evaluated for their performance in predicting diabetes diagnosis. The models include Decision Tree, Logistic Regression, Naive Bayes, K-Nearest Neighbors, Random Forest, Support Vector Machines, and more.

- Model training: Models are trained using the training set.
- Model evaluation: Performance metrics such as accuracy, precision, recall, and F1-score are calculated and visualized using confusion matrices.
- Model comparison: A comparison of model performance is presented through bar plots.

## Project Structure

The project consists of the following files:

- <b> Notebook/Notebook.ipynb </b>: Python script containing the code for breast cancer diagnosis classification.
- <b> data/diabetes.csv </b>: Dataset file containing breast cancer diagnosis and feature information.
- <b> requirements.txt </b>: Text file containing the list of required Python packages to run the project.

## Requirements

The following libraries are required to run the code:

- pandas
- numpy
- matplotlib
- seaborn
- sklearn

Install the dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Usage

To use this project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/jaywyawhare/Diabetes-Prediction.git
   ```

1. Navigate to the project directory:
   ```bash
   cd Diabetes-Diagnosis-Classification
   ```
   ```

   ```
