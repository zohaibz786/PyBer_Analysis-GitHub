# PyBer_Analysis
## 1. Overview of the analysis: the purpose of the new analysis.

The main purpose of this analysis is to provide clean and clear data analysis and visualizations to help PyBer improve access to ride-sharing services and determine affordability for underserved neighberhoods.
The data we'll work on is provided by PyBer in a CSV files format. We'll use a variety of Python libraries (Pandas, Matplotlib, ) to produce a summary DataFrame as well as generating a line chart based on the created DataFrame.

## 2. Results: differences in ride-sharing data among the different city types.
### Fig 1. Total fare by city type
![PyBer_fare_summary](https://user-images.githubusercontent.com/66907301/187660847-00faf7d3-6719-49a5-a306-2be0bc02520c.png "Total fare by city type")
From Fig 1. above we can observe that the monthly income of PyBer between January and early May is fairly stable. When it comes to generating profit, the Urban cities generate the most of the latter, followed by Suburban and Rural cities. Logically that would be expected given that the Urban are usually crowded than Suburban and Rural cities.

### Fig 2. Summary Dataframe by City Type
![df](https://user-images.githubusercontent.com/66907301/187662522-2a6f2c97-c4d2-4d8e-a943-47f090fb5dad.PNG "Summary Dataframe by City Type")

beside the difference noticed from Fig 1. the summary DataFrame shows huge differences between the Urban cities and Suburban or Rural cities when it comes to the number of rides as well as the number of drivers.
- The Urban cities has 13 times more rides compared to Rural cities and 2.6 times more rides compared to Suburban cities. 
- The Urban cities has almost 31 times more drivers compared to Rural cities and around 5 times more drivers than the Suburban cities.

When it comes to the Average fare per Ride the DataFrame shows That Rural city surpass the Urban and Suburban cities.
- The average fare per ride in Urban cities is 30% less than that of Rural cities.
- The average fare per ride in Suburban cities is 10% less than that of Rural cities.
Finally concerning the average fare per Driver, the Rural cities top the other city types.  

### **Conclusions**

1. Urban cities generate the most profit for PyBer
2. Customers in Urban cities pay less per ride and therefore drivers earn less per ride
3. Rural areas seem to be underserved and customers in those areas face more expensive fares than in Urban or Suburban cities

## 3. Summary: three business recommendations to the CEO for addressing any disparities among the city types.
1. Instead of focusing on just the first third of the year, the study may gain from having extra data points that span the entire year and provide insights into yearly trends.
2. It seems like the Rural cities are underserved, but it would be neccesary to perform a market study to confirm if there is enough demand in this market segment to justify investing in hiring more drivers.  
3. Based on the relationship of Urban cities of `2405 Drivers/1625 Rides = 1.48 Drivers/Ride`, the total number of drivers in Rural areas shold be increased at least to **185** `(78 drivers * 1.48 = 185 drivers)`, but this increase has to be supported by a market study, as explained in #2.
4. Using the same metric as in #3 above, the number of drivers in Suburban cities should be increased to a minimum of **726**















