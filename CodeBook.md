

##"Getting and Cleaning Data - Code Book for Course Project"

### Author: "Amit Kumar Das"
### Date: "June 21, 2015"


### Important points to start with:

#### About the data set used for the analysis:

The data was collated as a part of experiments "Human Activity Recognition Using Smartphones Dataset" conducted by Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto. The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist.The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

#### Subjects : Refer to the group of 30 volunteers

#### Activities: Refer to the six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) that the volunteers performed.

#### Columns in the final tidy data set:

### Group by columns:

Activity_Name
Subjects

### Measurements of Mean selected in the final tidy data set:

Sr# --> Indicates the serial number
Original_Seq --> This is the position of the column in the original test and training data set
Column Name --> The original feature list name has been retained to make the mapping easy to understand

Sr#  Original_Seq   Column Name
===  ============   ===========
1    1               tBodyAcc-mean()-X
2    2               tBodyAcc-mean()-Y
3    3               tBodyAcc-mean()-Z
4   41            tGravityAcc-mean()-X
5   42            tGravityAcc-mean()-Y
6   43            tGravityAcc-mean()-Z
7   81           tBodyAccJerk-mean()-X
8   82           tBodyAccJerk-mean()-Y
9   83           tBodyAccJerk-mean()-Z
10 121              tBodyGyro-mean()-X
11 122              tBodyGyro-mean()-Y
12 123              tBodyGyro-mean()-Z
13 161          tBodyGyroJerk-mean()-X
14 162          tBodyGyroJerk-mean()-Y
15 163          tBodyGyroJerk-mean()-Z
16 201              tBodyAccMag-mean()
17 214           tGravityAccMag-mean()
18 227          tBodyAccJerkMag-mean()
19 240             tBodyGyroMag-mean()
20 253         tBodyGyroJerkMag-mean()
21 266               fBodyAcc-mean()-X
22 267               fBodyAcc-mean()-Y
23 268               fBodyAcc-mean()-Z
24 294           fBodyAcc-meanFreq()-X
25 295           fBodyAcc-meanFreq()-Y
26 296           fBodyAcc-meanFreq()-Z
27 345           fBodyAccJerk-mean()-X
28 346           fBodyAccJerk-mean()-Y
29 347           fBodyAccJerk-mean()-Z
30 373       fBodyAccJerk-meanFreq()-X
31 374       fBodyAccJerk-meanFreq()-Y
32 375       fBodyAccJerk-meanFreq()-Z
33 424              fBodyGyro-mean()-X
34 425              fBodyGyro-mean()-Y
35 426              fBodyGyro-mean()-Z
36 452          fBodyGyro-meanFreq()-X
37 453          fBodyGyro-meanFreq()-Y
38 454          fBodyGyro-meanFreq()-Z
39 503              fBodyAccMag-mean()
40 513          fBodyAccMag-meanFreq()
41 516      fBodyBodyAccJerkMag-mean()
42 526  fBodyBodyAccJerkMag-meanFreq()
43 529         fBodyBodyGyroMag-mean()
44 539     fBodyBodyGyroMag-meanFreq()
45 542     fBodyBodyGyroJerkMag-mean()
46 552 fBodyBodyGyroJerkMag-meanFreq()

### Measurements of Standard Deviation selected in the final tidy data set:

Sr# --> Indicates the serial number
Original_Seq --> This is the position of the column in the original test and training data set
Column Name --> The original feature list name has been retained to make the mapping easy to understand

Sr#  Original_Seq   Column Name
===  ============   ===========
1    4           tBodyAcc-std()-X
2    5           tBodyAcc-std()-Y
3    6           tBodyAcc-std()-Z
4   44        tGravityAcc-std()-X
5   45        tGravityAcc-std()-Y
6   46        tGravityAcc-std()-Z
7   84       tBodyAccJerk-std()-X
8   85       tBodyAccJerk-std()-Y
9   86       tBodyAccJerk-std()-Z
10 124          tBodyGyro-std()-X
11 125          tBodyGyro-std()-Y
12 126          tBodyGyro-std()-Z
13 164      tBodyGyroJerk-std()-X
14 165      tBodyGyroJerk-std()-Y
15 166      tBodyGyroJerk-std()-Z
16 202          tBodyAccMag-std()
17 215       tGravityAccMag-std()
18 228      tBodyAccJerkMag-std()
19 241         tBodyGyroMag-std()
20 254     tBodyGyroJerkMag-std()
21 269           fBodyAcc-std()-X
22 270           fBodyAcc-std()-Y
23 271           fBodyAcc-std()-Z
24 348       fBodyAccJerk-std()-X
25 349       fBodyAccJerk-std()-Y
26 350       fBodyAccJerk-std()-Z
27 427          fBodyGyro-std()-X
28 428          fBodyGyro-std()-Y
29 429          fBodyGyro-std()-Z
30 504          fBodyAccMag-std()
31 517  fBodyBodyAccJerkMag-std()
32 530     fBodyBodyGyroMag-std()
33 543 fBodyBodyGyroJerkMag-std()