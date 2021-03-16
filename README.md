# LendingClub

The Lending Club is an online peer-to-peer lending company that offers people the ability to take out and give loans to their peers. The Lending Club published the 2007-2018 subset of its lending data a few years ago. This data is available on Kaggle, and it is what we will be using for our final project. This dataset consists of 145 interrelated columns, and roughly 2.26 million rows.

A critical business risk for the Lending Club is borrowers failing to pay their loans. Our team wishes to understand what factors are related or cause the bad loan. We would also like to predict if a loan would be charged off or not based on the features of each loan. After collecting the data, our team will first prepare the data, including coping with missing values, removing variables that are irrelevant to our question, winsorizing and standardizing numeric variables, encoding categorical variables. We will then explore the data using visualization techniques.To further reduce the number of variables, feature selection methods will be applied. We will compute a correlation matrix for all the numeric variables to drop the variables that contain similar information. After the correlation analysis, we will build decision trees using random forest, with the loan status (charged off or not) as the target variable. We are particularly interested in using some of the following methods to predict if a loan will be charged off or not:

1. Logistic Regression
2. Random Forest
3. Gradient Boosting Trees


Finally, we will evaluate and compare the performance of our models. We will use AUC, Recall Precision and F1 score as metrics to evaluate our models. To compare the models, we will use "Recall" in terms of our business problem because it shows the ability of the model to find all cases where the loan is Charged Off. In this way, investors and Lending Club can detect the risky behaviors in the early stages and conduct the corresponding actions to reduce the possible loss.
