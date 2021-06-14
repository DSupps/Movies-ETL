# Movies-ETL

## Movies-ETL Challenge Overview - 
*Create an automated pipeline that takes in new data from Wikipedia, Kaggle metadata, and MovieLens ratings.  The data is transformed into appropriate format and then loaded into a PostgreSQL database for further analysis.*

1. Deliverable 1: Write an ETL function to read three data files
2. Deliverable 2: Extract and Transform the Wikipedia Data
3. Deliverable 3: Extract and Transform the Kaggle Data
4. Deliverable 4: Create the Movie Database

## Resources
- Data Sources:
    - movies_metadata.csv
    - ratings.csv
    - wikipedia-movies.json

- Software:
    - Anaconda Version 3.7.3
    - MacOS Catalina Version 10.15.7
    - PgAdmin4
    - Jupyter Notebook

## Movies-ETL Challenge Results

### Results: Write an ETL function to read three data files
A function was created to take in Kaggle metadata, Wikipedia JSON, and MovieLens rating.csv. Each one was then set into their own seperate dataframe.

### Results: Extract and Transform the Wikipedia JSON data
A merge was created with Wikipedia JSOO data and Kaggle metadata.  The merged dataframe was filterd out for tv shows while multiple columns were cleaned up do to lack of or inapporpirate data. 

### Extract and Transform the Kaggle Data
Transformed Kaggle metadata and MovieLens rating data, and then converted into seperate dataframes.  Kaggle, Wikipedia, and MoviesLens rating dataframes were then merged to create one dataframe with ratings for analysis.

### Create the Movie Database
Added merged dataframes containg Kaggle and Wikipedia data with MoviesLens rating data to a SQL database where custom queries can be performed for analysis. 

## Movie-ETL Summary
Amazon Prime Video Development Team can now perform the "Predict the Popular Pictures" Hackathon as requested.  With the new "Movie Data" database, the team is now able to uncover low budget releases that they can use to predict are at a bargain price. 
