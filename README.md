# run_analysis.R (Coursera Project)
UCI HAR Analysis (run_analysis.R) is a R script that uses "Human Activity Recognition Using Smartphones" dataset and creates a tidy data that can be used for later analysis.

run_analysis.R :

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
When you run_analysis.R

If dataset directory is not in the same path with the R script , it will download and extract dataset.
It will install required packages if they are not already and it will load them.
Unlink if previous tidy.txt
Verify all required files are in placee
Will processes files and create a single tidy table
Will save this table to disk as tidy.txt