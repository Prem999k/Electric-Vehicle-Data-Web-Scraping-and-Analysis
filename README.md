🚗 EV Data Analysis & Web Scraping Project
📌 Project Overview

This project focuses on web scraping, data cleaning, and exploratory data analysis (EDA) of Electric Vehicle (EV) data. The dataset is collected from an online EV database and analyzed to extract meaningful insights about vehicle performance, efficiency, and market trends.


📂 GitHub Repo: 
(https://github.com/Prem999k/Electric-Vehicle-Data-Web-Scraping-and-Analysis)


⚙️ Tech Stack
Python
Pandas & NumPy
Matplotlib & Seaborn
BeautifulSoup (Web Scraping)
Requests
Jupyter Notebook
📊 Features of the Project
1️⃣ Web Scraping
Extracted EV data from multiple pages (1–50)
Scraped attributes:
Brand & Model
Range (km)
Battery Capacity
Efficiency
Fast Charging Speed
Weight, Cargo, Seats
Data scraping implemented using BeautifulSoup & Requests
2️⃣ Data Cleaning
Removed duplicates (~58,000 → ~990 rows)
Handled missing values (mean imputation)
Standardized column names
Converted data types to numeric
3️⃣ Exploratory Data Analysis (EDA)
🔹 Univariate Analysis
Histograms
KDE plots
Box plots
Violin plots
🔹 Bivariate Analysis
Scatter plots
Regression plots
Relationships:
Range vs Efficiency
Battery vs Fast Charging
Weight vs Cargo
🔹 Multivariate Analysis
Pairplots
Correlation heatmap
Brand vs Market Segment analysis
📁 Dataset Details
Feature	Description
Brand	EV Manufacturer
Model	Vehicle Model
Range (km)	Driving Range
Battery (kWh)	Battery Capacity
Efficiency	Energy Consumption
Fastcharge Speed	Charging Speed
Weight	Vehicle Weight
Acceleration	0–100 km/h
Market Segment	Vehicle Category
Seats	Number of Seats
📈 Key Insights
Average EV range: ~378 km
Battery capacity: ~14 kWh → 123 kWh
Fast charging speed varies significantly
Most EVs belong to C & D segments
Strong relationships:
Battery ↔ Charging Speed
Range ↔ Efficiency
