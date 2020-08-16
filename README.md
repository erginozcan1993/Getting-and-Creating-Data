# Getting-and-Creating-Data

This folder is created for Coursera Assignment. In this project, you see run_analysis.R for the answer of many question. 

Following steps are conducted in this project:
*Firstly, If dataset in the working directory is not available, dataset is downloaded from web. 
*Train and test datasets are read and merged into x, y and subjects. X means measurements and Y means activity.
*X data is loaded and columns are extracted call "mean" and "standard" from activity info. Also, column names are modified for description.
*Selected columns are extracted and merged. After that, Y column is replaced by "Activity Label".
*After all actions are completed. "Tidy Dataset" is generated and included each variables' average (mean) for each activity. This dataset is shown in the file "tidy_dataset.txt".
