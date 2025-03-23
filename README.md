# FBI Crime Rate Analysis - Power BI

## Project Overview
This dashboard is designed to help stakeholders get a clear picture of crime trends using interactive visualizations. It allows users to explore crime incidents based on different filters like time, location, and type of crime. The goal is to make crime data more accessible and actionable for law enforcement, policymakers, and the public.

## Data Source
- The dataset is sourced from FBI crime reports.
- It contains details like Incident Type, Year, Month, Day, Hour, Hundred Block, and Neighbourhood.
- To view the Dashboard click [here](https://app.powerbi.com/groups/me/dashboards/10586d80-4d12-49e1-bd92-d5854eb875f5?ctid=25ce0261-bbd6-49cd-a1e2-54260886d159&pbi_source=linkShare)

  ![FBI Crime Analysis](https://github.com/Balaji-0-5/FBI_Crime_Rate_Analysis/blob/main/FBI_Crime_Analysis.png)

## How to Use the Dashboard
The interactive dashboard allows users to drill down into data, hover over visuals for more insights, and apply filters to get specific information. Below is a breakdown of each component and how to use it.

### 1. Total Incidents Display
- This large yellow box in the center shows the total number of recorded crime incidents (474.565K).
- The number updates based on the filters applied, giving an instant view of crime volume under different conditions.

### 2. Filters Panel
The dropdowns at the top allow you to filter crime data by:
- Incident Type
- Year
- Month
- Day
- Hour
- Hundred Block
- Neighbourhood

**How to Use:**
- Simply select a value from any filter, and the dashboard updates instantly.
- Multiple filters can be used together for a more detailed analysis.

### 3. No of Incidents by Year (Line Chart with Drilldown & Tooltip Bar Chart)
- This line chart shows how crime trends have changed over the years.

**How to Use:**
- Click on a specific year to drill down into months, then further into days.
- Hover over any point to see a breakdown of incidents.
- The tooltip also includes a bar chart ranking crime types from most to least frequent in that year (month or day).

**Key Insights:**
- Crime incidents showed a steady decline from the early 2000s but started rising again in recent years.
- The tooltip helps identify which crime types were dominant in a given year (month or day).
- The trend-line helps us to understand the trend of crimes through time.

### 4. No of Incidents by Hour (Bar Chart with Drilldown & Tooltip Bar Chart)
- This chart highlights when crimes occur most often during the day.

**How to Use:**
- Click on a specific hour to drill down further into minutes.
- Hover over any bar to see a bar chart in the tooltip, ranking incident types by frequency for that hour.

**Key Insights:**
- Crime activity spikes in the late evening and nighttime.
- Early morning hours report fewer incidents.
- The tooltip helps understand which crimes dominate different time slots.

### 5. Crime Density Map (Heatmap)
- This heatmap visually represents crime concentration in different areas.

**How to Use:**
- The color intensity indicates crime density, with darker areas representing higher crime levels.
- Zoom in and out to focus on specific locations.

**Key Insights:**
- Some locations consistently show high crime density, indicating areas that may need targeted interventions.

### 6. Incidents Type Distribution (Pie Chart with Legend & Tooltip)
- This pie chart breaks down crimes by type.

**How to Use:**
- The stacked legend on the right shows different crime categories.
- Hover over any section to view the tooltip, which displays the incident type, count, and percentage.

**Key Insights:**
- Theft-related crimes make up the largest portion.
- Other significant categories include mischief and break-ins.

### 7. No of Incidents by Neighbourhood (Treemap with Drilldown & Tooltip Bar Chart)
- This treemap visualizes crime incidents across different neighborhoods.

**How to Use:**
- Click on a neighborhood to drill down into hundred_block-level crime data.
- Hover over a block to see a bar chart in the tooltip, ranking crime types for that area.

**Key Insights:**
- The Central Business District and a few other areas report the highest crime rates.
- The tooltip helps pinpoint the dominant crime type in each neighborhood.

## Who Can Benefit from This Dashboard?
- **Law Enforcement Agencies:** Identify crime hotspots and allocate resources efficiently.
- **Policymakers:** Use data-driven insights to shape crime prevention strategies.
- **Public & Community Organizations:** Raise awareness about local crime trends and improve neighborhood safety.

## Conclusion
This dashboard provides a powerful tool for analyzing crime data interactively. With features like drilldowns, tooltips, and geographic analysis, stakeholders can gain valuable insights to improve law enforcement strategies and community safety.
