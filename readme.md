Generate an API hey from https://openweathermap.org/api
Analysis:-
The plot on Latitude vs Temperature shows that the temperature is highest at the equator and lowest at the poles.
The humidity at the equator is in the range from 50%-100%. However, the trends does not change based on the latitude.
There seems to be no co-relation of cloudliness with respect to the latitude.
The windspeed for most cities fall under 20(mph) and there seems to be no trend on the windspeed with respect to the latitude
Steps:
# Import the Dependencies
# The Latitudes range considered from Equator : -90 to 90 & Longitudes range considered from Primeredian: -180 to 180
# Ramdomly generate co-ordinates by setting Latitude and Longitude.
# Create a dataframe from the random sample of Latitude and Longitude.
# Create new columns City and Country for storing the details corresponding to the co-ordinates.
# Drop the Latitude and Longitude as the values of the nearest city and not the excat co-ordinates of the city.
# Get data for each city in unique_cities_data.(Perform API Calls)
# Create an "extracts" object to get the various parameter required to form the weather data table.
# Create a Pandas DataFrame with the results.
# Plot Graphs.
