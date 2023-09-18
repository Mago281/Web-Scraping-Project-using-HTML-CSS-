# Module-_11_Challenge

This challenge demonstrates the usage of BeautifulSoup and Splinter with Selenium to collect data from websites without an API.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Part 1: Scrape Titles and Preview Text from Mars News
-----------------------------------------------------

In the Jupyter notebook part_1_mars_news, automated browsing, with Splinter, was used to visit the Mars news site, and the HTML code was extracted using Beautiful Soup.

The titles and preview text of the news articles were scraped and extracted in accordance with the Part 1 Requirements.

The scraped information was stored in the specified Python data structure, in a list of dictionaries.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Part 2: Scrape and Analyse Mars Weather Data
--------------------------------------------

In the Jupyter notebook part_2_mars_weather, the HTML table was extracted into a Pandas DataFrame using either Pandas or Splinter and Beautiful Soup.  The scraped data was analysed to answer the following questions: 

  •	How many months exist on Mars?
  
      o	12 months
      
    
  •	How many Martian days of data are there?
  
      o	1,867 days

      
The data was analysed further to answer the following questions, and a data visualisation was created to support each answer:

  •	Which months, on average, have the lowest and the highest temperatures on Mars?
  
      o	Coldest:		Month 3
      
      o	Warmest:	Month 8
      

  •	Which months, on average, have the lowest and the highest atmospheric pressures on Mars?
  
      o	Highest:		Month 9
      
      o	Lowest:		Month 6


  •	About how many terrestrial (earth) days exist in a Martian year?  (A visual estimate within 25% was made.) 
  
      o	About 675 terrestrial (earth) days exist in a Martian year
      

The DataFrame was exported into a CSV file:		mars_weather.csv


