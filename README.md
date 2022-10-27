# USFertility
Circle map of US fertility rates in 2019

#### This map illustrates the United States ferility rates as of 2019. Fertility rates are reported as births per women ages 15-44. The data was retrieved from the Center for Disease Control and Prevention](https://www.cdc.gov/nchs/hus/topics/births.htm#explore-data). Fertility rates are symbolized using graduated circles, where larger circles indicate higher fertility rates, and smaller circles indicate lower fertility rates. 

#### I created this map in HTML, JavaScript and CSS, utilizing Leaflet and JQuery libraries in Atom. To create the map, leaflet functions were very helpful, including L.map to create my map, L.tileLayer to add my basemap and L.geoJSON to retrieve my geoJSON files. I created my geoJSON file using a .CSV file with latitude and longitude readings for the center of each state, with fertiity data attached. To increase interaction with my map, I used 'mouseover' functions with 'varTipInfo' to indicate the exact fertility rate of each state. 



