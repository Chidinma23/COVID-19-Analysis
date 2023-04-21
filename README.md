# COVID-19-Analysis
![Screenshot 2023-04-21 154036](https://user-images.githubusercontent.com/115046602/233679926-ec78e018-659e-4164-8c5f-552eb4fb7e16.png)
![Screenshot 2023-04-21 154122](https://user-images.githubusercontent.com/115046602/233679457-00668e6d-ab8b-4499-98e9-8057520f5885.png)
![Screenshot 2023-04-21 155410](https://user-images.githubusercontent.com/115046602/233679504-eb1bbac4-3eb2-4ccc-bae1-ff59761a3cff.png)

# Introduction: 
Coronavirus disease 2019 (COVID-19) is a contagious disease caused by a virus, the severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2). COVID‑19 transmits when infectious particles are breathed in or come into contact with the eyes, nose, or mouth. The risk is highest when people are in close proximity, but small airborne particles containing the virus can remain suspended in the air and travel over longer distances, particularly indoors. The disease quickly spread worldwide, resulting in the COVID-19 pandemic.

# Project Name: COVID-19 GLOBAL ANALYSIS
COVID-19 GLOBAL ANALYSIS AND DASHBOARD

# Project Objective:
The purpose of this analysis is to bring to the consciousness of the stakeholders how bad the pandemic has been. Now to Stakeholders, who are they? Our stakeholders in this case study is the general topic. Anyone interested in understanding the spread of the global pandemic. This project was made in the fulfilment of #30daysoflearning data analysis by Microsoft.

# Data Sourcing: Web Scraping
Data was scrapped from the web and uploaded to Power Query on Excel. This data is from January 2020 to June 2022

# Cleaning Process
After uploading data on Power Query, first row is being applied as header. This data takes a specific number of columns and it keeps increasing whenever new updates are being made; it is a time series and it keeps increasing in columns because it is a wide data. since we simply need the data we have at the moment, we go to source and remove the columns so it doesnt refresh new columns. 
In the data we have many date columns and each of them contains values; so Province, Country, Longitude and Latitude are selected and upivot other columns is applied. Doing this, it aranges the date and value into two different columns. The value column is renamed to Confirmed. We have two other datasets to add to this query and we would go through this process. 
To make it easy adn automatic, first we duplicate the first query (confirmed cases), go to source settings and paste the url of the new dataset. By doing this the changes we made to the first query will be applied to the two other quueries. 
The value column changes according to the dataset. After this, the queries are merged and the new query is renamed consolidated data. Expand the death and recovered data to show just the value. Changed each columns to their required datatypes.
Before we close and apply, all changed type were deleted in the other queries this is beause we already have a consolidated data and we have removed the query or command that keeps this query active in terms of updating it on Excel. 

# Excel
After uploading data to Excel, the columns were checked and changed to its right format. Year, Month and Day were extracted separately from date. Next, we summarized with Pivot Table to begin analysis:
1. Total Confirmed cases
2. Total Death Cases
3. Rate of Death to confirmed cases
4. Top 10 Counries with confirmed cases
5. Bottom 10 Countries with confirmed cases
6. Rate of Death to Confirmed cases
7. Sum of Confirmed Cases
8. Sum of Death cases
9. Confirmed cases by year
10. Culmulative Yearly Confirmed Cases of COVID19 since 2020
11. Cummulative Monthly Confirmed Cases of COVID19 since 2020
12. Sum of Confrimed cases by year and month
13. Sum of Recovered Cases

# Conclusion
The folllowing insights were made:
1. United States have the highest prevalence (confirmed cases) of Covid19
2. North Korea have the lowest prevalence (confirmed cases) of Covid19
3. Rate of Death to confirmed cases is 1.50%
The sum of recovered cases  23,227,207,571 is more than the deaths of  3,723,034,613 from the month of January 2020 to June 2022. 
