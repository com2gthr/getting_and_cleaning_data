Getting and Cleaning Data Course Project
This repository contains required documents and scripts for Coursera Getting and Cleaning Data course project.

README.md : explains how all of the scripts work and how they are connected
tidy_data.txt : tidy data set
CodeBook.md : describes the variables, and data transformations
run_analysis.R: R script used to generate final results 'tidy_data.txt'
Introduction of Data
Business Background: One of the most exciting areas in all of data science right now is wearable computing.

Name: Human Activity Recognition Using Smartphones Dataset

Introduction: The data was collected from experiments with a group of 30 volunteers who performed six activities wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, they captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.

Links

original data
description
Analytical Approach
The tidy_data.txt was created using R script run_analysis.R. The code runs on R 3.6.0 version with library dplyr and reshape2.

As shown in its comments, run_analysis.R was splitted into five different parts. Each part aims at reaching one of below objectives.

Download .zip file and unzip it in designated working directory
Load training, test, labels, feature names data sets
Merges the training and the test sets to create one data set
Extracts only the measurements on the mean and standard deviation for each measurement
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names
Creates a second, independent tidy data set with the average of each variable for each activity and each subject
Export final results into tidy_data.txt
