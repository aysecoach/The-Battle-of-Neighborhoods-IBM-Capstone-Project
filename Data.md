# Data
Population of each borough is gathered by using web scraping method from a website [1]. 
It has been searched in web and only the population of main thirty six neighborhoods in Brooklyn is found. 
In addition, by using Geocoder Python package [2], latitude and longitude data of each neighborhood is retrieved. 
Also, to get venues and venue categories of each neighborhood Forsquare API [3] is used.
Moreover, to create a map of neighborhoods by using latitude and longitude values, Folium package [4] is used.
Boroughs and neighborhoods in each borough with their latitude and longitude values in New York is gathered from IBM Developer Skills Network [5]
#### Population, latitude and longitude values of Brooklyn neighborhoods are listed in the table by using Geocoder.
![image](https://user-images.githubusercontent.com/82239473/118260736-556ca680-b4bb-11eb-8ac0-450bfcd4fa52.png)

#### The neighborhoods of Brooklyn are pinned in the map by using Folium Map.
![image](https://user-images.githubusercontent.com/82239473/118260824-7208de80-b4bb-11eb-8c80-26356533fcc6.png)

#### Venues, venue categories, longitudes and latitudes are listed in table by using Foursquare API.
![image](https://user-images.githubusercontent.com/82239473/118260890-864cdb80-b4bb-11eb-9ae8-a4152fd48395.png)


#### [1] Population of Brooklyn Neighborhoods. URL: https://www.worldatlas.com/articles/brooklyn-neighborhoods-by-population.html
#### [2] Geocoder. URL: https://geocoder.readthedocs.io/index.html
#### [3] Foursquare: URL: https://foursquare.com/
#### [4] Folium Map: URL: https://pypi.org/project/folium/
#### [5] New York Boroughs: URL: https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/labs/newyork_data.json
