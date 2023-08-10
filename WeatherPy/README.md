# python-api-challenge

Created by: Alex Calametti

Overview:
This project visualizes weather data from a random selection of cities and was also used to plan an ideal vacation. This was done using two separate APIs: Weather Open API and Geoapify. The first portion of the project uses random selection to select cities across the globe. These cities were then plotted using different variables and the linear regression was calculated. The second portion of the project used the same cities to create an ideal vacation based on selected criteria for each variable. This data was then used with Geoapify to locate the nearest hotel. For this project you will need Jupyter Notebook and api keys generated from their corresponding website. 

Part 1: 
To begin the cities were randomly selected and placed into a pandas data frame. The API data was then stored as a json file in order to make the data easier to work with. Plots were then created to evaluate different weather variables such as maximum temperatures, cloudiness, wind speed, and humidity based on each locations latitude. Then each varaible was evaluated based on whether the location falls in the northern or southern hemisohere. These were then further evaluated using regression plots to identify any variable relationships that may be present. 

Part 2: 
The cities selected from the preivious part were plotted on a map with their dot sizes based on humidity. The data was then narrowed based on my ideal weather values with null values being dropped from the dataset. Then the data frame was copied and a new column for hotel names was added. Geoapify was utilized to find hotels within 10,000 meters of each location and plotted on a map. 

Big thanks to Geronimo Perez for helping me get started on this project and shoutout to the Learning Assistants that helped me tweak my code. 
