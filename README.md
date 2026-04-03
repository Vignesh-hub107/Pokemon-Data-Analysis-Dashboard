# Pokemon-Data-Analysis-Dashboard
This project focuses on analyzing Pokémon data and building an interactive dashboard using Power BI.

During the analysis, a key data quality issue was identified — duplicate Pokémon entries caused by multiple type classifications. This duplication affected aggregation logic, especially distinct counts, leading to incorrect insights.

To resolve this:
- Data was cleaned and duplicates were handled using Excel
- Unique identifiers were ensured for accurate analysis
- A dynamic Power BI dashboard was built for visualization

## 🔧 Tools Used
- Excel (Data Cleaning)
- Power BI (Data Visualization)

### 🚀 Key Features
- Top 5 Pokémon by Attack, Defense, and HP
- Type distribution analysis (Pie Chart)
- Speed comparison
- KPI Cards for quick insights
- Interactive slicer for type-based filtering

This project highlights the importance of data cleaning and how small inconsistencies can significantly impact analytical results.
Because when a Pokemon contains two types - Primary & Secondary
Then in Distinct Count of Pokemon name it shows less Total Count because of repeated names, but in Pie chart when it divides based on types it shows more Quantity because one name is assciated with multiple types so removal of secondary type is only solution 
