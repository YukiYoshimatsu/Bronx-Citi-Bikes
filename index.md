# Citi Bike Project                                           
### The Bronx
#### Ivy Birchall, Yusef Wray, Casey Walsh

##### Introduction
Each of these individual sites represents a group member's work on a specific neighborhood in the Bronx and explains he CitiBike stations that they proposed and why they proposed them. Each team member conducted their own individual research on their respective neighborhood, and used GeoJson to create a map with color coded markers for their first and second choices for CitiBike loctions within a 1,000 square foot grid. Together, they cover the South Bronx neighborhoods and what CitiBike expansion may look like. 

[Mott Haven](https://ivybirch.github.io/Honors-Bike-Website-Test/)
###### Created by Ivy Birchall

[Morrisania](https://yukiyoshimatsu.github.io/morrisania_neighborhood)
###### Created by Yusef Wray

[Port Morris](http://caseywalsh22.github.io/HC1-Neighborhood) 
###### Created by Casey Walsh

##### Mott Haven

##### Morrisania
 
##### Port Morris 
* Port Morris is an industrial neighborhood in the South Bronx.
* Most CitiBike locations were selected based on proximity to schools, stores, bus stops, event venues, and major intersections.
* The addition of CitiBike service to this neighborhood would improve transit, as there are very few bus stops and no subway stops

* It has a population of 3525, and is 52.9% female.
* 24.4% of the population is between the ages of 25 and 34.
* 72.3% of the neighborhood is Hispanic and Latinx Americans
* Port Morris is 474 acres large.

* CitiBikes in Port Morris would make transportation across the neighborhood safer and faster.
* The neighborhood is surrounded by many major roads and bridges, so CitiBikes would be a safer form of trasnportation than walking.
* There is very little public transport in the neighborhood, so CitiBikes will make travel in the neighborhood faster, and make it easier to reach mass transit to travel outside the neighborhood.
* There are some locations where CitiBikes would not be as useful, for example, the various unpaved roads and areas that are mostly shipping centers and warehouses.
 
##### Project Beginnings and Goals
 
Each team member was assigned to an individual neighborhood in the South Bronx. Using Google Maps, we each took a screenshot of our neighborhood. Using Python, we highlighted the area around our neighborhood and layered a grid over our screenshot. Each square within the grid represents 1,000 square feet of area. 

The goal of our project was to propose two station locations for each region and depict our choices through various methods such as folium maps in Python and GeoJson. 

Mott Haven:

![Image of Mott Haven Neighborhood](https://github.com/YukiYoshimatsu/morrisania_neighborhood/blob/master/mott_highlight.png)
![Image of Mott Haven Grid Map](https://github.com/YukiYoshimatsu/morrisania_neighborhood/blob/master/mott_grid.png)

Morrisania:

![Image of Morrisania Neighborhood](https://github.com/YukiYoshimatsu/morrisania_neighborhood/blob/master/mor_border.png)
![Image of Morrisania Grid Map](https://github.com/YukiYoshimatsu/morrisania_neighborhood/blob/master/mor_grid.png)
 
Port Morris:

![Image of Port Morris Neighborhood](https://github.com/caseywalsh22/HC1-Neighborhood/blob/master/bettergooglemaps.png)
![Image of Port Morris Grid Map](https://github.com/caseywalsh22/HC1-Neighborhood/blob/master/actualfinalgooglemaps.png)


##### Use of GeoJson

Each team member created their own geojson map, with a plot of first (green) and second (yellow) choices for CitiBike station locations. On our individual maps, the region of our neighborhood was marked with a polygon, and subway lines were shown with green/red lines. We then committed our geojsons to Github, and embedded them to our own website pages. 
Below is a merged version of all of our CitiBike proposed locations as one GeoJson map:

***
<script src="https://embed.github.com/view/geojson/IvyBirch/Bronx-Citi-Bikes/master/map (6).geojson	"></script>
***

##### Voronoi Map
![Image of Voronoi Map](https://github.com/YukiYoshimatsu/Bronx-Citi-Bikes/blob/master/combined_vor.png)

Station Legend (Colors)
Orange : Mott Haven
Red : Morrisania
Purple : Port Morris
Grey : Already Existing

***
<script src="https://embed.github.com/view/geojson/YukiYoshimatsu/Bronx-Citi-Bikes/master/combined_geo.geojson"></script>
***





