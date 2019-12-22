
## Identifying which factors predict future user adoption

The relax_data_science_challenge.pdf explains all the columns included in the tables. 

According to the pdf, an "adopted user" is defined as a user who has logged into the product on three separate days in at least one seven-day period.

We start this project by creating a binary column 'adopted' which indicates whether or not the user is considered an adopted user or not. This will be our target variable.

We also indicate whether or not the user has been invited by another user by creating the binary column 'invited'.

We use EDA to see the difference in behavior between the adopted users and those who aren't (are most of the adopted users included in the mailing list? were most of them invited by another user?)

Since this is a classification problem, we try three different machine learning models:

1) Logistic Regression

2) Random Forest Classifier

3) Gradient Boosting Classifier

In the end, we see which model performs best, and apply the .feature_importances_ feature to identify the variables that are most important in predicting user adoption.

