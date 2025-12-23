# Code book
This is the code book for tidy data set.

## Variables Description
Data read from project data files. For description of each data files, refer to README in the project folder.

features <- features.txt: The features selected for this database.

activities <- activity_labels.txt: List of activities performed 

subject_test <- test/subject_test.txt: Contains test data of volunteer test subjects 

x_test <- test/X_test.txt: Contains recorded features test data

y_test <- test/y_test.txt: Contains test data of activities’code labels

subject_train <- test/subject_train.txt: Contains train data of volunteer subjects 

x_train <- test/X_train.txt: Contains recorded features train data

y_train <- test/y_train.txt: Contains train data of activities’code labels

X <- Created by merging x_train and x_test 

Y <- Created by merging y_train and y_test 

Subject <- Created by merging subject_train and subject_test

Merged_Data <- Created by merging Subject, Y and X. Contains the mean and standard deviation for each measurement

TidyData <- Created by subsetting Merged_Data
