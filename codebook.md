---
title: "CodeBook"
output: html_document
---

# Getting and Cleaning Data Project: run_analysis.R

##Data 

Data lies at

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.

##Variables

Variables slightly altered from original study to remove parentheses and dashes

One variabl added, activityLabels, to match activity code number to the character string which explains the activity.

Test subject number 1-30 in the original experiment.

activityLabels - 1 of 6 activities done by the subject for that measurement: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, or LAYING.

Activity - a number 1-6 from the original experiment which represents the activity done by the subject for that measurement.

Copied from the original study's "features_info.txt", below the new variables

tBodyAccmeanX
tBodyAccstdX
tBodyAccmeanY
tBodyAccstdY
tBodyAccmeanZ
tBodyAccstdZ
tGravityAccmeanX
tGravityAccstdX
tGravityAccmeanY
tGravityAccstdY
tGravityAccmeanZ
tGravityAccstdZ
tBodyAccJerkmeanX
tBodyAccJerkstdX
tBodyAccJerkmeanY
tBodyAccJerkstdY
tBodyAccJerkmeanZ
tBodyAccJerkstdZ
tBodyGyromeanX
tBodyGyrostdX
tBodyGyromeanY
tBodyGyrostdY
tBodyGyromeanZ
tBodyGyrostdZ
tBodyGyroJerkmeanX
tBodyGyroJerkstdX
tBodyGyroJerkmeanY
tBodyGyroJerkstdY
tBodyGyroJerkmeanZ
tBodyGyroJerkstdZ
tBodyAccMagmean
tBodyAccMagstd
tGravityAccMagmean
tGravityAccMagstd
tBodyAccJerkMagmean
tBodyAccJerkMagstd
tBodyGyroMagmean
tBodyGyroMagstd
tBodyGyroJerkMagmean
tBodyGyroJerkMagstd
fBodyAccmeanX
fBodyAccstdX
fBodyAccmeanY
fBodyAccstdY
fBodyAccmeanZ
fBodyAccstdZ
fBodyAccmeanFreqX
fBodyAccJerkstdX
fBodyAccmeanFreqY
fBodyAccJerkstdY
fBodyAccmeanFreqZ
fBodyAccJerkstdZ
fBodyAccJerkmeanX
fBodyGyrostdX
fBodyAccJerkmeanY
fBodyGyrostdY
fBodyAccJerkmeanZ
fBodyGyrostdZ
fBodyAccJerkmeanFreqX
fBodyAccMagstd
fBodyAccJerkmeanFreqY
fBodyBodyAccJerkMagstd
fBodyAccJerkmeanFreqZ
fBodyBodyGyroMagstd
fBodyGyromeanX
fBodyBodyGyroJerkMagstd
fBodyGyromeanY
fBodyGyromeanZ
fBodyGyromeanFreqX
fBodyGyromeanFreqY
fBodyGyromeanFreqZ
fBodyAccMagmean
fBodyAccMagmeanFreq
fBodyBodyAccJerkMagmean
fBodyBodyAccJerkMagmeanFreq
fBodyBodyGyroMagmean
fBodyBodyGyroMagmeanFreq
fBodyBodyGyroJerkMagmean
fBodyBodyGyroJerkMagmeanFreq