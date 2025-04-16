# Website-Analytics-Dashboard

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📊 Overview
This Power BI report is built using the Matomo API for marketing websites. It visualizes important KPIs, their performance compared to previous time periods, and KPI trends with time. 

## 🗂 Dataset
- **Source:** Matomo cloud via API, Azure SQL Server
- **Description:** The dataset contains information about accounts, visits, pageviews, channel types, entry pages and device types amongst other KPIs. The data is extracted through a Python script via the Matomo API and stored in an Azure database before connecting to the Power BI report. 

## 📈 Features & Visuals
The dashboard offers the top KPIs in the first half of the report and continues to answer questions like: Which channel type brings in the most traffic? Which entry pages are the most popular? Through such insights, the business can make better decisions about where to make investments and how to better align their effors for maximum traffic and ultimately, conversions.

1. **KPI Line chart:**
   This line chart displays the KPI that is selected from the list of KPIs below. For example, if the user clicks on actions per visit, it will display the trend line for actions per visit in the line chart.
   The percentage comparison that appears as a subtitle was crafted using DAX and HTML to achieve a colour coded and icon based percentage value for each KPI.
   The KPIs used are:
   - Visits 
   - Average visit duration
   - Visits that bounced (left the website after one page)
   - Actions per visit
   - Pageviews
   - Unique Page views
   - Total seraches on your website

3. **Channel Type:**
   - % of total visits
   - Visits
   - Actions

4. **Entry Pages:**
   - Entrances
   - Bounces
   - Bounce Rate
   - Avg load Time (secs)

 ## 🖼 Dashboard Preview
 ![image](https://github.com/user-attachments/assets/1a212705-8511-432d-ba12-f1d8e89c2f79)
