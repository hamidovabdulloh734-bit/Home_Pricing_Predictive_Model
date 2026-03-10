# House Price Prediction using Multivariable Linear Regression

This project predicts house prices using **Multivariable Linear Regression**.

The model uses different house features such as:

- area
- bedrooms
- bathrooms
- number of stories
- parking
- furnishing status
- and other house-related factors

The goal of this project is to understand how machine learning can be used to estimate house prices based on available data.

---

## Project Overview

In this notebook, I:

- loaded and explored the dataset
- checked for missing values
- identified categorical features
- converted categorical data into numeric values
- built a Linear Regression model
- trained the model on the dataset
- visualized feature importance
- predicted the price of a new house
- evaluated the model performance using metrics

This project is beginner-friendly and helps demonstrate the basic workflow of a machine learning regression problem.

---

## Dataset

The dataset used in this project is:

- `Housing.csv`

It contains information about houses, including price and several features that may affect the final value of a house.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Workflow

### 1. Data Loading
The dataset is loaded using Pandas and explored to understand its structure.

### 2. Data Cleaning
The notebook checks for missing values and prepares the dataset for modeling.

### 3. Encoding Categorical Features
Categorical values such as `yes/no` and furnishing status are converted into numeric form so the model can use them.

### 4. Feature Selection
The target variable is:

- `price`

The remaining columns are used as input features.

### 5. Model Training
A **Linear Regression** model is trained using the prepared dataset.

### 6. Prediction
The model is used to predict the price of a sample house based on given input values.

### 7. Evaluation
The model is evaluated using:

- **R² Score**
- **RMSE (Root Mean Squared Error)**

---

## Model Performance

According to the notebook results:

- **R² Score:** 0.68
- **RMSE:** 1,056,995

This means the model explains a good portion of the price variation, but there is still room for improvement.

---

## Example Prediction

The model can predict the price of a new house by using values such as:

- area
- number of bedrooms
- bathrooms
- stories
- parking
- furnishing status
- and more

This shows how machine learning can be applied to real-world housing data.

---

## Why I Made This Project

I created this project to practice:

- data analysis
- data preprocessing
- regression modeling
- model evaluation
- visualization

It is part of my learning journey in **Python, data science, and machine learning**.

---

## Future Improvements

Possible improvements for this project:

- train/test split for better evaluation
- feature scaling
- trying other regression models
- hyperparameter tuning
- better handling of categorical features
- improving prediction accuracy

---

## File in This Repository

- `Uy_narxini_bashorat_qilish.ipynb` — main notebook
- `Housing.csv` — dataset file

---

## How to Run

1. Clone this repository
2. Install the required libraries
3. Open the notebook
4. Run the cells step by step

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
