# mars_Web-Scrapping
Mars Challenge 11 - Web Scrapping

Background
-----------
You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

What You're Creating
This new assignment consists of two technical products. You will submit the following deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.
--------------

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.
--------------

To complete this assignment mars_Web_Scrapping repository has created. This repo contains following files
- .gitignore
- README.md
- part_1_mars_news.ipynb
- part_2_mars_weather.ipynb
- mars_weather_data.csv

Part 1: Scrape Titles and Preview Text from Mars News
------------------------------------------------------
Code for part 1 has done in part_1_mars_news.ipynb which includes the followings:

- Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
- Create a Beautiful Soup object and use it to extract text elements from the website.
- Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures

Part 2: Scrape and Analyze Mars Weather Data
---------------------------------------------
Code for part 2 has done in part_2_mars_weather.ipynb file which includes the followings:

- Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html
- Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
- Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. 
- Analyze your dataset by using Pandas functions


mars_weather_data.csv
----------------------
This file contains the weather data of mars_weather_data_df




