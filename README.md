# EDA_NYC_TAXI_TRIPS

The aim of this Exploratory Data Analysis was to explore the real world Dataset and generate Insights.</br>

Data set contained 729322 rows and 11 columns. </br>

Variable Info:-</br>

id - a unique identifier for each trip</br>
vendor_id - a code indicating the provider associated with the trip record</br>
pickup_datetime - date and time when the meter was engaged</br>
dropoff_datetime - date and time when the meter was disengaged</br>
passenger_count - the number of passengers in the vehicle (driver entered value)</br>
pickup_longitude - the longitude where the meter was engaged</br>
pickup_latitude - the latitude where the meter was engaged</br>
dropoff_longitude - the longitude where the meter was disengaged</br>
dropoff_latitude - the latitude where the meter was disengaged</br>
store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server (Y=store and forward; N=not a store and forward trip)</br>
trip_duration - (target) duration of the trip in seconds</br>
</br>
Dataset Link:- https://drive.google.com/file/d/13wB3rix52ilaosazN3h06B3JhVT8LyFx/view?usp=sharing
</br>
# METHODOLOGY
Data Loading -> Variable identification & type casting -> Date time Extraction -> missing value identification -> outlier Detection -> KDE & Boxplot Univariate Analysis -> Bivariate Analysis </br>
# INSIGHTS
## Pickup time</br>

![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/140df7a6-eb03-4e7e-a04b-e0ffdd57a537)
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/b937543d-a270-4e21-86e3-cd6e0f57b18f)

## Trip duration of all trips</br>

![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/3db2256f-efcc-4d1a-b367-7f36ce0ec812)
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/3b6276f2-16dd-492e-a565-efe929803185)

![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/ee146648-d1cb-4520-bbd4-dedc99473586)
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/821612da-92cd-45ad-8ad3-adbc33eb3c64)

## Passenger Count</br>
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/3e2085f8-18ef-4c17-a439-6882b1b8aa09)
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/25454eb8-22a2-47c8-9d89-51a3f5458479)

## Vendors
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/f95a9e09-af3d-4240-a8d0-977742933eaf)
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/483b371b-8104-45e7-9240-af05cf8eebf0)

## Vendors' Average trip duration (in seconds) 
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/e926d185-8360-4443-9876-ec11b0ade5a4)

## Vendors' Average passenger count
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/352bbe6a-4f5d-4d24-aee9-cad0a8ba7b6a)

## Trips having active internet network
![image](https://github.com/DAKSH1-HUB/EDA_NYC_TAXI_TRIPS/assets/81084807/0f4ef319-f8aa-4d3f-a780-8c2c423b0826)





















