# python_kaggle_co2_emissions
Runs on the dataset in Kaggle at https://www.kaggle.com/datasets/ulrikthygepedersen/co2-emissions-by-country. 

CO2 Emissions Trending and Prediction

Thank you for sharing this dataset Ulrik Thyge Pedersen.

The first code cell is where you may change the country for which to study a trend and prediction. The world trend is also shown. Just change the country name and Run All.

The country Sweden began showing a decline in CO2 emissions after 1970.0 The country Djibouti began showing a decline in CO2 emissions after 2013.0 The year 1996.7692307692307 is the mean for when CO2 emissions at a decline were at their peak. 104 countries have shown a CO2 emission decline.

I could add splines. Instead, I put in a quick check to choose quadratic plots for countries that have significantly lowered their CO2 emissions since the mean of the peak year when those 104 counties began to show a decline in CO2 emissions. The world is showing a linear increase in CO2 emissions. With leading indicators, the trending could be made more precise and maybe more accurate.

Ulrik also shared population data, and examination of it suggests population declines are similar. The country St. Kitts and Nevis began showing a decline in population after a maximum size in 1960.0 (per the 1960 start) The country Lebanon began showing a decline in population after a maximum size in 2015.0 The year 1997.9268292682927 is the mean for when populations with a decline were at their peak. 41 countries have shown a population decline. https://www.kaggle.com/thomasgamet/population-forecasting-using-only-population-data

Population size and CO2 emissions are likely correlated, but it is not evident that CO2 emission changes must follow from population size changes. For example, Iceland is an outlier today with a population increase while its CO2 Emissions decrease. However, both Population size and CO2 emissions are linearly increasing on a global scale. The mean year for decreases of population and CO2 emissions are also very close (1996 and 1997 assuming the calculations are correct for these data sets).

Personal note, hopefully renewable energy and fusion nuclear energy production will some year soon start a global downward trend on CO2 emissions (not counting the 2020 year which will likely be treated as an outlier). Still, until the evidence is clear, the past trends will likely continue which is what this type of forecasting tries to show.
