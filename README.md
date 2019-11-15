# Coursera_Capstone
This is my capstone course for the IBM certification

# Description: Food Desert’s

A food desert is an area that has limited access to affordable and nutritious food, in contrast with an area with higher access to supermarkets or vegetable shops with fresh foods, which is called a food oasis. The designation considers the type and quality of food available to the population, in addition to the accessibility of the food through the size and proximity of the food stores.

In 2010, the United States Department of Agriculture (USDA) reported that 23.5 million Americans live in "food deserts", meaning that they live more than one mile from a supermarket in urban or suburban areas, and more than 10 miles from a supermarket in rural areas.

Food deserts tend to be more populated by low-income residents, who are not as attractive a market for large supermarkets, and have reduced mobility. Food deserts lack suppliers of fresh protein sources such as poultry, fish and meat, along with fresh fruit and vegetables, instead, relying on convenience stores, which provide processed and sugar- and fat-laden foods, which are known contributors to the United States' obesity epidemic.[1]

In this capstone project, I will focus my study of food deserts within the various, and unique neighborhoods that make up the city of Madison, Wisconsin (a place I call home!). Recently, a proposed project on the cities’ south side caused a lot of community concern when the project asserted to demolishing a Pick-n-Save supermarket to build a new health care clinic in its place, leaving this community without access to fresh produce within the guidelines posted above. While nothing to date has taken place with the development project, this also does raise the interesting question of not only determining current desert areas, but those also at risk of becoming a food desert. 

# Data Sources:
My analysis will focus on two main datasets:

    1)	The city of Madison provides a repository of different datasets via their Open Data Portal located here: https://data-cityofmadison.opendata.arcgis.com/  This repository contains various datasets via the ARCGIS open data module. I will use the 
    Neighborhood Plans data set to collect information about the different neighborhoods within the Madison area. 
    
    2)	Using the Foursquare location data API, we will focus our queries on the venue name “Grocery Store”, using the neighborhood data as 
    a reference point. This will provide location data of the specified venue, which can then be plotted on the map (using a 1 mile radius) 
    and analyzed with accordance to the parameters defined above. 
    
By combining these two datasets, it should provide an easy and intuitive visualization to identify areas of the cities and their associated neighborhoods of where food deserts exist within the city.  I also expect to identify areas of risk for which a food desert could occur based on the density of fill from overlapping radii of influences by grocery store. 
