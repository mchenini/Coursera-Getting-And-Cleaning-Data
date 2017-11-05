## Code Book

### This code book describes the data, the variables and transformations that were performed to clean up the data.

#### Overview from: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
 
#### "The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data."

### Transformation
#### The transformations performed on the input data are lisyed in the Readme.md file

### Files info
#### By running the nrow() and the ncol() functions, we obtain the following infornation on the variables used:

#### features.txt: Names of the 561 features.
#### activity_labels.txt: Names and IDs for each of the 6 activities.

#### X_train.txt: 7352 observations of the 561 features, for 21 of the 30 volunteers.

#### subject_train.txt: A vector of 7352 integers, denoting the ID of the volunteer related to each of the observations in X_train.txt.

#### y_train.txt: A vector of 7352 integers, denoting the ID of the activity related to each of the observations in X_train.txt.

#### X_test.txt: 2947 observations of the 561 features, for 9 of the 30 volunteers.

#### subject_test.txt: A vector of 2947 integers, denoting the ID of the volunteer related to each of the observations in X_test.txt.

### y_test.txt: A vector of 2947 integers, denoting the ID of the activity related to each of the observations in X_test.txt.

### Variables info
#### Some variables info were obtained by running head("filename",1)

#### A few examples are:

####  head(featureNames)
#### V1                V2
#### 1  1 tBodyAcc-mean()-X
#### 2  2 tBodyAcc-mean()-Y
#### 3  3 tBodyAcc-mean()-Z
#### 4  4  tBodyAcc-std()-X
#### 5  5  tBodyAcc-std()-Y
#### 6  6  tBodyAcc-std()-Z

#### > head(activityLabels)
####   V1                 V2
###  3 1  1            WALKING
#### 2  2   WALKING_UPSTAIRS
#### 3  3 WALKING_DOWNSTAIRS
#### 4  4            SITTING
#### 5  5           STANDING
#### 6  6             LAYING
 
####  head(subjectTest)
####   V1
#### 1  2
#### 2  2
#### 3  2
#### 4  2
#### 5  2
#### 6  2
####  head(yTest); 
####   V1
#### 1  5
#### 2  5
#### 3  5
#### 4  5
#### 5  5
#### 6  5

