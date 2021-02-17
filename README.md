# airline-analytics
Airline analytics in SQL

This is a quick analytics project to observe airline performance at CA airports.
I used Python to read the input CSV which was around 270MB and converted to Parquet format which reduced the file size to <20MB and stored the files in S3. This code is in my csv repo. In this repo sample files are there with data for one date.
I used BigQuery to do EDA and metrics in SQL. I did this using Pandas as part of a project and I am redoing it now in SQL. 

Sources of data: https://www.bts.gov/ , https://ourairports.com/ , https://geopandas.org/
