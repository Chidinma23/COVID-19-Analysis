# COVID-19-Analysis
# Introduction
# Project Name
# Project Objective:
# Data Sourcing: Web Scraping
Data was scrapped from the web and uploaded to Power Query on Excel
# Cleaning Process
After uploading data on Power Query, first row is being applied as header. This data takes a specific number of columns and it keeps increasing whenever new updates are being made; it is a time series and it keeps increasing in columns because it is a wide data. since we simply need the data we have at the moment, we go to source and remove the columns so it doesnt refresh new columns. In the data we have many date columns and each of them contains values; so Province, Country, Longitude and Latitude are selected and upivot other columns is applied. Doing this, it aranges the date and value into two different columns. The value column is renamed to Confirmed. We have two other datasets to add to this query and we would go through this process. To make it easy adn automatic, first we duplicate the first query (confirmed cases), go to source settings and paste the url of the new dataset. By doing this the changes we made to the first query will be applied to the two other quueries. The value column changes according to the dataset. After this, the que
