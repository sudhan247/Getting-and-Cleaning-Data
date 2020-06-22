# Peer-graded Assignment: Getting and Cleaning Data Course Project
```
  This repository is a submission for Getting and Cleaning Data course project. It has the instructions on how to run analysis on Human Activity recognition dataset.
```
## Dataset
```
  http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
```
## Files

```

  1.CodeBook.md a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

  2.run_analysis.R performs the data preparation and then followed by the 5 steps required as described in the course project’s definition:
      
	2.21 Merges the training and the test sets to create one data set.
       
	2.22 Extracts only the measurements on the mean and standard deviation for each measurement.
			 
	2.23 Uses descriptive activity names to name the activities in the data set
			 
	2.24 Appropriately labels the data set with descriptive variable names.
			 
	2.25 From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
   ```
    3.FinalData.txt is the exported final data after going through all the sequences described above.
  
 
## About variables

```
  * x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.
	
  * x_data, y_data and subject_data merge the previous datasets to further analysis.
	
  * features contains the correct names for the x_data dataset, which are applied to the column names stored in
```
