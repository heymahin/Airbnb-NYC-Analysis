# Airbnb-NYC-Analysis
Transforming raw, messy Airbnb data into actionable business insights using Excel and Power BI.


## 🔍 Problem Statement

The Airbnb NYC dataset from Kaggle contained thousands of listings but was highly unstructured — filled with missing values, data type errors, duplicates and inconsistent formatting. The goal was to clean this data, transform it and build a professional dashboard that answers real business questions about the NYC short-term rental market.


---

## ⚙️ Technology Stack

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data Cleaning & Preprocessing |
| Power Query | Data Transformation & Error Handling |
| Power BI | Interactive Dashboard & Visualization |

---

## 🔄 End-to-End Project Workflow

### 📥 Phase 1 — Data Collection
- Downloaded raw dataset from Kaggle (link below)
- Dataset contained 99,000+ listings with 25 columns

### 🧹 Phase 2 — Data Cleaning (Excel)
Raw data issues identified and resolved:

| Issue | Action Taken |
|-------|-------------|
| Missing values in price, reviews, neighbourhood | Removed or handled appropriately |
| Duplicate rows | Removed duplicates |
| Incorrect data types | Standardized all column formats |
| Blank and inconsistent rows | Cleaned and restructured |

### ⚙️ Phase 3 — Data Transformation (Power Query)
- Resolved Detect Type Mismatches errors
- Fixed data type conflicts in ID and NAME columns
- Reordered columns for better readability
- Removed unnecessary error steps from Applied Steps

### 📊 Phase 4 — Dashboard Development (Power BI)
Built an interactive 6-visual dashboard:

| Visual | Chart Type | Purpose |
|--------|-----------|---------|
| Price by Neighbourhood Group | Bar Chart | Compare pricing across NYC areas |
| Room Type Distribution | Pie Chart | Understand guest preferences |
| Active vs Inactive Listings | Bar Chart | Identify listing activity trends |
| Hosts with Multiple Listings | Bar Chart | Spot corporate vs individual hosts |
| Most Popular Listings | Bar Chart | Find top reviewed listings |
| Price vs Popularity | Scatter Plot | Identify best value neighbourhoods |

---

## 📊 Key Insights & Findings

### 💰 Pricing Analysis
> Queens has the highest average Airbnb price among all NYC neighbourhood groups, making it the most premium market for short-term rentals.

### 🏠 Guest Preferences
> 52% of all listings are Entire homes/apartments while 45% are Private rooms. This clearly indicates guests strongly prefer privacy over shared spaces.

### 📅 Market Activity
> Listing activity peaked in 2019 and dropped significantly afterward — a direct reflection of the COVID-19 pandemic's impact on the short-term rental market.

### 🏢 Host Landscape
> Corporate hosts like Sonder and Blueground dominate the multi-listing segment, posing strong competition for individual hosts in the NYC market.

### ⭐ Popularity Pattern
> Listings priced between $50–$200 receive the highest number of reviews and bookings. Very expensive listings show lower demand, indicating high price sensitivity among NYC Airbnb guests.

### 🗺️ Price vs Popularity
> The most expensive neighbourhoods are not always the most popular. Affordable areas with good connectivity attract more guests and generate higher booking volumes.

---

## 💡 Business Recommendations

- Hosts should price listings between **$100–$200** for maximum occupancy
- **Entire home** listings consistently outperform shared room listings
- Listings with **no recent reviews** should be refreshed to attract new guests
- Individual hosts should actively collect **reviews** to compete with corporate players

---

## 📁 Dataset Information

- **Source:** Kaggle — Airbnb Open Data
- **Dataset Link:** [Click Here](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
- **Original Condition:** Raw and messy — required significant cleaning
- **Total Records:** 99,000+ listings
- **Total Features:** 25 columns including price, neighbourhood, room type, host details, reviews and availability

---

## 👤 Author
- 💼 LinkedIn: [www.linkedin.com/in/mahinfatma]
- 🐙 GitHub: [https://github.com/heymahin]
