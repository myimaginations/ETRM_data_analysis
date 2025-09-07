Energy Trade Data Analysis
Overview

This project analyzes an Energy Trade dataset containing transactions across commodities like Power, Gas, Coal, and Oil.
The objective is to clean, transform, and analyze the dataset to uncover key patterns and insights.

Purpose of Analysis
Ensure correct ingestion of multiple formats (CSV/Excel/JSON) into Pandas.
Perform data cleaning & transformation to ensure consistency.
Conduct exploratory data analysis (EDA) with creativity and depth.
Provide insightful visualizations with clear labels and readability.
Maintain code readability & documentation for reproducibility.

🔑 Key Steps
Data Ingestion
Loaded CSV, Excel, and JSON formats into Pandas.
Data Exploration
Inspected dataset shape, column types, unique values.
Verified missing values and duplicates.

Data Cleaning
Handled duplicates, ensured consistency in categorical values.
Converted date fields into datetime
Created new derived fields (e.g., notional value = volume × price).
Data Transformation & Analysis
Outlier detection with boxplots.
Aggregations (average price per commodity, monthly trends).
Distribution and trend analysis.

Visualizations
Commodity & trade type distribution (bar charts).
Price trends over time (line charts).
Notional value distribution (histograms).
Commodity vs Trader heatmap.

Insights Derived
Power & Gas dominate trading activity.
Price & volume distributions show clear outliers worth deeper analysis.
Monthly trends highlight fluctuations in trade volume and prices.
Heatmap analysis shows trader preference across different commodities.

Tech Stack
Python (Pandas, NumPy)
Matplotlib & Seaborn (visualization)
Jupyter Notebook (analysis & documentation)
