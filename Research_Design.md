# Research Design

 

## Q1

1. Use QGIS to read the metro data points obtained by EDA
2. Use QRS tools to view the 15-minute walking circle, 15-minute cycling circle, and 15-minute bus circle of each metro station
3. Cutting Shenzhen internal range
4. Export the acquired data as three single attribute value shapefiles and three multiple attribute value shapefiles, so that the relevant area and reachable metro station can be calculated in python based on these two shapefiles.
5. Import data into python
6. Obtain the number of metro stations and the area of each area that can be reached within 15 minutes by bus, 15 minutes by bicycle and 15 minutes by walking among the 74 districts in Shenzhen
7. Consider factors affecting township differences: work areas, government offices, demographics, geography

 

## Q2

1. Divide the place into a starting point and an ending point. The starting points include different office areas (large farms, large factories, large office buildings) and residential areas. The end point is the activity area (including large parks, large supermarkets and key hospitals).
2. Determine the names of the main office areas and activity areas in Shenzhen and search and pull through Baidu api
3. The data on residential areas is mixed and large, and it is difficult to search for a representative classification basis. Therefore, the center point of each township is used for calculation, and the housing prices in different administrative townships are divided and compared.
4. According to the latitude and longitude of the starting point and ending point, the route planning data is pulled during the peak weekday local time.
5. Extract the route to travel by metro
6. Calculate the route status: can be reached by metro, unreachable route, walking reachable, etc.
7. Calculate the average time from each starting point to all the ending points and the average time by metro, etc.
8. Calculate the shortest time, median time, etc.
9. Regression analysis, etc. through the obtained results...