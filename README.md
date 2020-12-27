# PyBer_Analysis

## Overview
Ride-sharing app company 'PyBer' needed ride-sharing data from January 2019-May 2019 analyzed and visualized.  Data from urban, suburban, and rural cities was provided.  Using Python libraries 'Pandas' and 'Matplotlib', a muliple-line graph chart that shows the total weekly fares for each city type was produced.  This analysis will summarize how data differs by city type and how those differences can be used by senior leadership at PyBer.

## Resources
- Jupyter Notebook
- Python v3.7.x
    - Dependencies:
        - matplotlib.pyplot
        - pandas
- [city_data.csv](https://github.com/acfthomson/PyBer_Analysis/edit/main/Resources)
- [ride_data.csv](https://github.com/acfthomson/PyBer_Analysis/edit/main/Resources)


## Results
PyBer ride-sharing data was combined from [city_data.csv](https://github.com/acfthomson/PyBer_Analysis/edit/main/Resources) and [ride_data.csv](https://github.com/acfthomson/PyBer_Analysis/edit/main/Resources) in order to produce a summary of Total Ride, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver.

[![pyber-summary-df.png](https://i.postimg.cc/9f42xYzq/pyber-summary-df.png)](https://postimg.cc/4KTjyt6J)

Urban cities have approximately 2.6 times and 13 times as many total rides than suburban and rural cities, respectively.  Urban cities also have nearly 5 times as many drivers as suburban cities and nearly 31 times as many driveres as rural cities.

Total fares collected for this data set, which spans from January-May 2019 is $63,538.64.  Rural cities make up just 6.8% of total fares collected, while suburban and urban cities make up 30.5% and 62.7%, respectively.

Average fares per ride are higher in rural areas, with rural rides costing approximately 10.5% more than suburban cities and 29.1% more than urban cities.

Average fares per driver are lower in urban areas.  Urban fares are 58% cheaper than suburban fares and 70% cheaper than rural fares.

