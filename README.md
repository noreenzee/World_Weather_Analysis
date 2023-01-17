# World_Weather_Analysis


# Basic Project Plan:
Following plan is provided in the module to work on this challenge
Here's an outline of your project plan:

Task: Collect and analyze weather data across cities worldwide.
Purpose: PlanMyTrip will use the data to recommend ideal hotels based on clients' weather preferences.
Method: Create a Pandas DataFrame with 2000 random cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.
The data will be split into three main parts, or stages.

# Collect the Data

Use the NumPy module to generate more than 1,500 random latitudes and longitudes.
Use the citipy module to list the nearest city to the latitudes and longitudes.
Use the OpenWeatherMap API to request the current weather data from each unique city in your list.
Parse the JSON data from the API request.
Collect the following data from the JSON file and add it to a DataFrame:
City, country, and date
Latitude and longitude
Maximum temperature
Humidity
Cloudiness
Wind speed
Exploratory Analysis with Visualization


# Deliverable 1: Retrieve Weather Data
For this deliverable, you'll generate a set of 2,000 random latitudes and longitudes, retrieve the nearest city, and perform an API call with OpenWeatherMap. In addition to the city weather data you gathered in this module, use your API skills to retrieve the current weather description for each city. Then, create a new DataFrame containing the updated weather data.
# Deliverable 2: Create a Customer Travel Destinations Map
In this deliverable, you'll employ input statements to retrieve customer weather preferences. Next, you'll use those preferences to identify potential travel destinations and nearby hotels. Finally, you'll show those destinations on a map. Customer Travel Destination Map is as follow:
![image](https://user-images.githubusercontent.com/112978144/213019733-cfc2997c-28a1-481a-b4e0-0daa5b9749b5.png)
# Deliverable 3: Create a Travel Itinerary Map
For this deliverable, you'll use the Geoapify Routing API to create a travel itinerary that shows the route between four cities chosen from the customer’s possible travel destinations. Then, you'll create a map with a pop-up marker for each city on the itinerary.
![image](https://user-images.githubusercontent.com/112978144/213020262-1a3dbb1b-ab71-40dd-b7a2-bace6097ead8.png)
