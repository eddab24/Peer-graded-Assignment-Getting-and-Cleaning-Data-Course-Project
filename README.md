# Peer-graded-Assignment-Getting-and-Cleaning-Data-Course-Project
This repository is my submission for Getting and Cleaning Data course project. It contains instructions on how to run the analysis on Human Activity recognition dataset. 

# Dataset
Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

# Files

- CodeBook.md: This document outlines the variables, data, and any transformations or cleaning processes applied to the data.

- run_analysis.R: This script handles data preparation and implements the five steps required by the course project, as detailed below:

  1. Merges the training and test sets into a single dataset.
  2. Extracts only the mean and standard deviation measurements for each variable.
  3. Replaces activity codes with descriptive activity names.
  4. Assigns descriptive variable names to the dataset.
  5. Creates a second, independent tidy dataset, summarizing the average of each variable for every activity and subject.

- TidyData.txt: This file contains the cleaned and processed final dataset, resulting from the steps above.
