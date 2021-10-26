# PyBer_Analysis

**## Overview **

The purpose of this analysis was to gather and display the total fares (in $ USD) from January 2019 through April 2019 for PyBer rides in the three types of cities where PyBer operates: Rural cities, Suburban cities, and Urban cities. 

### Methods

I used Pandas to read the data-containing CSV files into DataFrames, which were then manipulated further to obtain the requested metrics per city type. These metrics included total rides, total drivers, total fares, and average fares per ride and per driver. 
A new DataFrame was then created to display the total, daily fare for each type of city. The total fares for each city type (Urban, Suburban, and Rural) were plotted using Matplotlib as three individual lines on one plot. The time range used was January 1, 2019 - April 29, 2019, and the results were visualized on a weekly basis during this time range. 

**## Results **

![image](https://user-images.githubusercontent.com/90593897/138783623-52b64a23-b5c0-4b5e-b149-2c101d5b8502.png)
As pictured by the DataFrame above, urban cities have the largest number of rides within the measured timeframe, the largest number of drivers, and the most affordable prices per ride and per driver. They also brought in the largest amount of revenue compared to suburban and rural cities; total fares were about twice as much as suburban city total fares, and almost ten times more than rural city total fares. 

The opposite trend can be seen with rural city data. Rural cities had the lowest number of rides within the measured timeframe (125 rides), and the lowest number of drivers (78 drivers). They brought in the least amount of revenue within the given timeframe ($4,327.93), yet their average fares were the most expensive both per ride and per driver. By comparing this with the urban city data, it may be financially beneficial for PyBer to think about how to increase business in rural cities to lower fares and bring in more revenue within rural cities. 

Suburban city data lies in the middle--they have roughly half the number of rides as urban cities, a fifth of the amount of drivers as urban cities do, and they bring in around half the amount of revenue that urban cities do in total fares for the measured timeframe. 
Suburban cities do have about 5x more rides, drivers, and total fares than rural cities do.
Their average fares, both per ride and driver, are in between that of rural and urban city fares however, they are closer to the more-expensive rural average fares.


![PyBer_fare_summary](https://user-images.githubusercontent.com/90593897/138785532-b17ec4c9-b3c8-4dee-802b-126f57335c6e.png)

Finally, as can be visualized by the graph above, the three city types are consistent in the total fare prices between January and May of 2019. Urban cities consistently bring in the most revenue in total fares, rural cities consistently bring in the lowest, and suburban cities consistently has total fares that fall in between urban and rural city fares. While there are peak weeks for each city type, they overall tend to perform the same over the measured time. 

**## Results **

Based on the data gathered in this analysis, PyBer should explore methods to increase their business in suburban and rural cities. This could include allocating resources to target the smaller city types in terms of marketing to attract more employees (drivers) and customers. After all, it would benefit both PyBer and the citizens of these smaller cities for the company to be able to provide more affordable fares, and increase the overall number of rides in these cities like they have in urban cities. 

PyBer should also analyze their most successful market as well--urban cities. As can be seen from the graph, urban cities consistently bring in the highest number of total fares no matter the month. On average, customers in urban cities pay the lowest amount for fares per ride and by driver. The company should dig deeper to identify factors that contribute to their success aside from the obvious--that urban cities are more densely populated. Tey may discover trends that can then be applied to increase total fares in suburban and rural cities. 

Second, it can be seen there is a peak in total fares for all three city types during the last week in February of 2019. It could be beneficial to determine the reason for this spike in service-use during this time in all three types of cities so PyBer can plan for future years and know if they will need to hire more drivers during this time to meet demand. 
