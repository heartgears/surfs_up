# surfs_up

## Overview ##
This analysis concerns a surfing and ice cream shop in Hawaii, designed to attract a potential investor in the company. The analysis was performed on weather data by using SQLite/SQLAclchemy and Python.

## Technologies & Requirements
* Data Source: SurfsUp_Challenge_starter_code.ipynb named later as SurfsUp_Challenge.ipynb
* Data File: hawaii.sqlite
* Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas, Numpy, Sqlalchemy.

## Results ##
- The average temperature in both months was only a difference of approximately 3 degrees.
- The standard deviation for temperature was wider in June than in December.
- This was due to the wider range of temperatures in June than December - June had a range of temperatures spanning 21 degrees, while December had a range of 27.

### Deliverable 1
* A query is written to retrieve the June temperatures from the date column of the Measurement table.
* The temperatures are added to a list.
* The list of temperatures is converted to a Pandas DataFrame.
* Summary statistics are generated for the DataFrame.

### Deliverable 2
* A  query is written to retrieve the December temperatures from the date column of the Measurement table.
* The temperatures are added to a list.
* The list of temperatures is converted to a Pandas DataFrame.
* Summary statistics are generated for the DataFrame

## Summary ##
The data analyzed here only concerns temperature, but there are lots of other weather variables that could affect how that feels, such as precipitation, humidity, wind speed, etc. A more thorough analysis would account for factors like these and the heat index or wind chill.
