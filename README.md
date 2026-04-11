🚗 EV Data Analysis & Web Scraping Project
📌 Project Overview

This project focuses on web scraping, data cleaning, and exploratory data analysis (EDA) of Electric Vehicle (EV) data. The dataset is collected from an online EV database and analyzed to extract meaningful insights about vehicle performance, efficiency, and market trends.

🔗 Project Links
(https://github.com/Prem999k/Electric-Vehicle-Data-Web-Scraping-and-Analysis)

📂 GitHub Repo: 
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
Scraped attributes like:
Brand & Model
Range (km)
Battery Capacity
Efficiency
Fast Charging Speed
Weight, Cargo, Seats, etc.

👉 Data scraping logic implemented using BeautifulSoup and Requests

2️⃣ Data Cleaning
Removed duplicates (reduced ~58,000 rows → ~990 unique entries)
Handled missing values using mean imputation
Standardized column names
Converted data types to numeric format
3️⃣ Exploratory Data Analysis (EDA)
🔹 Univariate Analysis
Histograms
KDE plots
Box plots
Violin plots
🔹 Bivariate Analysis
Scatter plots
Regression plots
Relationship analysis between:
Range vs Efficiency
Battery vs Fast Charging
Weight vs Cargo
🔹 Multivariate Analysis
Pairplots
Correlation Heatmap
Category comparisons (Brand vs Market Segment)
📁 Dataset Details
Feature	Description
Brand	EV Manufacturer
Model	Vehicle Model
Range (km)	Driving Range
Battery (kWh)	Battery Capacity
Efficiency	Energy consumption
Fastcharge Speed	Charging speed
Weight	Vehicle weight
Acceleration	0–100 km/h
Market Segment	Vehicle category
Seats	Number of seats
📈 Key Insights
Average EV range: ~378 km
Battery capacity ranges from ~14 kWh to 123 kWh
Fast charging speeds vary widely across models
Most EVs fall into C and D market segments
Strong relationships observed between:
Battery capacity & charging speed
Range & efficiency
