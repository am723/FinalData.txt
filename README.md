# FinalData.txt
Getting and cleaning data project

# Getting and Cleaning Data Project

This repository contains the R script and instructions for performing the data analysis for the Human Activity Recognition Using Smartphones dataset.

## Files

- `run_analysis.R`: R script that performs the data cleaning and analysis.
- `tidydata.txt`: Output file containing the tidy dataset.
- `CodeBook.md`: Description of the variables in the dataset and the transformations performed.

## Instructions

1. Place the Samsung dataset in your working directory.
2. Run the `run_analysis.R` script.
3. The output will be a file called `tidydata.txt` containing the cleaned dataset.



# Code Book

This code book describes the variables in the tidy dataset.

## Variables

- `subject`: ID of the subject who performed the activity.
- `activity`: The type of activity performed.
- `tBodyAcc-mean()-X`: Mean of the body acceleration signal in the X direction.
- `tBodyAcc-std()-X`: Standard deviation of the body acceleration signal in the X direction.
- (Include descriptions for other variables in your dataset)

## Transformations

1. Merged the training and test datasets.
2. Extracted mean and standard deviation measurements.
3. Applied descriptive activity names.
4. Appropriately labeled the dataset with descriptive variable names.
5. Created a second tidy dataset with the average of each variable for each activity and subject.
