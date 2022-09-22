# World Weather Analysis
### Plan your next big adventure
-----
PlanMyTrip is an industry leader in travel destination planning. PlanMyTrip wants to develop real-time suggestions to help clients find their ideal vacation destination and lodging, helping them plan their dream vacation.
<BR>
<BR>
### Resources
  • <a href="https://numpy.org/doc/stable/index.html">NumPy</a><BR>
  • <a href="https://pypi.org/project/citipy/">citipy</a><br>
  • <a href="https://developers.google.com/maps/documentation/directions/overview">Google Directions API</a><BR>
  • <a href="https://developers.google.com/maps/documentation/places/web-service/overview">Google Maps API</a><BR>
  • <a href="https://openweathermap.org/api">OpenWeatherMap API</a>
  <BR>
  <BR>
  
### Methods
I began by using NumPy to generate a list of 2,000 random sets of global coordinates, I then used citipy to determine the nearest city to each coordinate. Of those 2,000 selections, 677 were returned as viable vacation options. I called on the OpenWeatherMap API to retrieve the weather patterns and current conditions for each city.
<BR><BR>

### Planning the trip
Our client prefers temperatures that range between 75-85°F. They want to see the sights while being sure to get some beach time in. This information helped me narrow the destinations further and ultimately the clients decided to visit Brazil. After browsing the heat map, we got to work deciding which cities they should visit. They will be renting a vehicle in the city of Pilar, visiting 3 cities, then returning to Pilar for their journey home.  <BR>
<img src="https://github.com/meggrooms/World_Weather_Analysis/blob/main/Figures/Heat_Map.png">  
  
<BR>
<img src="https://github.com/meggrooms/World_Weather_Analysis/blob/main/Figures/DF-all_four.png">
  <BR><BR>
  
### The itinerary
Once the client decided on their destination I went to work planning their epic Brazilian road trip. The journey begins in Pilar, Brazil. Our clients will travel to Tamandare, Maragogi, & Maceio before they return to Pilar.
<br>
<img src="https://github.com/meggrooms/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map.png">
    <BR><BR
            
The interactive map I provided the clients was well received, providing exactly the information needed to plan their trip.<BR>
<img src="https://github.com/meggrooms/World_Weather_Analysis/blob/main/Vacation_Itinerary/WeatherPy_travel_map_markers.png">
      <BR><BR>

