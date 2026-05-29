# pcmc-mula-river-analytics
"Power BI tracking and analysis dashboard built to monitor tree data variables and KPIs for the PCMC Mula River Rejuvenation Project."

# PCMC Mula River Rejuvenation Project - Trees Analysis Dashboard

### 📊 [Click Here to View the Interactive Dashboard](YOUR_POWER_BI_PUBLIC_LINK_HERE 
(https://github.com/Hitesh-2146/pcmc-mula-river-analytics/blob/a202f3b11a3a94155d907ae56063a62542525b20/PCMC%20River%20Rejuvenation%20Dashboard.pbix))

![Trees Analysis Dashboard] https://github.com/Hitesh-2146/pcmc-mula-river-analytics/blob/fc70bc7e370778728a55789687fcf795340cf3c2/PCMC%20River%20Rejuvenation%20Dashboard.png

### 📌 Project Overview
Built a specialized environmental data tracking and analysis dashboard for the PCMC Mula River Rejuvenation Project. This initiative stands as one of the largest municipal development frameworks under the Pimpri-Chinchwad Municipal Corporation. The dashboard empowers project managers and conservation teams to dynamically monitor tree health, structural dimensions, and field actions.

### 🛠️ Data Structure & Modeling
The dashboard is built using a clean, structured schema divided into dedicated relational tables to analyze growth variables effectively:
* **Group Data:** Handles action categorization with fields like `Group`, `Tree no.`, and execution logging through `Current Date Time`.
* **Size Metrics:** Contains calculation measures and physical attributes including `Age`, `Height`, `Girth`, `Spread`, `Avg. Age`, `Avg Height`, `avg. Girth`, and `Growth Index`.
* **Tree Taxonomy:** Tracks specific species data via `Botanical Name`, `Local Name`, and calculates cumulative inventory using `Total Tree`.

### 💡 Key Metrics & Insights Discovered
* **Inventory Overview:** Tracks a baseline core dataset of 1K Total Trees within the surveyed zone.
* **Environmental Growth Baselines:** Established clear structural averages for the asset database:
  * **Average Age:** 22.54 years
  * **Average Height:** 9.99 feet
  * **Average Girth:** 0.58
  * **Growth Index:** 17.25
* **Operational Action Groups:** Categorized individual trees into distinct, actionable groups to drive project management decisions:
  * **To be retained** (Highest volume)
  * **To be transplanted**
  * **To be removed**
  * **Trees outside project boundary**
* **Advanced Visualizations & Interactive Slicers:**
  * **Age vs. Height:** A detailed bar chart showing the frequency distribution of tree heights across various ages.
  * **Spread vs. Age:** A custom area line chart mapping out how canopy coverage expands over time.
  * **Tree Structure Analysis:** A scatter plot displaying the correlation between trunk girth and the overall height count.
  * **Dynamic Filters:** Included easy-to-use age group checkboxes alongside strict adjustment sliders for both Age (Years) and Height (Feet) to help stakeholders filter data instantly.

### 🚀 Technical Skills Demonstrated
* **Business Intelligence Reporting:** Power BI dashboard design, custom thematic formatting (environmental green styling), and conditional reporting cards.
* **Data Transformations:** Segmenting numeric ranges into custom operational categorical bins (`Between 20 and 30`, `Higher than 30`, `Under 10`).
* **Stakeholder Enablement:** Providing complex data insights in an easy-to-understand format for both non-technical municipal authorities and corporate clients.
