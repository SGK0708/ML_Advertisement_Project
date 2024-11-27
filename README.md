# ML_Advertisement_Project

This project predicts the **Sales** outcome based on the advertisement budgets for **TV**, **Radio**, and **Newspapers** using various **Machine Learning** techniques, including **Linear Regression**, **Random Forest**, **Gradient Boosting**, **XGBoost**, **LightGBM**, and **Support Vector Regression (SVR)**.

## Dataset:
The dataset contains the following columns:
- **TV Ad Budget ($)**: The budget allocated for TV advertisements.
- **Radio Ad Budget ($)**: The budget allocated for Radio advertisements.
- **Newspaper Ad Budget ($)**: The budget allocated for Newspaper advertisements.
- **Sales ($)**: The sales generated, which is the target variable for prediction.

## Steps:
1. **Data Exploration**: Loaded and explored the dataset to understand the relationships between advertisement budgets and sales.
2. **Data Cleaning**: Handled missing values, checked for outliers, and performed any necessary transformations.
3. **Feature Selection**: Used **TV**, **Radio**, and **Newspaper** ad budgets as features and **Sales** as the target variable.
4. **Model Training**: Applied multiple machine learning models for predicting sales:
   - **Linear Regression** (Lasso, Ridge, ElasticNet)
   - **Random Forest Regressor**
   - **Gradient Boosting Regressor**
   - **XGBoost** and **LightGBM**
   - **K-Nearest Neighbors** (KNN)
   - **Support Vector Regression (SVR)**
   - **Decision Tree Regressor**
5. **Model Evaluation**: Evaluated model performance using metrics such as **Mean Squared Error (MSE)** and **R-squared**.

## Tools and Libraries:
- **Pandas**: Data manipulation.
- **Matplotlib/Seaborn**: Data visualization.
- **Scikit-learn**: For building and evaluating machine learning models.
- **XGBoost**: For XGBoost implementation.
- **LightGBM**: For LightGBM implementation.
- **Pickle**: For saving the trained models.
- **Jupyter Notebook**: For analysis and code execution.

