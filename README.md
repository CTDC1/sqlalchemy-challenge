# sqlalchemy-challenge

This repo contains data analysis and exploration for a CSV file containing weather readings and the station in which it was logged. Additionally, this repo has an app that shows the following data:
-	Precipitation for the year 
-	Stations that logged the data
-	Min, Max, and Avg

This repository includes two different documents of code: climate_starter and app.py. 

Climate Starter:
	This file includes data analysis for the weather readings in Hawaii. I analyzed the precipitation and station data for the last 12 months and then plotted them on a bar graph and histogram. 

App:
	This file includes a Flask API based on multiple queries I have created. The routes are as follows:

-	/
-	/api/v1.0/precipitation
-	/api/v1.0/stations
-	/api/v1.0/tobs
-	/api/v1.0/<start>
-	/api/v1.0/<start>/<end>

Notes:
I consulted a tutor for the first section of this homework.
