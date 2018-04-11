The data file is larger than Github file limit. Therefore, please find the data used in this project from 
https://www.kaggle.com/c/nyc-taxi-trip-duration/data


The data has 11 columns and 1,458,644 rows. There are 10 features,  and the details of the features are:
1. vendor_id - a code indicating the provider associated with the trip record
2. pickup_datetime - date and time when the meter was engaged
3. dropoff_datetime - date and time when the meter was disengaged
4. passenger_count - the number of passengers in the vehicle (driver entered value)
5. pickup_longitude - the longitude where the meter was engaged
6. pickup_latitude - the latitude where the meter was engaged
7. dropoff_longitude - the longitude where the meter was disengaged
8. dropoff_latitude - the latitude where the meter was disengaged
9. store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the 
10. vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip

The last column in data is trip_duration in seconds, which can be used to train the model for prediction.