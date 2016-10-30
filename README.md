# Gross Number of Maternal Deaths by Country Capital

A one paragraph explanation of what you built and what you used to build it (language, frameworks, libraries, etc..) 


Hi there! This is a [WebGL Globe](https://github.com/dataarts/webgl-globe) module - here is a [demo](http://karabeara.github.io) of my project!

I created this module as me data visualization project for the Capital One Software Engineering Summit. Here I explain how I went about creating this application:

First, in order to scrape data from [World Development Indicators (WDI), Quarterly Update](http://data.worldbank.org/data-catalog/world-development-indicators), I downloaded their comma separated value (CSV) data. After coding a scraper in Java, I cleaned up the collection to be in the [latitude, longitude, magnitude] format specified in the WebGL Globe API. The cleaned up data can be found in 

I then matched the individual countries' names with the latitude and longitude of the countries capital, thus providing a geospatial relation to the statistic of gross number of maternal deaths per country. 

