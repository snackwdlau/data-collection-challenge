# data-collection-challenge
This exercise use Browser, BeautifulSoup, matplotlib and pandas to access, scrape, extract, clean, and visualize data which will then be analyzed to answer questions for the activity.

### Background 
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their `id` and `class` attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

### Instructions 
This activity is broken down into two deliverables, Mars News and Mars Weather. 

#### Part 1: Scrape Titles and Preview Text from Mars News
* Use the `part_1_mars_news.ipynb` file  
* Use [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html) to extract HTML code and data
* Scrape, extract, and store data (titles and preview text) as a list of dictionaries

#### Part 2: Scrape and Analyze Mars Weather Data 
* Use the `part_2_mars_weather.ipynb` file
* Use [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) to extract HTML code and data
    * Use Pandas or Splinter and Beautiful Soup to scrape data
    * Transform data into Pandas DataFrame to be analzyed
* Questions to Analyze:
    1. How many months exist on Mars? 
    2. How many Martian day's worth of data are there? 
    3. Which month, on average, has the lowest temperature? The highest?
    4. Which month, on average, has the lowest atmospheric pressure? The higest? 
    5. How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 
* Export DataFrame into a CSV file 


### References
[The Mars News website](https://static.bc-edx.com/data/web/mars_news/index.html) is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from [NASA's Mars News](https://mars.nasa.gov/) website in November 2022. Images are used according to the [JPL Image Use Policy](https://www.jpl.nasa.gov/jpl-image-use-policy), courtesy NASA/JPL-Caltech.
