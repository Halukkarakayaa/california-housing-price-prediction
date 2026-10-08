# California Housing Price Prediction

## Overview

This project focuses on predicting California housing prices using machine learning techniques.

The project uses the California Housing dataset and builds a regression model based on different property and geographic features. The workflow includes data exploration, preprocessing, visualization, model training, and performance evaluation.

## Dataset

The project uses the California Housing dataset, which contains information about housing districts in California.

The dataset includes features related to:

* Geographic location
* Housing characteristics
* Population
* Number of households
* Median income
* Housing value

The dataset is loaded directly from an online CSV source within the Python notebook.

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Workflow

The project follows these main steps:

1. Data loading
2. Data exploration
3. Data preprocessing
4. Handling missing values
5. Categorical feature encoding
6. Exploratory Data Analysis (EDA)
7. Correlation analysis
8. Train-test split
9. Machine learning model training
10. Model evaluation
11. Housing price prediction

## Data Preprocessing

Before training the model, the dataset is prepared for machine learning.

The preprocessing steps include:

* Exploring the dataset structure
* Checking for missing values
* Handling missing data
* Separating numerical and categorical features
* Applying One-Hot Encoding to categorical variables
* Preparing the feature matrix and target variable

## Exploratory Data Analysis

Exploratory Data Analysis is performed to better understand the relationships between the housing features and housing prices.

The project includes visualizations and correlation analysis to examine the relationships between different variables.

## Machine Learning Model

A **Random Forest Regressor** is used to predict housing prices.

Random Forest is an ensemble learning method that combines multiple decision trees to produce a regression prediction.

The dataset is divided into training and testing sets before the model is trained.

## Model Evaluation

The trained model is evaluated using the following regression metrics:

* **Mean Absolute Error (MAE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score**

These metrics are used to measure how accurately the model predicts housing prices.

<img width="402" height="329" alt="image" src="https://github.com/user-attachments/assets/aa2d6923-5854-4c97-8129-c1a29c608595" />


## Prediction

After training the model, the project can be used to estimate the price of a previously unseen house based on its available features.

## Project Structure

```text
california-housing-price-prediction/
│
├── california_housing_prediction.ipynb
├── README.md
└── images/
```

## How to Run

### 1. Clone the repository

```bash
git clone https://github.com/HalukKarakayaa/california-housing-price-prediction.git
```

### 2. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### 3. Open the notebook

```bash
jupyter notebook
```

Then open:

```text
california_housing_prediction.ipynb
```

## Future Improvements

Possible improvements for this project include:

* Comparing Random Forest with other regression algorithms
* Hyperparameter tuning
* Improving feature engineering
* Comparing different preprocessing approaches
* Further model optimization
* Adding additional model evaluation visualizations

## Author

**Ahmet Haluk Karakaya**

Computer Engineering Graduate

[GitHub](https://github.com/HalukKarakayaa)
