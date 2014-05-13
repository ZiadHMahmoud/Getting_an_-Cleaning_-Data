## UCI HAR Dataset Readme

To run the file please add the file to the "UCI HAR Dataset" folder

In the run_analysis.R script you can find the steps taken to produce the wanted datasets
you can find below a short description of the steps taken
* steps from 1-9 read the data
* steps 11-13 combine the test and train data
* steps 15-17 sets the column names
* step 20 finds the columns that have the words "mean" or "std" in them 
* step 21 extracts the columns found in step 16 and creates the first dataset 
* steps 24-25 read the names of the activities and merges it with "act" dataframe in order to use a factor with descriptive names instead of numbers
* step 27 combines the the subjects, activities, and data together
* steps 30-31 calculate the mean for every measurement across subject and activites
* step 33 exports the data to a text file
