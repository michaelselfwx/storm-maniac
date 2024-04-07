# spc_mapper

Abstract:

For my project application, I want to use my meteorology knowledge and mix it with my newly learned GIS programming skills. I will create an application that shows the live Storm Predicion Center outlooks (mainly convective outlooks), while also allowing the user to add storm reports of high winds, hail, and tornadoes. 

The look of the application will consist mainly of a map of the continental US (CONUS). This will allow the user to see the entire SPC Outlook in just seconds instead of them having to look up the outlook on the website and not know where to go from there. The map will be in the middle of the window, with explandable widgets on the sides of the screen. This will give the user the chance to see the specific SPC outlook data they want in front of them, instead of having to strain their eyes to find the data they are looking for. On the left side of the screen there will be multiple layers of data that the user can either deselect or select, depending on what they would like the map to look like. For example, they may only want to see the convective outlook and not the names of cities or roads. In this case, they would only select “outlook" and then deselect “show road name” and “show city names”. This will make the map less crowded and personalized to what they want. On the right side of the window, this will be where the user can add their own reports to the map. When they add these reports, it will be added to the database, making it shown on other user’s screens as well. I will make sure to have this data will be selectable/reselectable in case some of the reports are inaccurate (maybe even adding a disclaimer will help). This application will be helpful for people doing physical activities outside, since lightning is a killer on the field, pun intended.

Databases: 

Basemap -
Esri.basemap (topo-vector) -
https://js.arcgis.com/4.25/ 

NOAA Storm Prediction Center -
https://spc.noaa.gov/products/outlooks

Other weather data -
NOAA/NWS Reports -
https://mesonet.agron.iastate.edu/request/download 


Workflow:

This website took me more than 30 hours to get it to work right, let alone look appeasing to the user's eyes (whether they are on desktop, tablet, or mobile). 
