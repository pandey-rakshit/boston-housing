# ML Project : Linear Regression - Boston-Housing

## **Problem Statement:**

You are tasked with developing a predictive model to estimate the median value of owner-occupied homes (MEDV) in various neighborhoods of Boston. To achieve this, you will use the Boston Housing dataset, which contains various features describing different aspects of the neighborhoods.

### **Dataset Description:**

The Boston Housing dataset includes the following features:

1. CRIM: Per capita crime rate by town.
2. ZN: Proportion of residential land zoned for large lots.
3. INDUS: Proportion of non-retail business acres per town.
4. CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise).
5. NOX: Nitrogen oxide concentration (parts per 10 million).
6. RM: Average number of rooms per dwelling.
7. AGE: Proportion of owner-occupied units built before 1940.
8. DIS: Weighted distance to employment centers.
9. RAD: Index of accessibility to radial highways.
10. TAX: Property tax rate.
11. PTRATIO: Pupil-teacher ratio.
12. B: Proportion of residents of African American descent.
13. LSTAT: Percentage of lower status population.

### **Objective:**

Your objective is to build a simple linear regression model that predicts the median value of homes (MEDV) based on a single feature, specifically the average number of rooms per dwelling (RM). The goal is to create a model that accurately estimates the MEDV using the RM feature.

### **Tasks:**

1. Load the Boston Housing dataset from the provided source.

2. Preprocess the dataset by selecting the RM feature as the independent variable (X) and the MEDV as the dependent variable (y).

3. Split the dataset into training and testing sets (e.g., 80% for training and 20% for testing) to evaluate the model's performance.

4. Develop a simple linear regression model using the training data, where you predict MEDV based on RM.

5. Evaluate the model's performance on the testing data using various metrics such as RMSE, MAE, MAPE, R<sup>2</sup>, and Adjusted R<sup>2</sup>.

6. Visualize the model's predictions by plotting the regression line against the actual data points.
