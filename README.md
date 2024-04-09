# Web Scraping Project using HTML and CSS

This project showcases the utilization of BeautifulSoup and Splinter integrated with Selenium to gather data from websites lacking an API.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Part 1: Scrape Titles and Preview Text from Mars News
-----------------------------------------------------

Part 1: Scrape Titles and Preview Text from Mars News
The Jupyter notebook part_1_mars_news employs automated browsing via Splinter to navigate the Mars news site, followed by extraction of HTML code utilizing Beautiful Soup.

Titles and preview texts of news articles were systematically scraped and extracted, adhering to the Part 1 Requirements.

The acquired information was stored in the specified Python data structure, structured as a list of dictionaries.


------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Part 2: Scrape and Analyse Mars Weather Data
--------------------------------------------

Within the Jupyter notebook 'part_2_mars_weather', the HTML table was meticulously extracted into a Pandas DataFrame employing either Pandas or Splinter integrated with Beautiful Soup.

Subsequently, the scraped data was meticulously analyzed to address the following inquiries:

  •	How many months exist on Mars?
  
      o	There are 12 months on Mars.
      
    
  •	How many Martian days of data are there ?
  
      o	There are 1,867 days of Martian data available.

      
Moreover, the data underwent further scrutiny to address the subsequent questions, supplemented with data visualizations for each response:

  •	Which months, on average, have the lowest and the highest temperatures on Mars?
  
      o	Coldest:   Month 3
      
      o	Warmest:   Month 8
      

  •	Which months, on average, have the lowest and the highest atmospheric pressures on Mars?
  
      o	Highest:   Month 9
      
      o	Lowest:    Month 6


  •	About how many terrestrial (earth) days exist in a Martian year?  (A visual estimate within 25% was made.) 
  
      o	Approximately 675 terrestrial (earth) days constitute a Martian year.
      

Lastly, the DataFrame was exported into a CSV filenamed 'mars_weather.csv'.


