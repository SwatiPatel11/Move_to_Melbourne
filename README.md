# Move_to_Melbourne

Problem statement:
Your friend from Iowa, whose housing problem you solved, is now moving to Melbourne for a new assignment Down Under. As you have solved his Iowa housing problem so well, he wants you to solve his Melbourne housing problem too. Armed with your new-found expertise in regularization, let's work on the Melbourne housing data using regularized regression. Each observation is a different house attribute with various features, like the number of properties that exist in the suburb, land size, building size, governing council for the area, real estate agent, price of the house, etc.

You can see that some of the features of Type, Method,SellerG,CouncilArea, and Regionname in the data are textual in nature. Don't worry, we have made things simple for you with some behind-the-scenes data preprocessing. You will learn about all these preprocessing techniques in a later concept. For now, let's concentrate on getting the Melbourne Housing data in your hands soon. :)

The dataset has details of 6830 house entries with 16 features. You need to predict the Price.

About the dataset
A zipped file containing following items is given:

train.csv
The data file train.csv contains the 4781 instances with the 16 features including the target feature.

test.csv
The datafile test.csv contains the 2049instances with the 15 features excluding the target feature.

sample_submission.csv
Explained under the Submission sub-heading

RegularizationDataDictionary.csv
The file contains data dictionary(Dictionary explaining what each feature of the dataset means) of the Insurance Claim dataset

regularization_student_template.ipynb
A template notebook explaining the task breakdown to solve the given problem statement (Learners are recommended to use it)

Submission
After training of the model on train.csv data, learner has to predict the target feature of the test.csv data using the trained model. The learner has to then submit a csv file with the predicted feature.

Sample submission file(sample_submission.csv) is given to you as reference to the format expected when you submit

Evaluation metrics
For this particular dataset we are using r2_score as the evaluation metric.

Submissions will be evaluated based on r2_score as per the below threshold.

Your r2_score score	Points earned for the Task
0.67 <= r2_score	100% of the available points
0.65 <= r2_score < 0.67	80% of the available points
0.63 < r2_score < 0.65	70% of the available points
r2_score <= 0.63	No points earned
Outcomes
The main objective of this task is to provide you with an open field where you can practise and work your way with a dataset end to end without any restrictions from our side. So feel free to play around the model until you arrive at your best solution.

In this project, you will apply the following concepts:

Linear Regression
Polynomial Regressor
Lasso Regressor
Ridge Regressor
R^2 Evaluation Metrics
After completing this project, you will have a better understanding of how to build a regularized regression model.

Skills Covered:
Data Aggregation
pandas
numpy
sklearn
Linear Regression
Regularization
