# User-Geo-Data

Please see the Notebooks folder for the 3 notebooks for the questions - Questions 1-3, Question 4a, and Question 4b.

There are examples of the visualization scheme used in Question 4a in the Maps folder, and one example still in the main notebook (it became too large when combining multiple different maps).

The files in the Maps folder are series of HTML files that can be opened with any standard browser to open a Folium map, and show the visualization of the model built for popularity of the POI. 


The Stats Can approach of user record counts per polygon (census subdivision) is not completed, and is just something I was tinkering with outside the main model. It looks like it could be a good free solution - 

Using Geopandas you can create spatial joins between points, and polygons, and the StatsCan data has polygon subdivisions for the entirety of Canada.

Counting the records should give you number of user records per population for a given area, which can then be compared with the actual population for the area so you aren't just visually representing the population density.


