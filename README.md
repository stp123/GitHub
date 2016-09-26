Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it is not alrady in the working directory
2. Load the information about activity and features
3. Loads  the training and test datasets, keeps only the columns that
   reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
5. Merges the datasets
6. Convert the [activity] and [subject] columns into factors
7. Create a tidy dataset that shows average (mean) value of each variable for each pair.

The end result is shown in the file `tidy.txt`.
