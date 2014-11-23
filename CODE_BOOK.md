#CODE BOOK
#####This file contains the explanation of every variables of the file "  ", that is given by run_analysis function.
#####In general all the data is a mean of certanly fields of the original project "Human Activity Recognition Using Smartphones Dataset"
#####Was selected only the fields o features that the names was contained "mean" or "std". Was excludes "Mean" because that was not properly a mean, that was the filter asked.
#####DESCRIPTION GENERAL OF NAMES
#####When the name beggining with "t" thats means time, when begining with "f" thats means frequency domain signals, that was applied to some of these signals.<br>
#####there was distitincted the type of device with "Acc":Accelerometer and  "Gyro": Gyroscope
#####The acceleration signal was separated into "Body" and "Gravity" acceleration.
#####"Jerks" means the Jerk signal obteined  and "Mag" will be the magnitud calculated using the Euclidean norm.
#####And finaly X, Y y Z will be the cordenates in the moment the experiment was done.

#####NUMBERS, NAMES AND DESCRIPTION OF COLUMNS<br>  
<ol>
<li>Activity.<br>
Will be contained the type of activity that subject is doing when the test was done.<br>
Posible values: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING</li> 
<li>Subject.<br>
Number of Subject that paticiped of project<br>
Posible values: 1 to 30</li> 
<li>tBodyAcc_mean_X.<br>
Mean of Body Acceleration time for X axis.</li> 
<li>tBodyAcc_mean_Y.<br>
Mean of Body Acceleration time for Y axis.</li> 
<li>tBodyAcc_mean_Z.<br>
Mean of Body Acceleration time for Z axis.</li>
<li>tGravityAcc_mean_X.<br>
Mean of Gravity Acceleration time for X axis.</li>
<li>tGravityAcc_mean_Y.<br>
Mean of Gravity Acceleration time for Y axis.</li> 
<li>tGravityAcc_mean_Z.<br>
Mean of Gravity Acceleration time for Z axis.</li> 
<li>tBodyAccJerk_mean_X.<br>
Mean of Jerk Signal time for Body Acceleration for X axis.</li> 
<li>tBodyAccJerk_mean_Y.<br>
Mean of Jerk Signal time for Body Acceleration for Y axis.</li> 
<li>tBodyAccJerk_mean_Z.<br>
Mean of Jerk Signal time for Body Acceleration for Z axis.</li> 
<li>tBodyGyro_mean_X.<br>
Average of Body position time for X axis.</li> 
<li>tBodyGyro_mean_Y.<br>
Average of Body position time for Y axis.</li> 
<li>tBodyGyro_mean_Z.<br>
Average of Body position time for Z axis.</li> 
<li>tBodyGyroJerk_mean_X.<br>
Average of Jerk Signal time for Body position for X axis.</li> 
<li>tBodyGyroJerk_mean_Y.<br>
Average of Jerk Signal time for Body position for Y axis.</li> 
<li>tBodyGyroJerk_mean_Z.<br>
Average of Jerk Signal time for Body position for Z axis.</li> 
<li>tBodyAccMag_mean.<br>
Average of magnitude time for Body acceleration.</li> 
<li>tGravityAccMag_mean.<br>
Average of magnitude time for Gravity acceleration.</li> 
<li>tBodyAccJerkMag_mean.<br>
Average of Jerk signal magnitude time for Body acceleration.</li> 
<li>tBodyGyroMag_mean.<br>
Average of magnitude time for Body position.</li> 
<li>tBodyGyroJerkMag_mean.<br>
Average of Jerk signal magnitude time for Body position.</li> 
<li>fBodyAcc_mean_X<br>
Average of frequency domain signal for Body acceleration X axis</li> 
<li>fBodyAcc_mean_Y<br>
Average of frequency domain signal for Body acceleration Y axis</li> 
<li>fBodyAcc_mean_Z<br>
Average of frequency domain signal for Body acceleration Z axis</li> 
<li>fBodyAcc_meanFreq_X<br>
Weighted average of the frequency components to obtain a mean frequency for Body acceleration X axis</li> 
<li>fBodyAcc_meanFreq_Y<br>
Weighted average of the frequency components to obtain a mean frequency for Body acceleration Y axis</li> 
<li>fBodyAcc_meanFreq_Z<br>
Weighted average of the frequency components to obtain a mean frequency for Body acceleration Z axis</li> 
<li>fBodyAccJerk_mean_X</li> 
<li>fBodyAccJerk_mean_Y</li> 
<li>fBodyAccJerk_mean_Z</li> 
<li>fBodyAccJerk_meanFreq_X</li> 
<li>fBodyAccJerk_meanFreq_Y</li> 
<li>fBodyAccJerk_meanFreq_Z</li> 
<li>fBodyGyro_mean_X</li> 
<li>fBodyGyro_mean_Y</li> 
<li>fBodyGyro_mean_Z</li> 
<li>fBodyGyro_meanFreq_X</li> 
<li>fBodyGyro_meanFreq_Y</li> 
<li>fBodyGyro_meanFreq_Z</li> 
<li>fBodyAccMag_mean</li> 
<li>fBodyAccMag_meanFreq</li> 
<li>fBodyBodyAccJerkMag_mean</li> 
<li>fBodyBodyAccJerkMag_meanFreq</li> 
<li>fBodyBodyGyroMag_mean</li> 
<li>fBodyBodyGyroMag_meanFreq</li> 
<li>fBodyBodyGyroJerkMag_mean</li> 
<li>fBodyBodyGyroJerkMag_meanFreq</li> 
<li>tBodyAcc_std_X</li> 
<li>tBodyAcc_std_Y</li> 
<li>tBodyAcc_std_Z</li> 
<li>tGravityAcc_std_X</li> 
<li>tGravityAcc_std_Y</li> 
<li>tGravityAcc_std_Z</li> 
<li>tBodyAccJerk_std_X</li> 
<li>tBodyAccJerk_std_Y</li> 
<li>tBodyAccJerk_std_Z</li> 
<li>tBodyGyro_std_X</li> 
<li>tBodyGyro_std_Y</li> 
<li>tBodyGyro_std_Z</li> 
<li>tBodyGyroJerk_std_X</li> 
<li>tBodyGyroJerk_std_Y</li> 
<li>tBodyGyroJerk_std_Z</li> 
<li>tBodyAccMag_std</li> 
<li>tGravityAccMag_std</li> 
<li>tBodyAccJerkMag_std</li> 
<li>tBodyGyroMag_std</li> 
<li>tBodyGyroJerkMag_std</li> 
<li>fBodyAcc_std_X</li> 
<li>fBodyAcc_std_Y</li> 
<li>fBodyAcc_std_Z</li> 
<li>fBodyAccJerk_std_X</li> 
<li>fBodyAccJerk_std_Y</li> 
<li>fBodyAccJerk_std_Z</li> 
<li>fBodyGyro_std_X</li> 
<li>fBodyGyro_std_Y</li> 
<li>fBodyGyro_std_Z</li> 
<li>fBodyAccMag_std</li> 
<li>fBodyBodyAccJerkMag_std</li> 
<li>fBodyBodyGyroMag_std</li> 
<li>fBodyBodyGyroJerkMag_std</li> 
</ol>
