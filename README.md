# South Florida City Analysis

## Problem and the background

South Florida (colloquially and locally known as SoFlo) is a geographic and cultural region that generally comprises Florida's southernmost counties, and is the fourth most populous (6.69 million) urban agglomeration in the United States. It is one of Florida's three most common "directional" regions, the others being Central Florida and North Florida. It includes the populous Miami metropolitan area, the Everglades, the Florida Keys, and other localities. South Florida is the only part of the continental United States with a tropical climate.

I want to start a business in South Florida and need to be associated or get in partnership with the companies in various cities. I am from Boca Raton, and my idea is to start with Boca and then expand to other cities in South Florida. The target businesses are usually B2C, and my product will help these businesses get more customers for them.

The idea behind this project is to find out the most common venues within Boca Raton and then find the cities that are alike with Boca. The algorithm to be used is k-means clustering so I can find out the cities that share common characteristics with Boca. As the first step, I need to find out the top venue categories and top venues in Boca Raton and to expand my market; I need to find out the cities that are like Boca Raton.

## Data and the usage

- Data about the list of South Florida Cities obtained from Wikipedia: This is used to get the list of cities for consideration
- Coordinates of these cities from my Github repo obtained from google maps: This is used to drop pins at these cities and search venues around
- Coordinates of Boca Raton to find out the venues, obtained from google maps: This is used to search venues around Boca
- Foursquare API to fetch venues and popular venues: To get the list of venue categories and the venue names basing the lat long values
