# Food Deserts in Pasadena, California

## Introduction and Business Problem

The city of Pasadena, California is approximately 10 miles
northeast of downtown Los Angeles, in the foothills of the
San Gabriel mountains. It has an estimated population of
141,000 people [Wikipedia](https://en.wikipedia.org/wiki/Pasadena,_California).

Pasadena has many, many restaurants. However, there are large parts 
of the city that do not have grocery stores.  This report 
looks to describe those regions with an eye toward recommending
locations for new grocery stores.

In other words, we are looking for "food deserts".

A food desert is "... an area that has limited access
to affordable and nutritious food, in contrast with an
area with higher access to supermarkets or vegetable shops
with fresh foods". [Wikipedia](https://en.wikipedia.org/wiki/Food_desert)

This project is aimed at entrepreneurs interested in opening a new retail
outlet.  It is also aimed at Pasadena city planners and related government officials
who may be in a place to incentivize these kinds of establishments. 

## Data

The data for this project comes from several sources:

1. Wikipedia, for the definition of a food desert.
2. The Python folium library, which provides maps of Pasadena.
3. The Python nominatum library, which is used
   to look up longitude and latitude of various locations.
4. The City of Pasadena's 
   [Open Data web site](https://data.cityofpasadena.net)
   which has GEOJson files that precisely define the city's 
   borders.
5. [The Foursquare venues database](https://developer.foursquare.com/docs/api-reference/venues/search/),
   which was used to find the list of existing grocery
   stores, and their locations.
6. Some original research, in the form of site visits. 