# Getting and Cleaning Data / Course Project

# Data description

 A full description of the data obtained can be found in http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
 and the exact data for this project can be found in https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# run_analysis.R

Created a file in R named run_analysis.R that did all the 5 steps asked:

1) Merging the training and the test sets to create one data set.
2) Reading files/
3) Merging all data in one set
4) Extracting only the measurements on the mean and standard deviation for each measurement
5) Using descriptive activity names to name the activities in the data set
6) Appropriately labeling the data set with descriptive variable names
7) Creating a second, independent tidy data set with the average of each variable for each activity and each subject

# variables used

x_train,y_train,x_test,y_test,subject_test,subject_train that contain data from the tables downloaded
mrg_test,mrg_train,setAllInOne merged data


