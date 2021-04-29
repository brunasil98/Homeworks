# Car Price Prediction

In this skill drill, you are being asked to build a multiple regression model that predicts the price of a car based on numerous numerical features. You will also try to improve the performance of your models through dimensionality reduction using PCA.

## Instructions

### Multiple Linear Regression

1. Read the csv file into a pandas DataFrame.

2. Select our independent X variables, and our dependent y variable.

3. Split the data into training and testing.

4. Create a LinearRegression model and fit it to the training data.

5. Use the X_train & y_train to calculate the R2 in-sample value (training data).

6. Use the X_test & y_test to calculate the R2 out-of-sample value (testing data).

### Principal Component Analysis

7. Run a Principal Component Analysis and create a Components DataFrame.

8. Run the code to generate the Features vs Principal Components correlartion matrix.

9. Create a Scree Plot.

10. Print the Cumulative Variance Explained.

11. Update `n` to be the varible that reaches 80% variance explained.

12. Split the data into training and testing with the new cumulative_df.

### PCA Multiple Linear Regression

13. Create a new LinearRegression model and fit it to the training data.

14. Use the new X_train & y_train to calculate the R2 in-sample value (training data)

15. Use the new X_test & y_test to calculate the R2 out-of-sample value (testing data)

Comapre the results of the non-PCA and PCA model and consider why one performs better on testing data than the other. 

---

© 2021 Trilogy Education Services, a 2U, Inc. brand. All Rights Reserved.
