## run_analysis.R (Coursera Project)
UCI HAR Analysis (run_analysis.R) is a R script that uses "Human Activity Recognition Using Smartphones" dataset and creates a tidy data that can be used for later analysis.

run_analysis.R :
##### Assumption 
The dataset is downloaded and unzipped as the same folder as the script. Read CodeBook.md for more details
The scrip will run the following process to generate tidy_data_all.txt
1. Read, then Merges the training and the test sets to create one data set.
4. Appropriately labels the data set with descriptive variable names. 
2. Extract only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
