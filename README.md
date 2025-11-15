# Road-Accident-Dashboard

🚧 Road Accident Analytics: National Traffic Casualty Insights Dashboard
An interactive, data-driven visualization tool designed to analyze road accident patterns across vehicle types, locations, road conditions, and time periods—helping stakeholders understand casualty trends and improve road safety strategies.

The Road Accident Analytics Dashboard provides a comprehensive view of nationwide road casualties by severity, vehicle type, road surface, and environmental conditions. This dashboard is designed to support transportation authorities, policymakers, and safety analysts in identifying risk factors and reducing roadway incidents.

The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Main platform for building interactive visuals and insights.
• 🔄 Power Query – Used for data shaping, cleaning, and transformation.
• 🧠 DAX (Data Analysis Expressions) – Created measures for dynamic KPIs, % breakdown, year-over-year comparisons, and segmentation.
• 🧩 Data Modeling – Relationships established across accident, location, and condition tables for synchronized insights.
• 📁 Source File Format – .pbix for development and .png for dashboard snapshots.

Source: Kaggel Dataset.

The dataset contains detailed records of road accident casualties, including:
• Casualty severity (fatal, serious, slight)
• Vehicle type involved
• Road type & surface condition
• Light conditions during accidents
• Urban vs. rural location
• Monthly breakdown for current year vs. previous year
• Accident date and multi-year timeline

• Business Problem

Road accidents cause significant social and economic losses every year. Policymakers, transport authorities, and safety organizations often struggle to identify which factors—vehicle type, road surface, location, road type, or environmental conditions—contribute most to casualties.

Key questions such as:
✔ Which road types have the highest casualty counts?
✔ Do rural or urban areas experience more accidents?
✔ How do casualty trends vary month-to-month?
✔ Which vehicle types are most involved in accidents?
… are difficult to answer without a structured analytical view.

• Goal of the Dashboard

To deliver a comprehensive visual tool that:
• Highlights major risk areas contributing to road casualties.
• Supports transport planners and safety agencies in making data-driven decisions.
• Reveals how casualties vary by road conditions, geography, time, and vehicle category.
• Helps identify target areas for infrastructure improvements and safety campaigns.

• Walkthrough of Key Visuals
🔹 Top KPI Tiles (Header Section)

Shows the overall accident severity distribution:

Total Casualties: 417,883

Fatal Casualties: 7,135 (1.7%)

Serious Casualties: 59,312 (14.2%)

Slight Casualties: 351,436 (84.1%)

Casualties by Car: 333,485 (79.8%)
Provides a quick snapshot of accident severity and major contributors.

🔹 Total Casualties by Vehicle Type (Left Panel)

Categories include:
• Cars – 333,485
• Buses – 12,798
• Trucks – 34,472
• Motorcycles – 33,672
• Agricultural vehicles – 1,032
• Others – 3,424
This chart helps identify which vehicles contribute most to accident casualties (cars are the highest).

🔹 CY vs PY Monthly Casualties (Line Chart)

Shows current year (2022) vs previous year (2021) casualty trends over 12 months.
Enables seasonal pattern detection and YoY comparison.

🔹 Casualties by Road Type (Horizontal Bar Visual)

Breakdown includes:
• Single carriageway – 309.7K
• Dual carriageway – 67.4K
• Roundabouts – 26.8K
• One-way streets – 7.4K
• Slip roads – 4.7K
Identifies road types with highest risks (single carriageways dominate).

🔹 Casualties by Road Surface (Pie Chart)

Shows surface conditions during accidents:
• Dry – 67%
• Wet – 28%
• Snow/Ice – 5%
Mostly accidents occur on dry roads, suggesting driver behavior—rather than weather—is a major factor.

🔹 Casualties by Location / Area (Donut Chart)

• Urban – 162K
• Rural – 255.9K
Rural areas have considerably higher casualties, which may indicate higher speeds or limited lighting.

🔹 Casualties by Light Condition (Donut Chart)

• Daylight – 305K
• Darkness – 111.4K
Accidents in darkness are lower in count but often more severe.

🔹 Filter Panel (Right Side)

Includes:
• Accident Date filter (multi-year selector)
• Urban/Rural toggle
Enables fully interactive exploration across time and regions.

• Business Impact & Insights
1. Policy & Safety Planning

Authorities can identify high-risk road types (single carriageways) and conditions requiring intervention.

2. Infrastructure Improvements

Higher rural casualties highlight the need for better road lighting, signage, and modifications in rural traffic design.

3. Targeted Awareness Campaigns

Since most casualties occur in:
→ Cars
→ Daylight
→ Dry conditions
— campaigns can focus on driver behavior, speeding, and distraction rather than weather.

4. Resource Allocation

Emergency services and transport departments can prioritize regions and road types with the highest casualty volumes.

5. Data-Driven Decision Making

The dashboard equips stakeholders with actionable insights to reduce road accidents, save lives, and enhance national road safety.

Show what the dashboard looks like. - Example:
