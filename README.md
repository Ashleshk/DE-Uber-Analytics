## Data Engineering
#  Uber Data Analytics Using Google Cloud Platform (GCP)

Thanks to Darshil Parmar for Hands-on project

# Introduction
The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, Compute Instance, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## Architecture

![architecture](https://github.com/Ashleshk/DE-Uber-Analytics/blob/main/architecture.jpg)

## Data Model Chart

prepared datamodel on **Lucidchart**, click [here](https://lucid.app/lucidchart/ea2e0389-8285-4e53-ae9c-65aa86127e2e/edit?viewport_loc=-264%2C-113%2C2594%2C1288%2C0_0&invitationId=inv_f2c9b5c0-5ee0-4f9f-ac4e-c0c0532a189f)

![dataModel](https://github.com/Ashleshk/DE-Uber-Analytics/blob/main/dataModel.png)

- Data Preparation & Cleaning: 
    - changed datetime attributes (tpep_pickup_datetime, tpep_dropoff_datetime) to datetime format.
    - Dropped duplicates and reseted indexes


## Dataset Used
TLC Trip Record Data Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

Here is the dataset - [link](https://github.com/Ashleshk/DE-Uber-Analytics/blob/main/data/uber_data.csv)

More info about dataset can be found here:

Website - https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page
Data Dictionary - https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf