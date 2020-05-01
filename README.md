# BerlinHousePricePrediction

The Notebook consists of two parts:
1 - Exploratory Data Analysis:
- The main purpose of this analysis is to detect interesting insights for potential real-estate companies.
- The data is clean (no duplicates) but not all the columns provided are complete.

2 - Regression Model:
- Predict apartment price square meter (price_m2) using the features provided or your own features created.
- In this challenge the accuracy of the result is not the most important thing. The main objective is to discuss about the pipeline followed (imputation, selection, training, testing ...)

Original Imput Features:

id: Unique identifier of the apartment
property_type_id: always '3' (means apartment)
market_type: always 'rent'
price_m2: apartment price square meter
area: apartment area
building_year: year when the building was build
posted_at: date the apartment was listed in the web page for rent
ended_at: date the apartment was removed from the web page
num_days: days between posted_at and ended_at
zip_code: zip code
city_id: id of the the city (always 11000000 -> Berlin)
district_id: subdivision of zip_codes
zone_id: subdivision of district_id
street: apartment street
street_number: apartment street number
latitude: apartment latitude
longitude: apartment longitude
floor: apartment floor
num_rooms: all rooms of the apartment (bedrooms, salon...)
living_space: apartment area excluding exterior zones
num_bedrooms: apartment number of bedrooms
num_bathrooms: apartment number of bathrooms
num_floors: building number of floors
apartment_type: apartment classification (in german)
condition: apartment condition (in german)
interior_quality: apartment quality (in german)
description: apartment description (in german)
