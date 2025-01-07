# COVID-19 Analytics Dashboard using Power BI

This project is a comprehensive data analytics dashboard built using Power BI to provide a real-time, interactive overview of the COVID-19 pandemic’s global impact. It showcases critical insights on confirmed cases, deaths, recoveries, and active cases using advanced data visualization techniques to make the data easy to interpret for users.

## 🔎 Project Overview
The COVID-19 Analytics Dashboard aims to offer visual insights into the spread and impact of COVID-19 worldwide. The dashboard is designed to provide a quick, clear, and interactive summary of pandemic-related data using Power BI’s advanced visuals and interactive features.

It helps users such as health organizations, researchers, policymakers, and the general public to track the evolution of the pandemic, identify trends, and compare key metrics across countries and regions.

## 📊 Key Metrics and KPIs Tracked in the Dashboard
The dashboard tracks the following key performance indicators (KPIs) at a global and regional level:

Total Confirmed Cases  
Total Deaths
Total Recovered Cases
Total Active Cases
Case Fatality Rate (CFR%) – Percentage of deaths compared to confirmed cases
Recovery Rate (%) – Percentage of recovered cases compared to confirmed cases
## 📈 Data Visualizations Included
The dashboard is designed using various Power BI visual elements to ensure that data is presented in an easy-to-understand and engaging format:

1. KPI Cards
The KPI Cards at the top of the dashboard display real-time key metrics:

Total Confirmed Cases: 829M
Total Deaths: 43M
Total Recovered Cases: 388M
Total Active Cases: 397M
Case Fatality Rate (CFR%): 5.24%
Recovery Rate: 47% 
These metrics are dynamically updated based on the selected country/region and time period filters.

2. Line Chart (COVID-19 Trends Over Time)
The line chart shows the trends of confirmed cases, deaths, and recovered cases over time.

This helps users track the progress of the pandemic across different time frames (daily, monthly, or yearly).
Users can observe spikes in cases and milestones in recovery.
3. Pie Charts (Top 5 Countries by CFR% and Recovery Rate)
The two pie charts highlight:

Top 5 Countries with High Case Fatality Rate (CFR%)
Top 5 Countries with High Recovery Rate (%)
This comparison helps users identify regions with better healthcare responses or severe pandemic impacts.

4. Data Table (Country/Region Insights)
The data table provides detailed information for each country/region:

New Cases
New Deaths
New Recovered Cases
Users can sort and filter the data to focus on specific countries or regions for more granular analysis.
5. Bar Chart (Comparison of Cases by Country/Region)
The bar chart compares the confirmed cases, deaths, and recoveries across different countries and regions.

This allows users to see which countries have been most affected by COVID-19.
It provides a side-by-side comparison of different key metrics.
6. Map Visualization (Geographical Spread of COVID-19)
The world map visualization shows the distribution of confirmed cases, deaths, and recoveries across different countries.
Geographic clustering helps users visualize hotspots and areas with high recovery rates.
Users can hover over countries to see specific data points.

## ⚙️ Data Sources and Processing
The dashboard uses trusted and publicly available datasets from sources such as:
World Health Organization (WHO)
Johns Hopkins University 
Our World in Data
Data was cleaned, transformed, and loaded into Power BI using Power Query.

DAX (Data Analysis Expressions) was used to calculate key metrics like:
Case Fatality Rate (CFR%)
Recovery Rate (%)

Daily and cumulative cases

The dashboard is fully interactive, allowing users to filter data by:
Country/Region
Time Period (Daily, Monthly, or Yearly)

## 📌 Key Insights Derived from the Dashboard
Countries with high Case Fatality Rates (CFR%) can be identified for further investigation into healthcare infrastructure and government responses.
Regions with high recovery rates show effective management and healthcare protocols.
The time series analysis helps observe the progression of the pandemic over time, identifying critical spikes and declines in cases.
Geographical maps reveal the distribution and concentration of cases worldwide.
Users can easily track new cases, deaths, and recoveries on a daily, monthly, or yearly basis.


## 📂 GitHub Repository Structure
Your GitHub repository could be structured as follows:

bash
Copy code
COVID-19-Analytics-Dashboard/
│
├── README.md                 # Project Description
├── Covid_19_Analytics.pbix   # Power BI Dashboard File
├── Dataset/                  # Raw and Processed Data Files
└── Images/                   # Screenshots of the Dashboard

## 💻 How to Use the Dashboard
Download the .pbix file from this repository.
Open it using Power BI Desktop.
Explore the dashboard by interacting with the various filters, charts, and maps.
Use the country filter to focus on specific regions.
Change the time range filter to observe the trends over time.

## 🌟 Key Learning Outcomes from this Project
By working on this project, I have gained:
Hands-on experience with Power BI’s visualization tools.
Proficiency in DAX calculations and data modeling.
Skills in building interactive dashboards for data analytics projects.
Experience in working with real-world data and deriving actionable insights.
