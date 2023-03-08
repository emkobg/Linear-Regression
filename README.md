# Linear-Regression by Emil.io

Linear Regression on the Palmer Penguins Dataset

This project is a demonstration of linear regression on the Palmer Penguins dataset, which contains information about various physical characteristics of three species of penguins found in the Palmer Archipelago in Antarctica.
Dataset

The dataset used in this project is available as a CSV file named penguins.csv. It contains 344 rows and 7 columns, including the penguins' species, island of origin, physical characteristics, and sex.
Approach

The goal of this project is to build a linear regression model to predict the body mass of a penguin based on its flipper length. To achieve this goal, the following steps were taken:

    Load the data into a pandas DataFrame using pd.read_csv.
    Select the columns of interest (flipper_length_mm and body_mass_g) and remove any rows with missing data using df.dropna.
    Split the data into a training set and a test set using train_test_split from sklearn.
    Fit a linear regression model to the training data using LinearRegression from sklearn.
    Evaluate the model's performance on the test data using mean_squared_error and r2_score from sklearn.

Results

The linear regression model achieved a mean squared error of 233558.6 and an R^2 score of 0.73 on the test data, indicating that it can explain about 73% of the variance in the body mass of the penguins based on their flipper length. The following plot shows the scatterplot of flipper length versus body mass, as well as the regression line fitted by the model:

scatterplot
Conclusion

Linear regression is a simple yet powerful technique for predicting a continuous variable from one or more predictor variables. In this project, we demonstrated how to build and evaluate a linear regression model on the Palmer Penguins dataset to predict the body mass of a penguin based on its flipper length. The results suggest that flipper length is a good predictor of body mass in penguins, although there is still some variability that cannot be explained by this model. Further exploration of the dataset and alternative modeling approaches could help improve the accuracy of the predictions.
