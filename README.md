# Boston Housing Regression Analysis

## Scenario

You are working as a **Data Scientist** and have been given a classic housing dataset.  
Your task is to:

- Understand which features are most important in predicting **median house value**.
- Compare **correlation-based insights** with **regression-based insights**.
- Explain why a variable that looks most important in **correlation** is not always the most important in the **regression model**.

This project was completed in a Jupyter Notebook as a self-learning exercise in **statistical thinking and regression analysis**.

---

## Objective

The main objectives of this project are:

1. **Explore the Boston Housing-style dataset** using summary statistics, visualizations and correlations.
2. **Build multiple linear regression models** to predict `MEDV` (median house value).
3. **Evaluate the impact of different predictors**:
   - `rm` – average number of rooms per dwelling  
   - `lstat` – % of lower-status population  
   - `ptratio` – pupil–teacher ratio
4. **Investigate feature importance** by:
   - Looking at the **correlation matrix**.
   - Comparing **R², Adjusted R² and RSS** when each variable is removed from the model.
5. **Develop statistical intuition** about:
   - Why the **most correlated** variable is not always the one that causes the **largest drop in R²**.
   - How **multicollinearity** affects regression interpretation.

---


## Skills Used

### Programming & Tools
- **Python**
- **Jupyter Notebook**
- **NumPy**
- **pandas**
- **Matplotlib** / **Seaborn**
- (Optionally) **scikit-learn** and/or **statsmodels** for regression

### Data & Statistics
- Exploratory Data Analysis (EDA)
  - Descriptive statistics  
  - Histograms, boxplots, scatterplots  
  - Correlation heatmaps
- **Regression Analysis**
  - Multiple Linear Regression  
  - R² and Adjusted R²  
  - Residual Sum of Squares (RSS)
- **Feature Importance & Multicollinearity**
  - Comparing models with and without certain predictors  
  - Understanding overlapping information between features

### Statistical Thinking
- Correlation vs Causation  
- Why “most correlated” ≠ “most important in the model”  
- Model comparison and interpretation

   