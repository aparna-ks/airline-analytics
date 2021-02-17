# airline-analytics
Airline analytics in SQL

This is a quick analytics project to observe airline performance at CA airports.
I used Python to read the input CSV which was around 270MB and converted to Parquet format which reduced the file size to <20MB and stored the files in S3. This code is in my [csv repo](https://github.com/aparna-ks/csv/blob/master/csv_to_pq.py). In this repo sample files are there with data for one date.
I used BigQuery to do EDA and metrics in SQL. I did this using Pandas as part of a project and I am redoing it in SQL now. 

Sources of data: https://www.bts.gov/ , https://ourairports.com/ , https://geopandas.org/


Data Dictionary - Schema

year

day_of_week

fl_date

op_unique_carrier

tail_num

op_carrier_fl_num

origin_airport_id

origin

origin_city_name

origin_state_abr

origin_state_nm

dest_airport_id

dest

dest_city_name

dest_state_abr

dest_state_nm

crs_dep_time

dep_time

dep_delay

dep_delay_new

taxi_out

wheels_off

wheels_on

taxi_in

crs_arr_time

arr_time

arr_delay

arr_delay_new

cancelled

cancellation_code

diverted

air_time

distance

carrier_delay

weather_delay

nas_delay

security_delay

late_aircraft_delay
