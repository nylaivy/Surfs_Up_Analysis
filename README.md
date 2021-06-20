# Surfs_Up_Analysis

## Overview Of Analysis

SQLite and SQLAlchemy were used to run queries on weather data for analysis. Python and Jupiter Notebook were also used to help with the analysis. The dataset used was weather data from Oahu Hawaii to help seasonal businesses, such as surf shops, identify less than ideal weather and help them better prepare to stay in business.

## Results

- Temperatures in June seem to be slightly higher than temperatures in December when comparing the average, min, and max temperatures. This can be seen in the summary statistics tables for each month below.

- There is a larger range of temperatures accounted for in the percentiles and when looking at the min and max for December relative to June. There therefore seems to be more variety in weather during December

- I also noticed that there is more data for June (there is a count of 1700) versus December (there is a count of 1517)

![juneSummary](juneSummary.png)
![decemberSummary](decemberSummary.png)


## Summary
While there are small differences between the weather trends in June and December, overall the temperature summary statistics for each month are relatively similar (averaging in the seventies) showing that the surf and ice cream shop business could in fact be sustainable year-round if we are just considering temperature. Additional queries for weather data for June and December to help determine the sustainable nature of the business could include doing the same analysis considering rain, wind, or cloudiness as opposed to temperature.
