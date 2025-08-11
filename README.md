# CIS3120_Project-2_Web-Scraping-APIs
This project showcases how to combine web scraping and API integration in Python to create richer datasets. I start by scraping a structured HTML table from the web into a Pandas DataFrame(DF1). One of the columns from this dataset is then used as an input parameter for an external API. The API call return informations for every query, which are stored in a second DataFrame(DF2). Finally, I merge DF1 and DF2 horizonally into third DataFrame(DF3), creating a combined dataset that enriches the scraped data with live, API-powered information.


This approach demonstrates:
  - Web Scraping using pandas
  - API integrating with requests
  - Data cleaning and structuring in Pandas
  - Merging datasets to create richer_insights
