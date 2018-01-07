#Getting and Cleaning Data

This is a repository for any and all code written for the Getting and Cleaning Data Coursera course through Johns Hopkins University. ##Course Project
(find all project-related materials in the UCI HAR Dataset directory, however, copies of the important files have been put into this main directory to fulfill the submission requirement)

Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder o your local drive, for example "C:\Users\yourname\Documents\R\"

Place run_analysis.R into C:\Users\yourname\Documents\R\UCI HAR Dataset\

In RStudio: setwd("C:\\Users\\yourname\\Documents\\R\\UCI HAR Dataset\\"), to be followed by: source("run_analysis.R")

Use data <- read.table("data_set_with_the_averages.txt") to read the data.
Dimensions are 180 by 68 since there is 30 subjects and 6 activities, therefore "for each activity and each subject" it is validated as 30 * 6 = 180 rows. Note that the provided R script has no assumptions for the total number of records, just for the locations of files.
