#SF_crime-
Historical Study of Incidence Reports in  San Francisco

San Francisco Crime Data Analysis (2018–Present)
Project Overview:
In this project, I analyzed a large dataset of crime incidents in San Francisco, spanning from 2018 to the present. The dataset consists of 990,000 rows and 36 attributes, including crime types, locations, dates, and descriptions. The analysis focused on understanding the distribution and trends of crimes, identifying hotspots, and forecasting future crime volumes using advanced machine learning techniques.
Key Highlights:
1.	Handling Large Datasets:
-	Utilized chunking techniques to efficiently process the large dataset (100,000 rows per chunk) without overwhelming system memory.
-	Managed the data in chunks to enable scalable processing and facilitate detailed analysis.
2.	Data Preprocessing & Feature Engineering:
-	Cleaned the dataset by filtering rows with missing geographic coordinates (Latitude and Longitude) to ensure the integrity of location-based analysis.
-	Applied StandardScaler to scale geographic coordinates (Latitude and Longitude) for clustering analysis.
3.	Clustering & Incident Hotspot Detection:
-	Applied the DBSCAN clustering algorithm on the scaled latitude and longitude data to identify crime hotspots across San Francisco.
-Visualized the clusters using heatmaps and scatter plots to showcase high-density areas and patterns of crime incidents.
4.	Categorical Analysis:
-	Conducted in-depth aggregation and analysis of incident categories, subcategories, and descriptions across different chunks of data.
-	Visualized the frequency of different crime types and subcategories using bar charts to uncover trends and dominant crime types.
-	Analyzed crime distribution across Police Districts using heatmaps, offering insights into regional crime patterns.
5.	Time Series Analysis & Forecasting:
-	Implemented ARIMA and LSTM models to forecast future crime incidents based on historical data.
-	Conducted time-series analysis to predict incident volumes, providing valuable insights for future crime trend forecasting.
6.	Visualization & Insights:
-	Created interactive and static visualizations such as heatmaps, time-series plots, and bar charts to effectively communicate findings.
-	Developed insights into crime patterns, including the most frequent incidents, the areas most affected by crime, and the times of day with the highest crime activity.
This project demonstrates my ability to work with large, complex datasets and apply machine learning techniques like clustering and time series forecasting to derive actionable insights. It also highlights my skills in data preprocessing, visualization, and model deployment to provide both descriptive and predictive analysis for real-world applications.


