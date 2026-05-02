# 🚗 EV Data Analysis & Web Scraping Project

## 📌 Project Overview

This project focuses on **Web Scraping, Data Cleaning, and Exploratory Data Analysis (EDA)** of Electric Vehicle (EV) data.

The dataset is collected from an online EV database and analyzed to extract meaningful insights about **vehicle performance, efficiency, and market trends**.

---

## 🌐 GitHub Repository

🔗 https://github.com/Prem999k/Electric-Vehicle-Data-Web-Scraping-and-Analysis

---

## 🎯 Objectives

* Scrape EV data from multiple web pages
* Clean and preprocess raw data
* Perform Exploratory Data Analysis (EDA)
* Identify trends and relationships in EV data
* Generate meaningful insights for decision-making

---

## ⚙️ Tech Stack

* **Language:** Python
* **Libraries:**

  * Pandas & NumPy
  * Matplotlib & Seaborn
  * BeautifulSoup (Web Scraping)
  * Requests
* **Environment:** Jupyter Notebook

---

## 🚀 Features

### 🔹 1. Web Scraping

* Extracted EV data from multiple pages (1–50)
* Scraped attributes:

  * Brand & Model
  * Range (km)
  * Battery Capacity
  * Efficiency
  * Fast Charging Speed
  * Weight, Cargo, Seats
* Implemented using BeautifulSoup & Requests

---

### 🔹 2. Data Cleaning

* Removed duplicates (**~58,000 → ~990 rows**)
* Handled missing values (mean imputation)
* Standardized column names
* Converted data types to numeric

---

### 🔹 3. Exploratory Data Analysis (EDA)

#### 📊 Univariate Analysis

* Histograms
* KDE plots
* Box plots
* Violin plots

#### 📊 Bivariate Analysis

* Scatter plots
* Regression plots
* Relationships analyzed:

  * Range vs Efficiency
  * Battery vs Fast Charging
  * Weight vs Cargo

#### 📊 Multivariate Analysis

* Pairplots
* Correlation Heatmap
* Brand vs Market Segment analysis

---

## 📁 Dataset Details

| Feature          | Description        |
| ---------------- | ------------------ |
| Brand            | EV Manufacturer    |
| Model            | Vehicle Model      |
| Range (km)       | Driving Range      |
| Battery (kWh)    | Battery Capacity   |
| Efficiency       | Energy Consumption |
| Fastcharge Speed | Charging Speed     |
| Weight           | Vehicle Weight     |
| Acceleration     | 0–100 km/h         |
| Market Segment   | Vehicle Category   |
| Seats            | Number of Seats    |

---

## 📈 Key Insights

* Average EV range: **~378 km**
* Battery capacity ranges from **~14 kWh to 123 kWh**
* Fast charging speed varies significantly across models
* Most EVs belong to **C & D market segments**

### 🔗 Strong Relationships:

* Battery Capacity ↔ Charging Speed
* Range ↔ Efficiency

---

## 🔄 Workflow

* Web Scraping (BeautifulSoup + Requests)
* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Insight Generation

---

## 🚀 Future Improvements

* Automate scraping with scheduling
* Add real-time data updates
* Build dashboard using Power BI / Streamlit
* Apply Machine Learning for prediction
* Expand dataset sources

---

## 🙌 Conclusion

This project demonstrates how **Web Scraping and Data Analysis** can be combined to extract valuable insights from raw data, helping understand trends in the rapidly growing Electric Vehicle market.

---

