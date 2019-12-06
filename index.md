

 # Citi Bike Project                                           
 ### The Bronx
 #### Ivy Birchall, Yusef Wray, Casey Walsh

Each of these individual sites repersents a group members work on a specific neighborhood in the Bronx, explaining what CitiBike stations they reccomend and why they reccomend them. Each team member conducted their own individual research on their own neighborhood, and used GeoJson to create a map with color coded markers for their first and second choices for CitiBike loctions within a 1,000 square foot grid. Together, they cover the South Bronx neighborhoods and what CitiBike expansion may look like. 

 [Mott Haven](https://ivybirch.github.io/Honors-Bike-Website-Test/)
 ######Created by Ivy Birchall

 [Morrisania](https://yukiyoshimatsu.github.io/morrisania_neighborhood)
 ######Created by Yusef Wray

 [Port Morris](http://caseywalsh22.github.io/HC1-Neighborhood)
 
 ###### Created by Casey Walsh
 * Port Morris is an industrial neighborhood in the South Bronx
 * Most CitiBike locations were selected based on proximity to schools, stores, bus stops, event venues, and major intersections
 * The addition of CitiBike's to this neighborhood would improve trasnit, because there are very few bus stops and no subway stops
 ###### Demographics and Statistics of Port Morris:
 * It has a population of 3525, and is 52.9% female
 * 24.4% of the population is between the ages of 25 and 34
 * 72.3% of the neighborhood is Hispanic and Lantinx Americans
 * Port Morris is 474 acres large
 ###### Impact of CitiBikes
 * CitiBikes in Port Morris would make transportation across the neighborhoo safer and faster
 * The neighborhood is surrounded by many major roads and bridges, so CitiBikes would be a safer form of trasnportation than walking
 * There is very little public trasnport in the neighborhood, so CitiBikes will make travelling in the nighborhood faster, and make it easier to reach mass trasnit to travel outside the neighborhood
* There are some locations that CitiBikes will not be useful, such as various unpaved roads and areas that are mostly shipping centers and warehouses
 
 
 ##### Project beginings and goals
 
 Each team member was assigned a individual neighborhood in the South Bronx. Using Google Maps, we each took a screenshot of our neighborhood highlighted. Using Python, we highlighted the area around our neighborhood, and layered a grid over our screenshot. The grid is meant to represent 1,000 square feet. 
 The goal of our project is to propose two locations for CitiBikes every 1,000 square feet, and be able to depict our choices through various methods like folium maps in Python and GeoJson. 
 
 Examples of our highlighted maps and grid maps from Port Morris:
 
 ![Image of Port Morris Neighborhood](https://github.com/caseywalsh22/HC1-Neighborhood/blob/master/bettergooglemaps.png)

![Image of Port Morris Grid Map](https://github.com/caseywalsh22/HC1-Neighborhood/blob/master/actualfinalgooglemaps.png)


##### Use of GeoJson

Each team member created their own individual geojson map, with a plot of a first choice for a CitiBike location (green), and a second choice for a CitiBike location (yellow). 
On our individual maps, the region of our neighborhood was marked with a polygon, and subway lines were shown with green/red lines. We then committed our geojson's to Github, and embeded them to our own website pages. 
Below is a merged version of all of our CitiBike proposed locations as one GeoJson map:

 ***
 <script src="https://embed.github.com/view/geojson/IvyBirch/Bronx-Citi-Bikes/master/combined_geo.geojson"></script>
 ***





