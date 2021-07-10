# PyBer Ride Share Analysis

# Overview

PyBer, a Python based ride sharing app company, has requested us to review app data to improve access to ride sharing services and determine affordability for under-served neighborhoods. We are finding ride sharing data by city type and, through the use of written and visual reports, submitting business recommendations to PyBer decision-makers for addressing disparities among the city types.


## Process:
STEP 1: Use the provided csv files to create a ride-sharing summary DataFrame by city type. To do this, we found the below data: 
1. Total Rides by City Type
2. Total Drivers by City Type
3. Total Fares by City Type
4. Average Fare per Ride by City Type
5. Average Fare per Driver by City Type

STEP 2: Using the ride-sharing summary DataFrame, we created a multiple-line chart of total fares for each city type: 
1. Found total fares for each type of city by the date
2. Used a sample of ride sharing data for January 2019 through April 2019 for our multiple-line chart
3. Created a multiple-line chart to visualize Total Fare by City Type data


## Resources:
Data Sources: [city_data.csv](https://github.com/corispade/PyBer_Analysis/blob/main/Resources/city_data.csv), [ride_data.csv](https://github.com/corispade/PyBer_Analysis/blob/main/Resources/ride_data.csv)

Software: Python 3.7.6, Conda 4.10.1

Environment: Jupyter Notebook

Dependencies: Pandas, Matplotlib


# Results:

Find the completed PyBer Ride Share Analysis [here](http://localhost:8889/notebooks/PyBer_Analysis/PyBer_Challenge.ipynb) for reference.

STEP 1: Reference the DataFrame image below: 

  * Total Rides By City Type: The urban city type had the most total rides by 1,000 over suburban and 1,500 over rural. 

  * Total Drivers: The urban city type had the most total drivers by 1,915 over suburban and 2,327 over rural. 

  * Total Fares: The urban city type had the highest total fares by $20,498 over suburban and $35,526 over rural. 

  * Average Fare per Ride: The rural city type has the highest average fare per ride by $3.65 over suburban and $10.09 over urban.

  * Average Fare per Driver: The rural city type has the highest average fare per driver by $15.99 over suburban and $38.92 over urban.

  * Total Fare by City Type: 

![summary](https://github.com/corispade/PyBer_Analysis/blob/main/Analysis/Summary_dataframe.png)


Step 2: We created a muliple-line chart to visualize the Total Fare by City Type. See results below:

   * Due to the limited number of drivers and rides, rural city types had the lowest total fare by city type.
   * Due to the greater number of drivers and rides, urban city types has the highest total fare by city type.
   * For all city types, there is a spike in total fare in late February.

![line_chart](https://github.com/corispade/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)


# Summary:
Based on the above results, we suggest the following business recommendations for addressing disparities among the city types:

1. Improve access to ride sharing services. One potential solution would be to increase the "hail radius" so that customers can hail cars from further distances. This will increase the number of potential drivers to allow for greater opportunity for rides. 

2. The average fare per ride in the rural city types is higher than suburban or urban. There could be numerous reasons for this, but two examples to highlight are the limited number of rural drivers and potential increase of ride distance due to the rural setting. The higher fare is beneficial to drivers, but not beneficial to riders. Find a way to increase affordability without discouraging drivers. For example, an option for a flat-rate charge based on ride length or ride time could be beneficial. 

3. There is a total fare spike in all city types in late February. There seems to be a greater demand for rides at this time. Take a larger sample of data to determine the highest demand for drivers throughout the year and capitalize on the demand. More available drivers could mean a greater opportunity for rides. 

4. A few additional recommendations for analysis improvement: 
   * Find the data of cost per mile for a more specific analysis.
   * Does the fare increase or reduce at certain times of day or holidays? Find this data to dig deeper. 
   * Maybe people in rural areas don't have access to the app. Survey rural areas and discover ways to improve access to PyBer.
