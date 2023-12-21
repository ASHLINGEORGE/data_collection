# Project Overview
This project involves scraping Mars news articles and analyzing Mars weather data. Below are the details of the project and how it was executed.

## Part 1: Scrape Titles and Preview Text from Mars News
Automated browsing was implemented using the Splinter library to visit the Mars news site. This allowed us to navigate the website programmatically.

The HTML code of the website was extracted using Beautiful Soup. Beautiful Soup is a Python library that provides tools to scrape and parse HTML content.

We successfully scraped and extracted titles and preview text of the Mars news articles. This information was collected from the website for further analysis.

The scraped data was organized and stored in a Python data structure, specifically a list of dictionaries. Each dictionary represented a news article and contained fields for the title and preview text.

## Part 2: Scrape and Analyze Mars Weather Data
The HTML table containing Mars weather data was scraped using either Pandas or Splinter and Beautiful Soup, depending on the preference and convenience of the developer. Pandas is a powerful library for data manipulation and analysis, while Splinter and Beautiful Soup provide a more versatile way to scrape data.

A DataFrame was created to store the scraped weather data with correct column headings and data types. This ensured that the data was well-structured and ready for analysis.

Data analysis was performed on the scraped weather data, answering important questions such as the number of months on Mars and the amount of Martian days' worth of data available.

## Data Visualization
Data visualization was employed to provide visual insights and answers to specific questions. The following visualizations were created:

Visualization 1: A bar chart showing the average temperature for each month on Mars, allowing us to identify the months with the lowest and highest temperatures.

Visualization 2: A bar chart displaying the average atmospheric pressure for each month on Mars, helping us identify the months with the lowest and highest atmospheric pressure.
A visual estimate, within a 25% margin, of the number of terrestrial days that exist in a Martian year. This estimate was based on the available data.

## Conclusion
This Mars Data Scraping and Analysis Project successfully scraped Mars news articles and analyzed Mars weather data. The project provided valuable insights into the Martian climate and the availability of news articles related to Mars.

The visualizations created from the data enhanced our understanding of Mars' climate patterns. The project serves as a useful resource for those interested in Mars and its weather conditions.






