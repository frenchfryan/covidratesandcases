# covidratesandcases
# GEOGRAPHY 458: Lab 3 by Ryan Danao

**Title:**

The title for Lab 3 would be **Web Map Application**. 

**Introduction and Data Sources:**
For this lab, we are tasked to construct thematic maps that represent cases and rates of COVID-19 in the United States. For the first map that will represent the rates, the data was collected from the [2018 ACS 5 year estimates](https://data.census.gov/cedsci/table?g=0100000US%24050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true) while the data for the second map was collected from [New York Times](https://github.com/jakobzhao/geog458/tree/master/labs/lab03). Lastly, the county boundary shapefile was collected from the [U.S. Census Bereau](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html). 

**Map 1: COVID-19 Rates Choropleth Map**
![map 1](/img/Map1.jpg)
Link: http://127.0.0.1:5500/map1.html

**Description of Map and Primary Uses:**
The thematic map for map 1 will be portrayed in the form of a choropleth map. More specifically, this map will represent the COVID-19 rates in each county across the U.S. Furthermore, the number of deaths per county will also be shown along with the rates if you hover your mouse over a county. Lastly, the legend will show the source of the data as well as the range of rates each color represents, depending on how high or low the COVID-19 rate is.

**Map 2: COVID-19 Cases Proportional Symbols Map**
![map 2](/img/Map2.jpg)
Link: http://127.0.0.1:5500/map2.html

**Description of Map and Primary Uses:**
The thematic map for map 2 will be portrayed in the form of a proportional symbols map. More specifically, this map will represent the COVID-19 cases in each county across the U.S. Furthermore, the number of deaths per county will also be shown along with the cases if you click any of the circles on the map. Lastly, the legend will show the source of the data as well as the number of cases each color and shape of the circle represents, depending on how high or low the COVID-19 case is.

**Acknowledgement:**
 The data has bee processed by Steven Bao, and the web application example and lab instructions of 
[Lab 3: Web Map Application](https://github.com/jakobzhao/geog458/tree/master/labs/lab03) were made by Professor Bo Zhao. Another resource that was used in implementing this lab was [Lab 4: Interactive Web Mapping](https://github.com/jakobzhao/geog495/tree/main/labs/lab04), which was also made by Professor Bo Zhao.

**Libraries in Use:**
 JavaScript and Map Box API
