## Coursera-Getting-And-Cleaning-Data

## Goal
## The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set.
## To this end an R script needs to be writen that will:

* 1. Merges the training and the test sets to create one data set.
* 2. Extracts only the measurements on the mean and standard deviation for each measurement.
* 3. Uses descriptive activity names to name the activities in the data set
* 4. Appropriately labels the data set with descriptive variable names.
* 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


###  Note that the data file for the project was downloaded from this URL:
###  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
###  A description for this data is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

### The files used in this project are:

 * README.md (this current file)
 * CodeBook.md -- codebook describing variables, the data and transformations
 * run_analysis.R -- the R code
 
### The run_analysis.R script works as follows:
 
 * 1.  Load the required libraries
 * 2.  Extract the activity labels and the data column names
 * 3.  Read the testing data X_test & y_test data & subject_test.
 * 4.  Extract only the measurements on the mean and standard deviation for each measurement of the testing data.
 * 5.  Load the activity labels
 * 6.  Merge the testing data
 * 7.  Extract only the measurements on the mean and standard deviation for each measurement of the training data.
 * 8.  Load the activity data
 * 9.  Merge the training data
 * 10. Merge the testing and the training data
 * 11. View the merged data
 * 12. create the tidy data set
 * 13. Write the new tidy set into a text file called tidy_data.txt
 
### 14. Finally the above mentioned data is located in these diractories
 *     "./data" 
 *     "./UCI HAR Dataset/test"
 *     "./UCI HAR Dataset/train"
 *     "./UCI HAR Dataset/UCI HAR Dataset/test"
 *     "./UCI HAR Dataset/UCI HAR Dataset/train"
 