# Movie Data ETL 

## Purpose
Retrieving and cleaning movie ratings data from multiple sources and loading it into a PostgreSQL database

## Process 
### Extract
Three predominate sources of data were used for this project:
- Wikipedia movie data in JSON format
- Movie metadata derived from kaggle 
- MovieLens rating data derived from kaggle

### Transform
Data from all sources required a sufficient amount of cleaning involving filtering, converting datatypes, renaming/dropping columns, cleaning up string text using regular expression, etc. After cleaning, dataframes were merged to prepare for load 

### Load 
Finally, data was loaded into a postgreSQL database using a single function and timed.

## Steps 
- Files include similarities in code but are meant to show the work through additive stages:
    1. Writing a function to read in three data files and testing
    (See [ETL_function_test.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_function_test.ipynb))
    
    2. Wikipedia data read into a Pandas DataFrame and cleaned
    (See [ETL_clean_wiki_movies.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_clean_wiki_movies.ipynb))
    
    3. Cleaning Kaggle data in addition to wikipedia data and merge with ratings data 
    (See [ETL_clean_kaggle_data.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_clean_kaggle_data.ipynb))
    
    4. Finish the ETL process by loading all data into a postgreSQL database 
    (See [ETL_create_database.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_create_database.ipynb))
