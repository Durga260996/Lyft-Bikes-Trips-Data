# Lyft Bikes Trips Data Exploration
## by Dugra Prasad Reddy Kasireddy

## Introduction

This dataset provides the detailed inforamtion of the trips of the customers of the lyft bikes. There are multiple datasets which are alingned in year-month order expect for 2017 which has cumulative data.  
Each trip is anonymized and includes:

- Trip Duration (seconds)
- Start Time and Date
- End Time and Date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)
- Member Year of Birth
- Member Gender

The data consits trip duration given in seconds and I converted it into minutes. The age was calculated by subtracting birth_year from the present year. Ride distance was calculated from the start and end points latitudes and logitudes data. age_groups was formed by categorizing the age's from age column. date, weekday were extracted from start and end times columns.
