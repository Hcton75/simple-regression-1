# simple-regression-1

## About the dataset
The dataset is from https://www.kaggle.com/datasets/mitgandhi10/dataset-for-simple-linear-regression to help in mastering simple liniear regression model.

The dataset contains 2 columns

        1. YearsExperience - Which shows the years of experience in the field
        2. Salary - Showing the salary according to the experience

## Business Overview
Does increase in experienceby years increase the salary 

## Modelling
Used Linear regression model to predict whether an increase in experience by years will lead to a increase in salary

To get better results, **StandardScaler** was used on the inpendent varible(YearsExperience). 

## Visualizing the standardscaled varible
<img width="578" height="413" alt="image" src="https://github.com/user-attachments/assets/bf2e4c6b-f47a-477d-a6e0-60a4afc80d78" />

## Plotting the line of best fit after the modelling
<img width="597" height="432" alt="image" src="https://github.com/user-attachments/assets/d9dd567b-b655-4a3e-b240-edea5e77f934" />

## Visualizing the predicted points
<img width="598" height="432" alt="image" src="https://github.com/user-attachments/assets/b11676de-db22-4531-98ea-b6d00d3baf93" />

For performance metrics, mean_squared error, mean_absolute error, root mean_squared_error and r2_score were used.
The outcomes were the following:
                                  **Mean Squared Error**: 37784662.46621304
                                  **Mean Absolute Error**: 5161.328710400178
                                  **Root Mean Squared Error**: 6146.923007994572
                                  **R squared**: 0.9414466227178215

The model is **94%** accurate.

## Conclusion\
From the model, An increase in **years of experience** leads to an increase in **Salary**



