# Predicting Life Expectancy

## Objective
Creating a linear regression model to predict life expectancy based on data related to health, economy and education of each country. Two linear models were to be created: one detailed model using all features of the dataset which help predict life expectancy, and one sensitive model, which excludes features that could give rise to negative connotations. A function which took the user's input to predict their life expectancy based on these models was to be created.

## Results
We successfully created two models, which can be viewed in the Modelling folder, the Detailed Model achieving an Root Mean Sqaured Error (RMSE) of less than 2, and the Sensitive Model achieving an RMSE of just over 2. This means that the life expectancy function predicts a person's lifetime with an average error of about 2 years. We successfully created a function which allows the user to input their own data and calculate their lifetime in years. Users have the option to choose between the detailed or sensitive model, and if a user chooses not to input an answer, the mean of the data is inputted instead.
