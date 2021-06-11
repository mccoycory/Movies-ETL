# Movies ETL

# Overview 

It was our duty to use the ETL method to clean 3 data sources for and upload the clean data file into a SQL database. The datafiles we used were 2 csv files and a JSON file from Wikipedia. During this module we used python and the define function variable. Using the def function code allowed us to write one block of code of ETL code and we could then pass the files through it. Lastly, we merged the two dataframes and exported the merged data set from python into a SQL database. Below are some screenshots of our outputs. 

## Wiki JSON Page 
The Json file had over 160 columns. There were many data errors with a bunch of null values, strings types that need to be ints, etc. The final clean out put of the data from is below. Along with a snap shot of the remaining columns. 

### Cleaned Wiki Dataframe
![Cleaned Wiki Dataframe](https://github.com/mccoycory/Movies-ETL/blob/main/Challenge/cleaned_wiki_df.png)

### Cleaned Wiki Dataframe Columns 

![wiki columns](https://github.com/mccoycory/Movies-ETL/blob/main/Challenge/cleaned_wiki_columns.png)

## CSV Cleaning

The next step was to manage and clean out csv files. This was a little easier as the data was formatted in a better way. We merged some kaggle data with some movie rating data. Below is a screen shot of the merged data frame.

### Merged Data Frame of CSV 

![Merged data frame](https://github.com/mccoycory/Movies-ETL/blob/main/Challenge/movies_merge_ratings_df.png)

## Python to Sql 

Lastly, we used python to create a sql database. The output of the sql database is below 

### Final Movie Dataframe in sql 

![python to sql](https://github.com/mccoycory/Movies-ETL/blob/main/Challenge/Sql%20database%20creation.png)

