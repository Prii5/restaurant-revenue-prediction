# Restaurant Revenue Prediction

This project aims to predict monthly revenue for restaurants based on various features like location, cuisine type, promotions, and customer reviews. It employs multiple regression techniques and includes exploratory data analysis, preprocessing, visualization, and model evaluation steps.


## Objective

To build regression models that accurately predict restaurant monthly revenue


## Exploratory Data Analysis (EDA)

- Checked for duplicates and missing values
- Descriptive statistics and data types
- Distribution plots for numerical and categorical features
- Correlation heatmap
- revenue analysis by Cuisine_Type and Promotions


## Visualizations

- KDE & histogram plots for all numerical variables
- Count plots for categorical features
- Bar and box plots to compare Monthly_Revenue across Cuisine_Type and Promotions
- Correlation matrix to identify linear relationships
- Scatter plots of features vs revenue



## Data Preprocessing

- One-Hot Encoding for categorical variable
- Train-test split before encoding to prevent data leakage
- Separate treatment of training and testing sets


## Modeling

Four models were trained and evaluated:
1. **Linear Regression**
2. **Random Forest Regressor**
3. **Ridge Regression** with GridSearchCV
4. **Lasso Regression** with GridSearchCV


## Evaluation Metrics

Each model was evaluated using:
- **Root Mean Squared Error (RMSE)**
- **R² Score**

All models were compared based on performance on the test set.


##  Tech Stack

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (for modeling and metrics)
