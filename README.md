# Getting-CleaningData Course Project

The R script, run_analysis.R, does the following and stores output in tidy.txt:

Download the dataset if it does not exist in current working directory.
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges the two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
