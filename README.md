# Population within a Walking Distance from Shopping Centres
<i>Exercise 3 of Automating GIS Process 2023</i> 

## Overview
The goal of this project is to find the number of people living within a walking distance from seven major shopping centres in Helsinki, Finland.

<!---
<div align="center">
  <img src="images/front_1.png" alt="classification" width="700">
  <img src="images/front_2.png" alt="dominace_areas" width="700">
</div>
--->

The project is composed of the following steps:
1. geocode the addresses of shopping centres into coordinates using the Nominatim server
2. create a buffer of 1.5 km around each coordinate
3. request population data from the web feature service (WFS) endpoint of Helsinki Region Environmental Services HSY and spatial join with buffer data
4. calculate the sum of the population in each buffer

## Software and Libaries
- Python 3.9
- NumPy
- Pandas
- Geopandas
- PyProj
- Jupyter Notebook

## Related Projects
