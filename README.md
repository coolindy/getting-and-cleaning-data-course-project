# Getting and Cleaning Data Course Project

This R script is written as part of week 4 peer graded assigment of getting and cleaning data coursera course
Data for the assigment was downloaded from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
This script
 1. Merges the training and the test sets to create one data set.
 2. Extracts only the measurements on the mean and standard deviation for each measurement.
 3. Uses descriptive activity names to name the activities in the data set
 4. Appropriately labels the data set with descriptive activity names.
 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Follow the below steps before running the script run_analysis.R
 1. Download the data from the below data source
    https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
 2. Extract the zip file and copy UCI HAR Dataset folder in your R working directory
 3. Copy and put run_analysis.R file in UCI HAR Dataset directory
 4. Run source("run_analysis.R"). This will generate a new file tiny_data.txt in UCI HAR Dataset directory
 
 ## Dependencies
 run_analysis.R file will help you to install the dependencies automatically. It depends on reshape2 and data.table
