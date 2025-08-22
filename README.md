# PowerBI-videogame-analysis-reports
Global video game sales analyzed in Power BI. Dataset cleaned, transformed, and visualized to explore sales trends, regional differences, top titles, and publisher impact."

## Project overview
This project analyzes global video game sales using **Power BI**. The goal is to transform raw sales data into interactive visualizations to support data-driven business decisions.

## Dataset
The analysis uses a real-world `.csv` dataset containing yearly sales data across multiple regions.  
The dataset was downloaded from **Kaggle**, a popular platform for sharing data science resources.  

Key preprocessing steps included:  

- **Assigning correct data types**  
  Ensured each column (numeric, text, year, etc.) had the appropriate type for accurate processing and visualization.  

- **Unpivoting regional sales columns**  
  Converted regional columns into rows, creating two key fields: *Region* and *Sales*, making the dataset more flexible for filtering and analysis.  

- **Handling missing values**  
  Filled gaps in the *Year* column to maintain a complete and consistent time series.  

- **Removing redundant columns**  
  Dropped the *Global Sales* column since it represents the sum of all regions, which can be easily reconstructed within Power BI through measures and aggregations.  

## Key dashboard visualizations
- **Trend chart:** Annual sales from 1980 to 2015  
- **Scatter plot:** Correlation of sales between North America and Europe  
- **Bar charts:** Top 10 best-selling games and total sales per publisher  
- **Pie chart:** Regional sales distribution  
- **Card visualization:** Best-selling platform globally  
- **Matrix visualization:** Number of games released per platform and genre  

## Usage
1. Open Power BI Desktop  
2. Load the provided `.pbix` file or `.csv` dataset  
3. Explore the dashboard and interact with filters for platform, publisher, genre, or region  


## References
1. [Kaggle](https://www.kaggle.com/) – Dataset source (accessed April 23, 2025)  
2. [Skyvia Blog](https://blog.skyvia.com/etl-in-power-bi/) – ETL in Power BI (accessed May 3, 2025)  
3. [Medium Article](https://medium.com/@andruvictortj7/video-games-sales-dashboard-using-power-query-and-unpivot-column-7c2f99fde9b2) – Example dashboard (accessed May 3, 2025)  
