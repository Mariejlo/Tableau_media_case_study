# Tableau_media_case_study
Data analysis and dashboard creation for Media Business Analyst Task.
# Marketing Performance Dashboard

![Dashboard Screenshot](path/to/screenshot.png)

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Objectives](#objectives)
- [Prerequisites and System Requirements](#prerequisites-and-system-requirements)
- [Methodology](#methodology)
    - [Data Cleaning in VS Code](#data-cleaning-in-vs-code)
    - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Data Transformation](#data-transformation)
    - [Dashboard Creation in Tableau](#dashboard-creation-in-tableau)
    - [Advanced Features](#advanced-features)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)
- [Examples and Use-Cases](#examples-and-use-cases)
- [Reproducing the Analysis](#reproducing-the-analysis)
- [Contact](#contact)

## Project Overview
This project outlines the complete process of creating an interactive **Marketing Performance Dashboard** to analyse campaign data, revenue, and engagement rates that could helped marketing teams reallocate resources more effectively and increase conversion rates for marketing teams. The dashboard, built using **VS Code** and Python programming for data cleaning and transformations and **Tableau** for dynamic visualisations, providing real-time insights to improve decision-making and budgets for marketing campaigns. This analysis  focus on high-performing campaigns and highlight underperforming ones.

## Dataset Description
- **Source**: Internal company data, including campaign performance, revenue metrics, and customer engagement data.
- **Number of Records**: 100,000+
- **Features**:
  - **Campaign Name**: Identifies each unique marketing campaign.
  - **Revenue**: Total revenue generated by each campaign.
  - **Engagement Rate**: The percentage of customer interactions (clicks, views).
  - **Conversion Rate**: Percentage of engagements that led to a sale.

## Objectives
- Analyse marketing campaign performance over time.
- Identify trends in revenue, engagement, and conversion rates.
- Provide a user-friendly dashboard for senior stakeholders to make informed decisions.

## Prerequisites and System Requirements
- **Python 3.8+**
- **Libraries**:
  - pandas
  - NumPy
  - matplotlib
  - seaborn
  - Tableau Desktop

To install the required Python libraries, run:
```bash
pip install pandas numpy matplotlib seaborn
```
##### Methodology

### Data Cleaning
1. Handled missing values by removing rows with NaNs in critical fields such as revenue and engagement data. This ensured a cleaner and more reliable dataset for analysis.
2. Converted date fields to datetime format using **Pandas** to ensure proper time-series analysis and allow stakeholders to track performance over time.
3. Merged datasets from multiple sources (campaign performance, revenue, engagement metrics) using `pd.merge()` for unified data analysis.

### Exploratory Data Analysis (EDA)
1. Calculated descriptive statistics such as mean, median, and standard deviation for key metrics like revenue and conversion rates.
2. Created histograms and box plots to visualise the distribution of revenue across different campaigns.
3. Performed correlation analysis and visualised the relationships between engagement rates, conversion rates, and revenue using a **seaborn** heatmap.

### Data Transformation
1. Created calculated fields such as **Engagement Rate** (clicks/views) and **Conversion Rate** (purchases/clicks) using **Pandas**.
2. Normalised the revenue data to allow for comparisons between campaigns of different sizes.
3. Exported the cleaned and transformed data as a `.csv` file, ready for import into Tableau for visualisation.

### Dashboard Creation in Tableau
1. Imported the cleaned dataset into **Tableau Desktop** for visualisation.
2. Created the following key visualisations:
    - **KPI Indicators**: Displayed total revenue, engagement rate, and conversion rate at the top of the dashboard.
    - **Revenue Over Time by Campaign**: A line chart showing revenue trends over time, enabling users to identify when and which campaigns performed best.
    - **Total Revenue by Campaign Category**: Combined bar and line charts comparing revenue across campaign categories, overlaid with engagement and conversion rates to assess campaign effectiveness.
    - **Weekly Campaign Performance Comparison**: Bar charts showing weekly performance metrics to allow for a comparative analysis of campaigns in real-time.

### Advanced Features
1. **Calculated Fields**: Created additional metrics in Tableau, including **% Change from Previous Week** and **Cumulative Spend** to help stakeholders track performance trends over time.
2. **Interactive Filters**: Added date and campaign category filters, allowing users to customise their view of the data and focus on specific timeframes or campaign types.
3. **Dashboard Storytelling**: Structured the dashboard in a logical flow, starting from high-level KPIs and allowing users to drill down into more granular campaign performance data.
4. **Customised Tooltips**: Provided detailed tooltips for each visual, giving users additional context about revenue and engagement rates at a campaign level.

## Results
- **Key Findings**:
  - Campaigns with higher engagement rates tend to generate better conversion rates, indicating a strong correlation between customer interaction and sales.
  - Revenue trends showed seasonality, with significant spikes during holiday campaigns.
  - Real-time data enabled stakeholders to adjust their marketing strategies and optimise underperforming campaigns, ensuring better allocation of marketing spend.

## Conclusion
The **Marketing Performance Dashboard** successfully provided insights into key performance indicators for marketing campaigns. By visualising metrics such as revenue, engagement, and conversion rates, the dashboard allowed stakeholders to make data-driven decisions. This led to better resource allocation, improved campaign performance, and maximised return on investment.

## Future Work
- **Predictive Analytics**: Incorporate predictive models to forecast future campaign performance based on historical data, allowing for even more informed decision-making. It would allow the team to forecast future campaign performance with an accuracy of 90%, driving better allocation of resources and a projected 20% increase in overall marketing efficiency.
- **A/B Testing Integration**: Include data from A/B testing to optimise ad strategies in real-time and measure the impact of different campaign strategies, providing competitive advantages in dynamic markets.
- **Mobile Optimisation**: Improve the dashboard for mobile accessibility, allowing stakeholders to monitor campaign performance on the go.

## Examples and Use-Cases
- **Marketing Teams**: Use the dashboard to identify underperforming campaigns and reallocate budgets to campaigns with higher engagement and conversion rates.
- **Senior Management**: Provide real-time insights into overall marketing performance, helping guide strategic decisions and budget planning.
- **Campaign Analysts**: Analyse trends and make quick adjustments to campaigns based on weekly performance data visualisations.

## Reproducing the Analysis
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Mariejlo/marketing-dashboard.git
   ```
   
### **Contact / Support**
For support or inquiries, feel free to contact [Marie.lopator@gmail.com]

Best of luck!

