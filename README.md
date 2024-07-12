# Diabetes Prediction Model

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model Training](#model-training)
6. [Evaluation](#evaluation)
7. [Results](#results)
8. [Contributing](#contributing)
9. [Contact](#contact)
10. [Author](#author)

## Introduction
This project uses the "Pima Indians Diabetes" dataset to predict which people are likely to develop diabetes. The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. The objective is to diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. All patients in this dataset are females at least 21 years old of Pima Indian heritage.

## Dataset
The dataset includes medical data for female patients of Pima Indian heritage who are at least 21 years old. The features include:

- **Pregnancies**: Number of times the patient has been pregnant.
- **Glucose**: Plasma glucose concentration a 2 hours in an oral glucose tolerance test.
- **BloodPressure**: Diastolic blood pressure (mm Hg).
- **SkinThickness**: Triceps skinfold thickness (mm).
- **Insulin**: 2-Hour serum insulin (mu U/ml).
- **BMI**: Body mass index (weight in kg/(height in m)^2).
- **DiabetesPedigreeFunction**: A function that scores the likelihood of diabetes based on family history.
- **Age**: Age of the patient (years).

The target variable is **Outcome**, which indicates whether the patient has diabetes (1) or not (0).

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/TimothyBelekollie/Diabetes_Prediction_model
    ```

2. Create a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Install JupyterLab if not already installed:
    ```bash
    pip install jupyterlab
    ```

## Usage
To use the Diabetes Prediction Model, follow these steps:

1. Launch JupyterLab:
    ```bash
    jupyter lab
    ```

2. Open the `lab1.ipynb` notebook.
3. Follow the instructions in the notebook to load the dataset, preprocess the data, train the model, and evaluate the results.

## Model Training
The model training process includes:
1. Data preprocessing (handling missing values, one-hot encoding for categorical features, and standardizing numerical features).
2. Splitting the data into training and testing sets.
3. Training a Naive Bayes classifier on the training data.

## Evaluation
The model is evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score

## Results
The model's performance on the testing set is as follows:
- Model Accuracy with training data: `0.7393`
- Model Accuracy with testing data: `0.7706`

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request for any improvements or additions.

## Contact
For any questions or inquiries, please contact Timothy Belekollie at:

- **Email**: [belekollietimothy2@gmail.com](mailto:belekollietimothy2@gmail.com)
- **LinkedIn**: [Timothy Belekollie](https://www.linkedin.com/in/timothy-belekollie-1b3a5321b/)
- **Twitter**: [@TimothyBelekol2](https://twitter.com/TimothyBelekol2)

## Author
- **GitHub**: [TimothyBelekollie](https://www.github.com/TimothyBelekollie)