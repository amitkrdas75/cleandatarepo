

##"Getting and Cleaning Data - Readme file for Course Project"

### Author: "Amit Kumar Das"
### Date: "June 21, 2015"



### Important points to start with:

* The compressed file 'getdata-projectfiles-UCI HAR Dataset.zip' containing data set and other related data files have been downloaded from the link mentioned
* After that, 'getdata-projectfiles-UCI HAR Dataset.zip' has been uncompressed.
* The root folder after uncompression, 'UCI HAR Dataset' has been set as the working folder. All subsequent references to the file paths have been made with respect to this working folder.


### Code Sections

#### Step: Merges the training and the test sets to create one data set:

* Loading the test dataset - 
(i) First load the subject column of test data set from the file "subject_test.txt"
(ii) Next load the activity column of test data setfrom the file "y_test.txt"
(iii) Then load the actual data columns of test data set from the file "X_test.txt"
(iv) At the end, bind the datasets column-wise to get the full test dataset


* Loading the training dataset - 
(i) First load the subject column of training data set from the file "subject_train.txt"
(ii) Next load the activity column of training data setfrom the file "y_train.txt"
(iii) Then load the actual data columns of training data set from the file "X_train.txt"
(iv) At the end, bind the datasets column-wise to get the full training dataset


* Bind the test and training datasets to get the full data set
* Get the features list loaded in a data frame

#### Step: Uses descriptive activity names to name the activities in the data set

* Now append "Subjects" and "Activity" to the list of features - reason is the rows of feature dataset can be the column names for the full dataset
* Now let's get feature names added as the column header of the full dataset

#### Step: Extracts only the measurements on the mean and standard deviation for each measurement:

* Use the "grep" function of R to sub-set only the columns of the full dataset having "mean" or "std" as a part of column name

#### Step: Create independent tidy data set with the average of each variable for each activity and each subject

* Group the sub-setted dataset (only the measurements on the mean and standard deviation for each measurement) by activity and subject
* Summarize the dataset by activity and subject to calculate the average
* Write the data to a file "tidy_data.txt"

##### Point to be noted: There may be a confusion regarding which specific columns of mean should be taken and which to be left out. I've personally kept all the columns having any kind of mean)





