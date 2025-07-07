
# 🧭 Indian Tourism & Travel Packages: Web Scraping + Exploratory Data Analysis

A data-driven project that scrapes Indian tour packages from TravelTriangle, cleans and analyzes the data, and visualizes patterns in pricing, discounts, durations, and destinations to uncover actionable insights for the tourism industry.

---

## 📌 Project Overview

This project combines **web scraping** and **exploratory data analysis (EDA)** to:

- Extract package data such as destination, duration, price, and discount
- Analyze tourism trends across various Indian cities
- Explore customer preferences and market behavior
- Provide insights for optimizing travel offerings and promotional strategies

---

## 🧰 Tech Stack

- **Language**: Python
- **Libraries Used**:
  - `requests` – For fetching website data
  - `BeautifulSoup` – For HTML parsing and extraction
  - `re` (Regex) – For pattern matching and text cleanup
  - `pandas`, `numpy` – For data manipulation and preprocessing
  - `matplotlib`, `seaborn` – For visualization and trend plotting
  - `Jupyter Notebook` – For running and presenting EDA

---

## 🔍 Data Source

Web scraping was conducted on:

- 🌐 [TravelTriangle - India Tour Packages](https://traveltriangle.com/tour-packages/india)

> ⚠️ All data was scraped ethically and in compliance with the site's `robots.txt` guidelines. Data is used for educational purposes only.

---

## 🕸️ Web Scraping Process

1. **Inspected HTML structure** of package listings
2. **Selected appropriate tags** to extract:
   - Destination names
   - Price (original & discounted)
   - Duration (days & nights)
   - Discount percentage
   - Hotel ratings
3. Used Python scripts with `requests` and `BeautifulSoup` to collect data
4. Cleaned and stored data in structured CSV format for analysis

---

## 🧹 Data Cleaning Steps

- Split and normalized columns like price and duration
- Converted types for numerical analysis (e.g., integers for price & discount)
- Handled missing values and dropped unnecessary features
- Removed inconsistencies and ensured uniform formats for analysis

---

## 📊 Analysis Highlights

- **Popular Destinations**: Munnar, Manali, and Alleppey lead in frequency
- **Pricing**: Most packages fall under ₹50,000; few exceed ₹1 lakh
- **Trip Duration**: 3–5 day packages are most common
- **Discounts**: Majority between 5%–15%, not strongly linked to duration
- **Daily Cost Insights**:
  - Highest: Guptakashi, Gangotri, Yamunotri
  - Lowest: Kurnool, Puttaparthi, Nagarjuna Sagar
- **Budget Distribution**:
  - 57.3% Mid-Range (₹15K–₹50K)
  - 39.1% Low Budget (<₹15K)
  - 3.6% Premium (>₹50K)

---

## 🎯 Key Outcomes

- Mid-range, short-duration trips dominate demand
- Some destinations offer strong value with high discounts
- Longer trips cover more cities but don't guarantee better discounts
- Strategic pricing and package design can better capture market preferences

---



