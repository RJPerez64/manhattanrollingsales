# March 2023 - February 2024 Manhattan Property Sales

Understanding the makeup of a borough's property sales can be important when deciding which neighborhoods to invest into and which ones to avoid. Additionally, determining what property type does well in those neighborhoods can make all of the difference.

I reviewed Manhattan's property sales over a 12-month period (March 2023 to Febrauary 2024) in various formats (Google Colab with Python, Microsoft Excel, and Tableau). I found that initial dataset on New York City's Department of Finance website (https://www.nyc.gov/site/finance/property/property-rolling-sales-data.page).

I have posted various Excel files, including the original from their website and altered versions from my own data cleaning directly in the file and through Python in Google Colab.

Excel: For the main Excel document, I did data cleaning in Cleaning Data, got the Median Longitude and Latitude of each neighborhood in Longitude and Latitude (which would be used in
       one of the Tableau dashboard maps), pivot tables investigating the sales by neighborhood and average sale price by property type by quarter in Pivot Table, insights about
       the data (highest sale count, which property type did best, the stability of each property type during this period, the top 10 properties by sale price and price per square foot)
       in Analysis of Pivot Tables & Data, found the youngest and oldest properties and compared their qualities in Youngest and Oldest Properties, and then looking at the number of
       sales by month and quarter in Quarter and Monthly Sales. There are other Excel files that showcase other things of interest.

Colab: This document (https://colab.research.google.com/drive/1_SrKaB0mPCABvftlnY63A-ajjoDIUaDl#scrollTo=WzPqnC66_V6n) is where I tried my hand at using Python to do a similar analysis.
       I did similar data cleaning and made some additional analysis, such as determining the most sought after building class categories in each neighborhood during this time. Additionally,
       I did linear regression using some of the features in this data, including the ones that I made (has elevator, has commercial, has residential).

Tableau: I made a dashboard (https://public.tableau.com/app/profile/rafael.perez4912/viz/ManhattanRollingSalesAnalysis_17120823597350/OriginalDashboard) out of this data, where I made sure
         to discuss my findings and showcase this information in a digestable way.
