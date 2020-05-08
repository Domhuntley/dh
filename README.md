The Battle of Neighborhoods | Business Proposal | Introduction¶

Introduction:

My propsosal for this Project is directed at  helping people explore better facilities around their neighbourhood. This proposal is designed to help people make rational and beneficial decisions, based on clustering and segmenting of the neighbourhoods in Scarborough, Toranto.
There and many people migrating to various states of Canada, more and more ever year. housing prices and reputable schools are a necessity for these migrates. This project is for those looking for a new start, and a better way of life. For ease of access to Cafes, Schools, Super markets, medical shops, grocery shops, a mall, theatre, hospital, and even like minded people.
The aim of this Project is to create an analysis for people migrating to Scarborough, to search the best areas for settlement, as a comparative analysis between neighborhoods. The features include housing price and better schools according to ratings, crime rates of that particular area, road connectivity, weather conditions, emergency services, water resources, both freash and waste water, and excrement conveyed in sewers, as well as recreational facilities. I believe this an analysis will be very beneficial to those mentioned above, and for finding all facilities mentioned above. 

Solving the problem:

The purpose of this project is to find the best possible neighbourhoods for living in, in respect to the settling party’s needs. Connectivity to the airport, bus stand, city centre, markets and a multitude of other facilities nearby.
1.Sorted list of housing prices in ascending or descending order
 2.Sorted list of schools locations, fees, ratings and reviews

The Location:

Scarborough is a popular destination for new immigrants in Canada to reside. As a result, it is one of the most diverse and multicultural areas in the Greater Toronto Area, though immigration has become more prominent over the past few years, with more governments seeking more restrictions on immigrants and refugees, the immigration into Canada has projected a steady increase each year.
Foursquare API:
In this project I will use Four-square API as the prime source for gathering the data needed, as it has a database of millions of places, especially API, as it provides location search, location sharing and details about a business.

Work Flow:

Using credentials of Foursquare API features, I will attempt to find near-by neighborhoods that possess the needed resources for these individuals. Due to http request limitations, the number of places per neighborhood parameter  will be set to 100, and the radius parameter would be set to 500.

Clustering:

To compare two cities and their similarities, I have chosen to explore neighbourhoods, segment them, and group them into clusters to find similar neighborhoods to New York and Toronto. To be able to do that, I will need data from an unsupervised machine learning: k-means clustering algorithm.

Libraries Used in Developement:
Pandas: For creating and manipulating dataframes.
Folium: Python visualization library would be used to visualize the neighborhoods cluster distribution of using interactive leaflet map.
Scikit Learn: For importing k-means clustering.
JSON: Library to handle JSON files.
XML: To separate data from presentation and XML stores data in plain text format.
Geocoder: To retrieve Location Data.
Beautiful Soup and Requests: To scrap and library to handle http requests.
Matplotlib: Python Plotting Module.
