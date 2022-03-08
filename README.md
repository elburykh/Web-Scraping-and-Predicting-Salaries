# Web-Scraping-and-Predicting-Salaries

One of my projects during the General Assembly Data Science Immersive course was to scrape job listings from Indeed.com and apply machine learning algorithms to predict salaries for Data Science related roles. This project was completed in January 2022.

## The Goals of the Project

1. Scrape data from a job aggregation tool like Indeed.com.
2. Determine the industry factors that are most important in predicting the salary amounts for these data.

## Scraping job listings from Indeed.com

 - We will be scraping job listings from Indeed.com using BeautifulSoup. Luckily, Indeed.com is a simple text page where we can easily find relevant entries.

 - The source is an Indeed.com page: (http://www.indeed.com/jobs?q=data+scientist+%2420%2C000&l=New+York&start=10").

 - Each job listing is underneath a div tag with a class name of result. We can use BeautifulSoup to extract those.
