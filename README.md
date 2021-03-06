# Project_GCD

##Getting and Cleaning Data##

**Introduction**

The present repository contains the course project of the Getting and Cleaning Data (GCD) course offered by The Johns Hopkins University at the Coursera MOOC, February 2015.

The repository encompasses three major documents:

1. The README.md presenting the objective and contents of the repository;
2. The R script "run_analysis.R";
3. The Code Book with the description of the variables present in the script output.

**Objective**

The script *run_analysis.R* takes the dataset obtained in the study *Human Activity Recognition Using Smartphones Data Set* carried out by Reyes-Ortiz, Anguita, Ghio, Oneto and Parra (2013) and outputs a file named *run_analysis.txt*.

The dataset has 561 different three-dimensional sensor readings ("features") of accelaration (accelerometer) and angular velocity (gyroscope) along the time domain (variables starting with "t") and frequency domain (variables starting with "f") obtained from a smartphone installed in the waist of 30 volunteers. All subjects performed six activities: walking, walking upstairs, walking downstairs, sitting, standing, and laying. The subjects were splitted randomly into two groups: *test* (30% of the subjects) and *training* (70%).

The script merges the two sets and selects 66 features related to mean and standard deviation of some of the sensor readings. The final dataframe encompasses a tidy dataset of 180 rows (30 subjects X 6 activities) and 68 columns. The first two columns identify the subject and the activity. The remaining 66 columns are the calculated mean of each feature for each activity and for each subject.

**Literature**

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. *A Public Domain Dataset for Human Activity Recognition Using Smartphones*. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013.
