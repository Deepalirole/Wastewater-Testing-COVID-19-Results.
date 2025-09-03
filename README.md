🧪 Wastewater Testing COVID-19 Results Dashboard (Power BI)

This project visualizes COVID-19 genome copies detected in wastewater across various collection areas. Using Power BI, a dynamic dashboard was created to monitor and analyze the viral load trends, helping public health officials and researchers take informed decisions.


📊 Project Overview

The purpose of this project is to:

Monitor COVID-19 genome copies in wastewater over time.

Track changes in viral load across different collection areas.

Visualize thresholds to identify areas above or below the risk limit.

Offer a public-facing dashboard for transparency and awareness.


Tools Used

Power BI Desktop

Excel/CSV File (Assumed as source)

DAX (Data Analysis Expressions) for calculated fields

Power Query for data cleaning and transformation


✅ Features Implemented

Dynamic Filtering by Collection Areas

Genome Range Gauge to indicate current status

Yearly & Quarterly Trends of Avg Genome Copies

Threshold Flags: Above / Below threshold classification

Interactive Charts: Line chart, donut chart, bar chart

Distribution Analysis by Collection Area

![image alt](


🔁 Step-by-Step Process
1. Data Collection

Collected time-series data of genome copies per liter in wastewater.

Fields included: Date, Collection Area, Genome Copies, Threshold Flag.

2. Data Cleaning (Power Query)

Cleaned missing values and formatted dates.

Transformed data into appropriate structure (e.g., unpivot if needed).

Ensured proper data types for all fields.

3. Data Modeling

Created a single data table (or linked with dimension tables if any).

Defined relationships (if multiple tables).

Added calculated columns/fields such as:

Above Threshold / Below Threshold flag.

Average Genome Copies.

Monthly and Quarterly aggregations.

4. DAX Measures Created

Avg Genome Copies

Sum of Genome Copies per Liter

Above Threshold Count

5. Dashboard Design (Power BI Visuals)

Donut Chart – Proportion of Above vs Below Threshold.

Line + Marker Chart – Avg Genome Copies by Quarter.

Bar Chart – Distribution of genome copies across collection areas.

Gauge – Genome range overview.

Slicer Filters – By Collection Area, Month, Year.

6. Testing & Validation

Validated data with known samples.

Cross-checked averages, thresholds, and count metrics.

7. Exported Screenshot

Exported the dashboard to include in README for visualization.

.

📌 Use Cases

Public health monitoring

Predictive analysis for outbreaks

Community-level surveillance

Policy-making and intervention planning


