# Economic Indicators Clustering & Analysis 🌎

This project analyzes socio-economic metrics for American countries using clustering techniques and visualization. The goal is to:

- Use LLM to get indicadotrs from world bank data set. 
- Identify patterns in economic development
- Highlight disparities between countries across the Americas
- Group countries into clusters based on similar development profiles

By doing so, we aim to provide a clear, data-driven overview of how countries in the Americas compare in terms of development, education, health, and economic performance.

## 📌 Project Highlights

- Fetches time-series economic data using the World Bank API (`wbdata`)
- Preprocesses data: handles missing values and standardizes features
- Uses **K-Means Clustering** to group countries by development indicators
- Visualizes null rate heatmaps, cluster patterns, and indicator distributions
- Applies **Linear Regression** for imputation of missing data in some cases

## 👀 Sample Visualizations

- Heatmap showing null value distribution by country and indicator
- Scatter plots of clusters across standardized GDP, education, and health features
- Cluster centroid trends over time (if applicable)

## Tech Stack

- **Data Access**: `wbdata`, `pandas`, `numpy`
- **Modeling**: `scikit-learn` (`KMeans`, `LinearRegression`)
- **Visualization**: `matplotlib`, `seaborn`
- **Utilities**: `re`, `math`, `json`, `warnings`

