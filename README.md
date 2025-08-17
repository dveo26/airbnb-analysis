# 🏙️ Airbnb New York City: Data Analysis and Visualization

## 📌 Project Overview
This project presents a comprehensive exploratory data analysis (EDA) of the Airbnb market in **New York City**. The goal is to extract actionable insights to understand:
- Pricing structures
- Availability patterns
- Influence of location and property type on listings

By cleaning, analyzing, and visualizing the data, we offer recommendations for:
- **Hosts** to optimize their listings
- **Travelers** to find the best accommodation options

> 🔧 Tools Used: Python (Pandas, Matplotlib, Seaborn), Jupyter Notebook, and Power BI (for final interactive dashboard)

---

## 🔍 Key Insights from the Analysis

### 💰 Price Skewness
- Most listings are priced under **$250/night**
- The distribution is **right-skewed** – few high-cost listings act as outliers

### 🏠 Room Type Distribution
- **"Entire home/apt"** is the most common room type
- Followed by **"Private room"**
- **"Shared room"** and **"Hotel room"** are rare

### 🗺️ Geographical Hotspots
- **Brooklyn** and **Manhattan** have the highest concentration of listings
- These are the most competitive markets

### 🏙️ Price by Borough
- **Manhattan** has the **highest average prices**, followed by Brooklyn
- Queens, the Bronx, and Staten Island are more budget-friendly

### 🏘️ Top Neighborhoods by Listings
- **Williamsburg**
- **Bedford-Stuyvesant**
- **Harlem**

---

## 💡 Recommendations

### 🧑‍💼 For Hosts:
- **Strategic Pricing**: Be competitive, especially in saturated boroughs
- **Room Type Optimization**: Offering "Entire home/apt" can be more profitable
- **Invest Wisely**: Focus on top-performing neighborhoods for better ROI

### 🧳 For Travelers:
- **Budget Travel**: Look for listings in Queens, the Bronx, or Staten Island
- **Private Room Value**: Great for solo or couple travelers
- **Book Early**: High-demand areas sell out fast

---

## 📂 Dataset Summary

Dataset used: `airbnb_cleaned.csv`  
Total listings: **20,461**  
Total columns: **33**

### 🧾 Key Columns
| Column               | Description                                      |
|----------------------|--------------------------------------------------|
| `id`                 | Unique listing ID                                |
| `name`               | Listing name                                     |
| `host_id`            | Unique host ID                                   |
| `neighbourhood_group`| Borough (e.g., Brooklyn, Manhattan)              |
| `neighbourhood`      | Specific neighborhood                            |
| `latitude`, `longitude` | Location coordinates                        |
| `room_type`          | Type of accommodation offered                    |
| `price`              | Price per night (USD)                            |
| `minimum_nights`     | Minimum stay required                            |
| `number_of_reviews`  | Number of reviews                                |
| `availability_365`   | Available days per year                          |
| `rating`             | Overall rating                                   |
| `bedrooms`, `beds`, `baths` | Accommodation details                    |

---

## ⚙️ Methodology

### 1. 🧹 Data Cleaning & Preprocessing
- Removed rows with missing values in critical fields
- Dropped duplicate listings
- Converted invalid string values to numeric (e.g., "Studio", "New")
- Created `license_status` column for binary classification

### 2. 📊 Exploratory Data Analysis
- **Univariate Analysis**: Histograms, count plots
- **Bivariate Analysis**: Box plots, bar charts to explore relationships
- **Geospatial Analysis**: Mapped listing density by location

---

## 🧰 Tools and Libraries

| Purpose                    | Tools/Libraries Used         |
|---------------------------|------------------------------|
| Data Manipulation          | Pandas, NumPy                |
| Data Visualization         | Matplotlib, Seaborn          |
| Interactive Dashboard      | Power BI                     |
| Development Environment    | Jupyter Notebook             |

---

## 📈 Final Deliverable
**Live Dashboard: https://app.powerbi.com/links/Sj-dAeP6cL?ctid=75c6a54f-cdc9-4ed2-941c-7096cf7dbda0&pbi_source=linkShare&bookmarkGuid=5710ce5a-bac9-4a81-8a9a-dace892bede3**
An **interactive Power BI dashboard** summarizing the insights from the analysis.

---

## 📫 Contact

For questions, feedback, or collaborations, feel free to reach out!

