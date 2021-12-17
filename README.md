# PyBer_Analysis
## Overview of the analysis: the purpose of the analysis
The purpose of this analysis is to analyze and create visualizations for all major data from January to early May of 2019 for PyBer, a ride-sharing company. It is to also create a summary DataFrame of the ride-sharing data by city type. Using the Pandas and Matplotlib libraries, this report will include multiple-line graphs of total weekly fares for each city type. The data includes the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

## Resources:
### Data Source:
- city_data.csv
- ride_data.csv

### Software:
- Python 3.10
- Jupyter Notebook 6.4.5
- Matplotlib 3.4.3
- Pandas 1.3.4

## Results: the differences in ride-sharing data among the different city types
### Summary DataFrame
![1](https://user-images.githubusercontent.com/33900637/146473771-45483611-61a3-4124-b589-f6eb3fa65a78.png)

Based on the Pyber summary DataFrame, there are significant differences in ride cost and activity between the rural, suburban, and urban cities. The data based on city type shows an overall direct relationship between total rides, total drivers, and total fares, and it also shows an inverse relationship for average fare per ride and average fare per driver. While the total fares in urban cities is higher than that of suburban and rural ones, it seems that the total number of drivers has a greater effect on the average fare per driver, causing it to be highest in rural cities.

### Multiply-line chart 
![PyBer_fare_summary](https://user-images.githubusercontent.com/33900637/146473790-adc293ae-0a11-40d4-828d-51f05baa89da.png)

This leads us to expect an increase in price based on decreased demand, increased distance, and driver availability. In urban areas, the number of drivers is greater than in rural areas, which results to an increased relative demand. Since, as shown in the Pyber summary DataFrame, there are so many drivers in the urban area by the contrast between the total number of rides and the total number of drivers. Prices are likely also increased in rural areas based on the distance between destinations. The line chart shows an overall higher volume in total fares for urban areas, lowest volume for rural areas, with suburban falling in between.

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
Based on the above results, the following three business recommendations:
1. Focus recruitment resources in rural and suburban areas to to increase the number of available drivers at a given time and to accommodate this increased demand. while decreasing recruitment in urban areas. 
2. Place a cap on fare to keep the service affordable in rural areas. This would make it more accessible while still allowing for profit.
3. Increase user-facing marketing efforts across the board, but particularly in urban areas, focusing on the services affordability across  and short wait times based on driver availability.
4.  Use technology to better understand how the three city types are being used by riders to make the drivers' rides more efficient and available to riders. Such as, if the rider's destination is known, technology such as the web/app can be used to match a driver with the next rider for pick up who is in the same area and around the same time as the drop off while being a manageable route. Another use for technology is for drivers to make more pick ups on their way to a destination with a rider who is headed in the same direction with a manageable route. Thus, making it also more affordable for riders too.
