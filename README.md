# MSCS_634_Lab_4 – Regression Analysis with Regularization Techniques

#Overview
This lab focuses on implementing and comparing different regression techniques using the Diabetes dataset from sklearn. The objective is to understand how various regression models perform and how regularization methods help prevent overfitting.

#Objectives
- Implement Simple Linear Regression
- Implement Multiple Linear Regression
- Apply Polynomial Regression
- Use Ridge and Lasso Regression for regularization
- Evaluate models using MAE, MSE, RMSE, and R²
- Visualize predictions and model performance

#Dataset
The Diabetes dataset contains medical predictor variables such as age, BMI, and blood pressure. The target variable represents disease progression after one year.

#Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

#Steps Performed
1. Loaded and explored the dataset
2. Split data into training and testing sets
3. Applied:
   - Linear Regression (single feature)
   - Multiple Regression (all features)
   - Polynomial Regression
4. Implemented:
   - Ridge Regression
   - Lasso Regression
5. Evaluated models using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R-squared (R²)
6. Compared model performance visually

#Key Insights
- Multiple regression performed better than simple linear regression
- Polynomial regression can lead to overfitting with higher degrees
- Ridge regression reduces coefficient magnitude and improves stability
- Lasso regression performs feature selection by shrinking coefficients to zero
- Regularization helps improve model generalization

#Challenges Faced
- Selecting the optimal polynomial degree
- Choosing appropriate alpha values for Ridge and Lasso
- Balancing overfitting and underfitting

#Repository Structure
- Lab4.ipynb
- README.md
