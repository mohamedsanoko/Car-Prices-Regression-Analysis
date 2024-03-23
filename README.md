# Used Car Price Prediction Analysis

This Jupyter notebook represents a multiple regression analysis aimed at predicting the price of a used car based on its specifications. The analysis utilizes various Python libraries, including numpy, pandas, statsmodels, matplotlib, sklearn, and seaborn.

## Project Description

### Variables:
1. Brand: Brand of the car (Categorical variable).

2. Price: Price of the car (Numerical variable).

3. Body: Body type of the car (Categorical variable).

4. Mileage: Mileage of the car (Numerical variable).

5. Engine Volume: Engine volume of the car (Numerical variable).

6. Engine Type: Type of engine in the car (Categorical variable).

7. Year: Year of Production of the car (Numerical variable).

8. Model: Model of the car (Categorical variable).

### Preprocessing:
1. Exploring the descriptive statistics of the variables.

2. Determining the variables of interest based on the descriptive statistics.

3. Dealing with missing values.

4. Exploring the PDFs of numerical variables.

5. Dealing with outliers.

6. Checking and relaxing the OLS assumptions (Linearity, No endogeneeity, Normality and homoscedasticity, No autocorrelation, No mullticollinearity).

7. Create dummy variables for categorical data.

8. Rearranging the data columns in a convenient order.

### Linear Regression:
1. Declaring the inputs and the targets.

2. Scaling the data.

3. Splitting the data into a training and a testing set.

4. Create the regression.

5. Finding the weights and bias of the regression.

### Evaluation of the Model:
1. Evaluating the model performance on the training data by plotting predicted values against observed values, and visualizing residuals.

2. Evaluating the model performance on the test data by plotting predicted values against observed values, and visualizing residuals.

3. Creating a summary table of the regression and its results.

## Running the Notebook
1. Ensure all required Python libraries are installed.

2. Open the notebook file in a Jupyter environment.

3. Execute each cell in a sequential order to run the analysis step-by-step.

## Conclusion
This project demonstrates the process of building a multiple regression model to predict used car prices based on various features. It involves data preprocessing, model development, and evaluation to create a reliable predictive model. Further improvements and optimizations can be explored based on specific requirements and insights gained from the analysis.
