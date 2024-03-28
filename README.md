# lightningMapperv1

For my project application, I want to use my meteorology knowledge and mix it with my newly learned GIS programming skills. I will create an application that shows the live lightning-strike data from various sources, while also allowing the user to add reports of lightning, wind-damage, rainfall, and many other weather impacts. 

The look of the application will consist mainly of a map of their nearby area (using their location, if given the ability to know it). This will allow the user to see nearby strike data in just seconds instead of them having to look up their address on the website. The map will be in the middle of the window, with widgets on the sides of the screen. This will give the user the chance to see the lightning strike data in front of them, instead of having to strain their eyes to find the data they are looking for. On the left side of the screen there will be multiple layers of data that the user can either deselect or select, depending on what they would like the map to look like. For example, they may only want to see the nearby lightning strikes and not the names of cities or roads. In this case, they would only select “strike-data" and then deselect “show road name” and “show city names”. This will make the map less crowded and personalized to what they want. On the right side of the window, this will be where the user can add their own reports to the map. When they add these reports, it will be added to the database, making it shown on other user’s screens as well. I will make sure to have this data will be selectable/reselectable in case some of the reports are inaccurate (maybe even adding a disclaimer will help). This application will be helpful for people doing physical activities outside, since lightning is a killer on the field, pun intended. This will allow them to see when lightning is within 10 miles of their location and suspend these activities until the storm passes. There are apps (like the weather channel) that do similar things to this proposed application, but they are locked behind paywalls that many people do not want to pay for. 

Databases: 

Basemap
Esri.basemap (topo-vector)
https://js.arcgis.com/4.25/ 

GLM Lightning Strike Data
NOAA AWS OpenData
https://registry.opendata.aws/noaa-goes/ 

Other weather data
NOAA/NWS Reports
https://mesonet.agron.iastate.edu/request/download 

