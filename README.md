# Movie Data ETL (Extract, Transform, Load)

## Purpose
- Performing ETL on Wikipedia movie data, Kaggle metadata and MovieLens rating data and adding it to a PostgresSQL database.

## Steps 
- Files include similarities in code but are meant to show the work through stages:
    1. Writing a function to read in three data files and testing it
    (See [ETL_function_test.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_function_test.ipynb))
    
    2. Cleaning Wikipedia data read into a Pandas DataFrame 
    (See [ETL_clean_wiki_movies.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_clean_wiki_movies.ipynb))
    
    3. Cleaning Kaggle data in addition to wikipedia data and merge with ratings data 
    (See [ETL_clean_kaggle_data.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_clean_kaggle_data.ipynb)
    
    4. Finish the ETL process by loading all data into a postgreSQL database 
    (See [ETL_create_database.ipynb](https://github.com/a-memme/Movie_Data_ETL/blob/main/ETL_create_database.ipynb)
