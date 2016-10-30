# Gross Number of Maternal Deaths by Country Capital

Hi there! My name is Kara Bressler, and I created this module as my data visualization project for the Capital One Software Engineering Summit. Here I explain how I went about creating this application:

First, in order to scrape data from [World Development Indicators (WDI), Quarterly Update](http://data.worldbank.org/data-catalog/world-development-indicators), I downloaded their comma separated value (CSV) data. After coding a scraper in Java, I cleaned up the data initially provided in Excel to be in a simple [country, magnitude] format, organized by year. Again using a simple Java program, I then matched the individual countries' names with the latitude and longitude of the countries' respective capitals, thus providing a geospatial relation to the statistic of gross number of maternal deaths per country. I cleaned up the collection to be in the [latitude, longitude, magnitude] format specified in the WebGL Globe API. The cleaned up data can be found in population909500.json. 

I then created a GitHub repository, forking in contents from the [WebGL Globe](https://github.com/dataarts/webgl-globe) repostory, in order to create a live application which can be found [here](http://karabeara.github.io). 


