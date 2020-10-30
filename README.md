# Python-API-Challenge

Part 1: WeatherPy

A Python script utilizing OpenWeatherMap API was created to visualize the weather of 500+ random cities across the world with varying distance from the equator. The following scatter plot models were created to represent the weather across these cities:
  * Temperature (F) v Latitude
  * Humidity (%) v Latitude
  * Cloudiness (%) v Latitude
  * WInd Speed (mph) v Latitude

These cities were then divided into northern and southern hemispheres, and linear regressions were run on each relationship. The city list was saved as a CSV file, analysis was made after each plot, and all the figures were saved.

------------------------------------------------------

Part 2: VacationPy

Using the cities CSV file from part 1, a heat map was created displaying he humidity from every city. A DataFrame was also created to find cities meeting ideal weather critera: between 70 and 80 degrees F, wind speeds less than 10 mph, zero cloudiness. Using Google Places API, the first hotel in each city within 5000 meters was located and pinned onto the heatmap.

