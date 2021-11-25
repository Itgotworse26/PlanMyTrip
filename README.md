# PlanMyTrip-
Challenge Assignment for Module 6

Jack loves the PlanMyTrip app. Beta testers love it too. And, as with any new product, they’ve recommended a few changes to take the app to the next level. Specifically, they recommend adding the weather description to the weather data you’ve already retrieved in this module. Then, you'll have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. Finally, using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Summary on using the Beta
The basic architecture of PlanMyTrip works. The syntax is able to call APIs, mine data from then, use the data to build dataframes, and then use additional APIs from Google Maps to build a desired iteniary based off of desired minimum and maximum temperature.

However, there are some comments I want to note with Jack after attempted personal use of the beta.

First off, I was unable to figure the syntax or coding that would allow me to call one config.py from one folder. I am unsure whether syntax or dependencies are the issue, but it has forced me to place a copy of config.py in multiple folders. Thankfully, the gitignore successfully made sure that the config.py file would not be pushed to the repository. 

Secondly, calling the APIs to build the populate and build the city_data_df dataframe takes forever. True, APIs are slow in calling data, but the time that is spent calling the data is time users will have to wait while time is a premium for them. While the current crop of beta testers might enjoy the app as is, trying the to add additional data might cause a chillier reception is the general consummer base. 

Also, having the user manually input their city destinations is a hassle. While the intent of this version is to prove that the app works, a more easier method of user input should be looked into before the app goes on the market. Being able to pick and choose from a dataframe, or even choosing from the map directly could be much easier. 