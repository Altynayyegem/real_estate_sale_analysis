# Real Estate Sales Analysis (USA, 2001-2022)

## Introduction: 
This project analyses real estate market dynamics and transaction analysis

## Dataset
- Source: DataGov (https://catalog.data.gov/dataset/real-estate-sales-2001-2018)
- Size: 1,097,631
- Description: Price, Assessed Value, Location, Property Types

## Tech Stack  
- Python: Pandas, Numpy, Matplotlib, Pyplot
- SQL: SQLite for querying data, CSV, prettytable

## Steps Taken  
- Data Cleaning (importing, handling missing values, standardizing categorical data, correcting data format, binning, binning visualisation)
- Exploratory Data Analysis (trends, transactions)

## Results: During the exploratory analysis, the insights suggest that there had been a positive trend in price increases from 2001 to 2022. In addition, results represent a positive correlation between increasing assessed values and sale amounts. Yet, the correlation is not perfect, and other factors could influence the growth in sale prices over time. Next, the findings determined that apartments are the most expensive among other property types, while public utilities are the least costly. Finally, results identified Greenwich as the most expensive town in the United States. Meanwhile, the highest transactions occurred in Bridgeport, Stamford and Waterbury.

## Next Steps: Further analysis is suggested based on the given exploratory analysis. This analysis can include the cause of high transactions in the top cities and the reason for increasing sale prices. Since the correlation between increasing assessed value and sale amount did not show the perfect positive correlations.
In addition, the limitation for data cleaning exists due to the size of the dataset. The limitation consists of repeating raws with the same town name, address, and assessed value, while the varying sale amounts are comparatively low. That implies one assessed value on the entire block with clustered properties. Those properties were sold separately, contributing to separate transactions at different times. Future analysis could include the aggregated data frame for further investigations.





