#SF_crime-
Historical Study of Incidence Reports in  San Francisco
 and time-series forecasting to extract actionable insights. It also highlights my skills in data preprocessing, visualization, and modeling, enabling both descriptive and predictive analysis for real-world applications.

San Francisco Crime Data Analysis (2018–Nov 2024)
Project Overview:
In this project, I worked with a large dataset containing crime incidents in San Francisco from 2018 to the present. The dataset includes 990,000 rows and 36 attributes, covering crime types, locations, dates, and descriptions. My focus was on analyzing the distribution and trends of crimes, detecting crime hotspots, and predicting future crime volumes using machine learning methods.
Key Highlights:
1.	Handling Large Datasets:
-I employed chunking techniques to process the large dataset (100,000 rows per chunk), ensuring that the system memory was not overwhelmed.
-By breaking the data into smaller chunks, I was able to scale the processing efficiently and conduct detailed analysis without running into memory limitations.
2.	Data Preprocessing & Feature Engineering:
-I cleaned the data by filtering out rows with missing geographic coordinates (Latitude and Longitude), ensuring the integrity of location-based analysis.
-I applied StandardScaler to normalize the geographic coordinates, making them ready for clustering analysis.
3.	Clustering & Incident Hotspot Detection:
-I applied the DBSCAN clustering algorithm to identify geographic crime hotspots based on scaled latitude and longitude data.
-I visualized the results with heatmaps and scatter plots, which helped to uncover areas with high crime density and identify recurring patterns in crime incidents.
4.	Categorical Analysis:
-I aggregated and analyzed crime data by incident category, subcategory, and description across various chunks of the dataset.
-To reveal trends in crime types, I visualized the frequency of different crime categories and subcategories with bar charts.
-I also analyzed crime distribution across Police Districts, providing insights into which areas are most affected by specific types of incidents, visualized using heatmaps.
5.	Time Series Analysis & Forecasting:
-I implemented ARIMA and LSTM models to predict future crime incidents based on historical data.
-By conducting time-series analysis, I was able to forecast future incident volumes, providing valuable insights into potential crime trends.
6.	Visualization & Insights:
-I created both interactive and static visualizations, including heatmaps, time-series plots, and bar charts to effectively communicate my findings.
-These visualizations helped me gain insights into crime patterns, such as the most common types of crimes, the areas most affected, and the times of day with the highest levels of criminal activity.


