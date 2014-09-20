CodeBook

Data:

The data were collected from the accelerometers from the Samsung Galaxy S smartphone. 

Feature Selection:

The features selected come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. 
The time domain signals were captured at a constant rate of 50 Hz. 
Noises were removed using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz. 
The acceleration signals were tcategorized into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.
The body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). 
The magnitude of these three-dimensional signals were also calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).
A Fast Fourier Transform (FFT) was applied to some of the signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag.

'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

Variables estimated:

mean(): Mean value
std(): Standard deviation
