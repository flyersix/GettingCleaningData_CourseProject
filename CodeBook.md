# GettingCleaningData_CourseProject
# CodeBook.md

This is a code book that describes the variables, the data, and any transformations or work that was performed on the raw data.


# Analysis Summary

The purpose of this project is to demonstrate my ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.

To prepare the final tidy data set, I was tasked with creating one R script called run_analysis.R that does the following:
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each 			           activity and each subject.

# Raw Data

Raw data = Human Activity Recognition Using Smartphones Data Set
The raw data can be downloaded here:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

For more information on raw data files and other variables contained in the set, see README.txt provided in the data set.

# Data Prep

run_analysis.R performs all the necessary data cleaning and other prep necessary to obtain the required tidy data step for the Course Project
Steps required to manipulate the data into the final today dat set form are outlined in more detail in the Analysis Summary section of this code book.  Detailed comments explaining each procedure are also included throughout the run_analysis.R code.

# Final Tidy Data Set

The final tidy data set required for the Course project can be found in dt_final.txt on this repo.  
For each activity and each subject in the final today data set, the mean of each variable was ultimately calculated. 
Note that final variable (column names) included in the final tidy set are simply expanded versions based on the raw data provided in features.txt
(See run_analysis_code STEP 4 for transformation to final variable names in dt_final.txt)
For complete details on units and other information pertaining to each variable, see raw data set file features_info.txt
