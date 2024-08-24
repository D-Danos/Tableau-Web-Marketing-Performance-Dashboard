# Tableau Web Marketing Performance Dashboard

**Tools:** Tableau

## Overview

This repository contains the **Tableau Web Marketing Performance Dashboard**. The dashboard is designed to provide a comprehensive overview of a website's marketing performance, showcasing key metrics and visualizations to help analyze traffic sources, user behavior, and engagement.

### Goal

The main goal of this dashboard is to help businesses understand their web traffic data effectively. It is a powerful tool for tracking user sessions, page load times, bounce rates, and other critical metrics. By visualizing web marketing data in an interactive format, users can make data-driven decisions to enhance their online presence and user engagement.

### Dashboard Key Features

- Web Traffic Overview
- Sessions and Bounces Analysis by Month and Device
- Top Unique Pageviews and Country Insights

## How to Use the Dashboard

1. **Explore the Dashboard Online**:
   - Access the dashboard directly via this [Tableau Public link](https://public.tableau.com/app/profile/danos.dimitris/viz/WebMarketingDashboard_17243592790950/Dashboard?publish=yes).
   - Utilize the interactive filters to explore different aspects of the web marketing data.
   - Hover over data points to see detailed information and tooltips.

2. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/web-marketing-performance-dashboard.git
    ```

## Steps

1. **Imported Data**:
   - Imported the provided `.csv` file into Tableau.

2. **Data Preparation**:
   - Ensured data consistency and validity with no errors or empty fields.

3. **Creating Filters and Calculations**:
   - Created filters for Channel Grouping, Device Category, and Date Range to allow dynamic data exploration.
   - Calculated key metrics like Total Sessions, Total Exits, Average Page Load Time, Average Time on Page, and Total Bounces.

4. **Measures Used**:
   - Used the following measures:

    ```Tableau
    Total Sessions = SUM([Sessions])
    Total Exits = SUM([Exits])
    Average Page Load Time = AVG([Page Load Time (s)])
    Average Time on Page = AVG([Time on Page (s)])
    Total Bounces = SUM([Bounces])
    Unique Pageviews = COUNTD([Pageviews])
    ```

5. **Creating the Dashboard**:
   - Designed the dashboard layout to include key performance indicators (KPIs), bar charts for monthly sessions and bounces, and a geographical breakdown of top countries by unique pageviews.
   - Utilized color coding and tooltips to enhance user experience and interactivity.

## Credits

Credits to [Data Tutorials](https://www.youtube.com/@datatutorials1) for providing the web traffic data and inspiration via their tutorial.

## Contact

For any questions or support, please reach out via [LinkedIn](https://www.linkedin.com/in/dimitris-danos).
