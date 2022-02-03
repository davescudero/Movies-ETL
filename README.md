#  Extract, Transform, and Load (ETL)

## Overview

Perform ETL on several movie datasets to predict popular films for a streaming service

## ETL

### **Extract**
 The extract phase involved the data retrieval from sources like Wikipedia, Kaggle and IMDB.

 ### **Transform**
The transform phase involved python´s labrary pandas, to merge data and transform it into dataframes so we can export it to SQL

### **Load**
The loading phase consisted in using psycopg to create the connection with pandas and our SQL database

## Results
After finishing our ETL process we have to tables in our database. One for movies and other one for ratings

![movies_query](https://github.com/davescudero/Movies-ETL/blob/main/Resources/movies_query.png)

![ratings_query](https://github.com/davescudero/Movies-ETL/blob/main/Resources/ratings_query.png)

**With this new database students can create their own analysis**
