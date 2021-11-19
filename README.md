# Data_science_test_Xepelin
This is the submission to Xepelin's data science test by Teresita Eyzaguirre.

In the submission folder "xepelin_submission_folder" you can find 3 files:
- requirements.txt : necessary packages and its versions for running the code.
- data_test2.csv: input csv file
- data_science_xepelin_script.ipynb: jupyter notebook where I developed the test.

The chosen model was to forecast using the median, which yields the exact results as a support vector regression with hyperparameters 
C = 10, epsilon = epsilon = 0.001, gamma= 0.001 and kernel RBF.

These models have a train RMSE of 283187 which can be interpreted as 68% of the models predictions fall within $283187 of the actual value.
