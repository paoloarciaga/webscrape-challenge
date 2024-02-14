# Web-Scraping and Data Analysis Challenge

This repo consists of two technical products: 
- Deliverable 1: Scraped titles and previewed text from Mars news articles.
- Deliveable 2: Scraped and analyzed Mars weather data, which exists in a table.

## Mars News
In this notebook, you'll see how I completed the following: 
- Automated browsing (with Splinter) was used to visit the Mars news site, and the HTML code was extracted (with Beautiful Soup). 
- Scraped and extracted the titles and preview text of the news articles 
- The scraped information was stored in the specified Python data structure—specifically, a list of dictionaries.

## Mars Weather Data
In this notebook, you'll see how I completed the following: 
- The HTML table was extracted into a Pandas DataFrame. Either Pandas or Splinter and Beautiful Soup were used to scrape the data. 
- The data was analyzed to answer the following questions: 
  - How many months exist on Mars? 
  - How many Martian days' worth of data are there? 
- The data was analyzed to answer the following questions, and a data visualization was created to support each answer: 
  - Which month, on average, has the lowest temperature? The highest? 
  - Which month, on average, has the lowest atmospheric pressure? The highest? 
  - How many terrestrial days exist in a Martian year? A visual estimate within 25% was made. 
- The DataFrame was exported into a CSV file.

