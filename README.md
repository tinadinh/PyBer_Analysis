# PyBer_Analysis
## Overview of the analysis: Explain the purpose of the new analysis.
The purpose of this analysis is to analyze and create visualizations for all major data from January to early May of 2019 for PyBer, a ride-sharing company. It is to also create a summary DataFrame of the ride-sharing data by city type. Using the Pandas and Matplotlib libraries, this report will include multiple-line graphs of total weekly fares for each city type. The data includes the total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type.

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Based on city type, the data showed an overall direct relationship between total rides, total drivers, and total fares, and showed an inverse relationship for average fare per ride and average fare per driver.
![1](https://user-images.githubusercontent.com/33900637/146473771-45483611-61a3-4124-b589-f6eb3fa65a78.png)

User knowledge of ride-sharing services and basic economics lead us to expect an increase in price based on decreased demand, increased distance, and driver availability. In larger cities and urban areas, the number of drivers is about 30 times greater than in rural areas, which translates to an increased relative demand. In fact, there are so many drivers in the urban area that at any given time, many drivers are not contracted, as shown by the contrast between the total number of rides and the total number of drivers. Prices are likely also increased in rural areas based on the distance between destinations. At a glance, the line chart shows exactly what's expected: an overall higher volume in total fares for urban areas, lowest volume for rural areas, with suburban falling in between.
![PyBer_fare_summary](https://user-images.githubusercontent.com/33900637/146473790-adc293ae-0a11-40d4-828d-51f05baa89da.png)

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.
