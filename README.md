# Malnutrition-Analysis-and-Forecasting-using-Power-BI
📌 Project Overview

Malnutrition among children under the age of five is a critical global health issue. This project aims to analyze worldwide malnutrition data, focusing on stunting, wasting, underweight, and overweight indicators, using Power BI.

The dashboard provides interactive insights across countries, regions, and income groups. Policymakers, NGOs, and researchers can use these insights to identify priority countries and develop data-driven nutrition policies.

🎯 Objectives

To study global malnutrition trends among children under five.

To compare malnutrition prevalence across income groups and regions.

To identify priority countries contributing the highest burden.

To design an interactive Power BI dashboard for visualization and storytelling.

📂 Datasets Used

country-wise averages.csv

Country-wise malnutrition percentages.

Columns: Country, Income_Group, Stunting_%, Wasting_%, Underweight_%, Overweight_%.

malnutrition-estimates.csv

Detailed child malnutrition estimates (under-5 population).

Columns: Country, Year, U5 Population, Stunting_%, Wasting_%, Underweight_%, Overweight_%, Income_Group, Burden.

Note:

Burden column = (U5 Population × Stunting_%)/100

Source: WHO Global Malnutrition Database

🛠️ Tools & Technologies

Power BI – Dashboard creation & visualization

Excel/CSV – Data storage & preprocessing

DAX (Data Analysis Expressions) – Custom measures for KPIs

🔎 Project Methodology
1. Data Collection & Cleaning

Imported datasets into Power BI.

Cleaned column names, removed duplicates & missing values.

Added calculated columns for Burden (Stunted Children).

2. Business Questions Defined

Which countries contribute most to the global malnutrition burden?

How do malnutrition trends vary across income groups?

What are the global trends in stunting, wasting, and underweight over time?

Which countries should be prioritized for interventions?

3. Visualization & Dashboard Design

Created KPIs, Maps, Bar Charts, Line Charts, Treemaps, Scatter Plots.

Designed dashboard with 4 pages for storytelling.

📊 Dashboard Pages
Page 1: Global Overview

KPIs: Stunting, Wasting, Underweight, Overweight.

World map: Stunting % by country.

Income group comparison chart.

Global trends line chart.

Page 2: Country Analysis

Drilldown country KPIs.

Line chart: Country vs. global average.

Burden share analysis.

Page 3: Priority Countries

Top 10 countries for stunting/wasting.

Treemap: Malnutrition burden.

Scatter plot: Stunting vs. Underweight.

Page 4: Insights & Recommendations

Narrative insights for policymakers.

Identified high-burden countries.

Highlighted policy focus regions.

📈 Key Insights

Stunting has reduced globally (27% in 2000 → 22% in 2020), but low-income countries still face high rates (~34%).

India, Nigeria, and Pakistan contribute nearly 40% of global stunting burden.

Income strongly correlates with malnutrition – high-income countries show <5% stunting, while low-income countries exceed 30%.

Sub-Saharan Africa & South Asia are hotspots for malnutrition.

Rising overweight prevalence in middle-income countries indicates a “double burden” of malnutrition.

🚀 How to Run the Project

Download the Power BI file (Malnutrition_Project.pbix).

Ensure datasets (country-wise averages.csv & malnutrition-estimates.csv) are in the same folder.

Open .pbix file in Power BI Desktop.

Use filters (Country, Year, Income Group) to explore insights interactively.

📌 Performance Testing

Filters Used: Country, Year, Income Group.

DAX Measures: Stunted Children, Wasted Children, Underweight Children, Overweight Children.

Total Visuals: 12 major visuals across 4 report pages.

✅ Conclusion

Malnutrition is declining globally but unevenly distributed.

Low-income countries require urgent intervention.

Top burden countries (India, Nigeria, Pakistan) need special policy focus.

Global strategies must address both under-nutrition and rising overweight cases.

🔮 Future Scope

Add data on micronutrient deficiencies & maternal health.

Implement predictive modeling for future malnutrition trends.

Create mobile-friendly dashboards for field officers.

Expand analysis to regional policies & intervention programs.

📎 Project Resources

Source Code/DAX Calculations: Included in .pbix file.

GitHub Repository: [Insert Link]

Demo Video / Project Walkthrough: [Insert Link]

✨ This project demonstrates how data visualization + storytelling can drive policy-level decisions in solving one of the world’s most pressing issues – child malnutrition.
