# Salary Prediction using Machine Learning

This repository demonstrates the implementation of a salary prediction model using linear regression. The model predicts an individual's salary based on years of experience using the provided dataset.

## Files in this Repository

- **Salary Linear Regression Model.ipynb**: Jupyter notebook containing the implementation of the linear regression model to predict salary based on years of experience.
- **Salary.csv**: The dataset used to train the model, containing columns such as years of experience and salary.

## Dataset

The dataset used for this project, **Salary.csv**, includes the following columns:

- **Years of Experience**: The number of years of experience the individual has.
- **Salary**: The annual salary of the individual in USD.

### Sample Data

| Years of Experience | Salary    |
|---------------------|-----------|
| 1.1                 | 39343.00  |
| 1.3                 | 46205.00  |
| 1.5                 | 37731.00  |
| 2.0                 | 43525.00  |
| 3.0                 | 39891.00  |

## Steps to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Amandeep1912/Salary-Prediction-using-Machine-Learning.git
```

### 2. Install Dependencies

Make sure you have the required libraries installed:
```bash
pip install pandas numpy scikit-learn matplotlib
```

### 3. Open the Jupyter Notebook

To run the code, open the **Salary Linear Regression Model.ipynb** notebook in a Jupyter notebook environment or Google Colab.

```bash
jupyter notebook "Salary Linear Regression Model.ipynb"
```

### 4. Run the Cells

Run each cell in the notebook to load the data, preprocess it, train the linear regression model, and make predictions on salaries based on years of experience.

## Model Explanation

The project uses a simple **Linear Regression** model to predict the salary based on the years of experience of the employee. The linear regression model tries to find the relationship between the years of experience and the salary in the dataset.

### Steps in the Notebook:
1. **Data Loading**: The dataset is loaded using pandas.
2. **Data Preprocessing**: The data is cleaned and prepared for training.
3. **Model Training**: A Linear Regression model is trained using the training data.
4. **Prediction**: The model is used to predict the salary for given years of experience.
5. **Evaluation**: The model's performance is evaluated using metrics like Mean Absolute Error (MAE) or R².
