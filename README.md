# Getting and Cleaning Data Course Project
**PROJECT DESCRIPTION**

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. You will be graded by your peers on a series of yes/no questions related to the project.

You will be required to submit:
- a tidy data set as described below
- a link to a Github repository with your script for performing the analysis
- a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.  
Here are the data for the project: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
You should create one R script called run_analysis.R that does the following. 
- Merges the training and the test sets to create one data set.
- Extracts only the measurements on the mean and standard deviation for each measurement. 
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names. 
- From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

**FILES**

- CodeBook.md: information about raw and tidy data set and elaboration made to transform them
- LICENSE: license terms for text and code
- README.md: this file
- run_analysis.R: R script to transform raw data set in a tidy one

**CREATE TIDY DATA SET**

- Download the data source and put into a folder on your local drive. 
- Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.
- Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.
