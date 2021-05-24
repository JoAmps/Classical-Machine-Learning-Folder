# The aim is to make a program to find the longitude and latitude and distance between polish cities per day, and the distance travelled from first day to last day, and finally to find the optimal(shortest) route between cities for a given day.
### The program was written in python, where based on the input data from the spreadsheet, it will retrieve dates, routes in Poland, kilometers traveled. The program first calculates the kilometers traveled on a given day, from the first address to the last one. As the results you get a sheet with the number of kilometers from points a to b, from b to c, from c to d etc. for each day. Then, in the next line, an increasing value, the total number of kilometers traveled from the first day to the last day.  At the end, the order of the cities should be specified (shortest route).
### Libraries and tools used:
#### Pandas (for data manipulation)
#### numpy (for numerical computations)
#### Geopy and opencage (for latitude and longitude calculation)
#### Mlrose (travelling salesman using genetic algorithm for shortest route calculation)
#### OSRM (open-source routing for calculating distance and time between original city and the rest)
