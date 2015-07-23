# Getting and Cleaning Data
# Course Project

You should create one R script called run_analysis.R that does the following.

- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement.
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive activity names.
- Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# How use this course project

- Download the data source and put into a folder on your local drive. You'll have a UCI HAR Dataset folder.
- Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory ( use setwd() function or Menu in RStudio).
- Run "run_analysis.R", and it will generate a file tiny_data.txt in your working directory.

# Additional conditions

This script depends on reshape2 and data.table.
