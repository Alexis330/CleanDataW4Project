# CleanDataW4Project

This is a course project for "Getting and Cleaning Data".

This project includes a R script called run_analysis.R, performs the following:

1. Download raw data from web.

2. Read both the train and test data and merge them into x(measurements), y(activity) and subject, respectively.

3. Load the data(x's) feature, activity info and extract columns named 'mean'(-mean) and 'standard'(-std). Modify column names to be descriptive. (-mean to Mean, -std to Std, and remove symbols such as -, (, ))

4. Extract data by selecting columns(from step 3) and merging x, y(activity) and subject data. Next, replace y(activity) column with its name by referring activity label.

5. Create a 'Tidy Data' that consists of the average (mean) of each variable for each subject and each activity. The result is saved as tidy_dataset.txt.



