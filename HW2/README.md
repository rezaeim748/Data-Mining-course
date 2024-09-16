
# Data Mining Homework 2 - Practical

This repository contains the second practical homework for the Data Mining course, focusing on data preprocessing, regression, and classification tasks using various machine learning techniques.

## Technologies Used:
- **Python**
- **Pandas**: Data manipulation.
- **NumPy**: Numerical operations.
- **Scikit-learn**: Machine learning algorithms.
- **Matplotlib & Seaborn**: Data visualization.

## Homework Overview:
### 1. Data Preprocessing:
- Load the `worldcities.xlsx` dataset.
- Add a `Population Level` column by categorizing the population into four quartiles: Low, Mid, High, and Over.
- Handle missing data by dropping empty columns and encoding categorical variables.
- Normalize numerical data using Min-Max scaling.

### 2. Regression Models:
- Linear Regression and Polynomial Regression (degree 1 and 2) are implemented to predict the population using the other features.
- Model evaluation is based on Mean Squared Error (MSE) and R-squared.

### 3. Classification Models:
- Predict the `Population Level` using several classifiers:
  - Decision Tree.
  - Random Forest.
  - K-Nearest Neighbors (K=2, 3, 5).
  - Support Vector Machine (Linear and Non-linear).
- Model evaluation is based on accuracy and mean squared error (MSE).

## How to Run
1. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

2. Load the Jupyter Notebook:

```bash
jupyter notebook DM-HW2-Practical.ipynb
```

3. Follow the instructions within the notebook to execute each task.
