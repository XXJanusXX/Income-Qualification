# Income-Qualification
Identify the level of income qualification needed for the families in Latin America.
Problem Statement Scenario:

Many social programs have a hard time ensuring that the right people are given enough aid. It’s tricky when a program focuses on the poorest segment of the population. This segment of the population can’t provide the necessary income and expense records to prove that they qualify.
In Latin America, a popular method called Proxy Means Test (PMT) uses an algorithm to verify income qualification. With PMT, agencies use a model that considers a family’s observable household attributes like the material of their walls and ceiling, or the assets found in their homes to
classify them and predict their level of need.
While this is an improvement, accuracy remains a problem as the region’s population grows and poverty declines.
The Inter-American Development Bank (IDB)believes that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.

Following actions should be performed:

•	Identify the output variable.

•	Understand the type of data.

•	Check if there are any biases in your dataset.

•	Check whether all members of the house have the same poverty level.

•	Check if there is a house without a family head.

•	Set poverty level of the members and the head of the house within a family.

•	Count how many null values are existing in columns.

•	Remove null value rows of the target variable.

•	Predict the accuracy using random forest classifier.

•	Check the accuracy using random forest with cross validation.


Identify the output variable.

To identify the output variable in a dataset, you will first need to load the dataset and understand the structure and content of the data. Here is an example of how you could do this in Python:

Load the dataset using a suitable library or module.

Inspect the structure of the dataset. This can be done by printing the shape of the dataset (number of rows and columns) and the column names.

Analyze the content of the dataset. Look at the values in the different columns and try to understand the meaning and relationship between them.

Based on your understanding of the dataset, identify the column or columns that represent the output variable. The output variable is typically the variable that you are trying to predict or estimate based on the other variables in the dataset.

