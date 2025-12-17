# 🎬 Intelligent Movie Insights Dashboard

An end-to-end **data analytics & visualization project** that extracts movie data from the **TMDB (The Movie Database) API**, processes it using **Python** and **Power Query**, and presents actionable insights through an **interactive Power BI dashboard**.

This project demonstrates real-world skills in **API integration, star schema modeling, data cleaning, DAX measure creation, and dashboard design**.

---

## 📌 Project Overview

The **Intelligent Movie Insights Dashboard** helps users analyze movie performance, popularity trends, genres, ratings, and revenue metrics using dynamic and interactive visuals.

**Key Highlights:**

* Live movie data collected from TMDB API
* Star schema data modeling
* 20+ advanced DAX measures
* Optimized Power BI dashboard with slicers & KPIs
* Clean, scalable, and industry-style data pipeline

---

## 🧰 Tech Stack

| Tool / Technology   | Usage                                    |
| ------------------- | ---------------------------------------- |
| **Python**          | TMDB API data extraction & preprocessing |
| **TMDB API**        | Source of movie metadata                 |
| **Power BI**        | Data modeling & visualization            |
| **Power Query (M)** | Data cleaning & transformation           |
| **DAX**             | Measures, KPIs & calculations            |
| **GitHub**          | Version control & documentation          |

---

## 📊 Data Source

* **API:** The Movie Database (TMDB)
* **Data Includes:**

  * Movies
  * Genres
  * Ratings
  * Popularity
  * Revenue & Budget
  * Release dates
  * Language & country information

> ⚠️ TMDB data is used for educational and analytical purposes only.

---

## 🧱 Data Modeling (Star Schema)

The dataset follows a **Star Schema** design for optimal performance and scalability.

**Fact Table:**

* `Fact_Movies`

  * Revenue
  * Budget
  * Popularity
  * Vote Count
  * Vote Average

**Dimension Tables:**

* `Dim_Date`
* `Dim_Genre`
* `Dim_Language`
* `Dim_Movie`
* `Dim_Country`

✔ Optimized relationships
✔ Reduced redundancy
✔ Faster DAX calculations

---

## 🧹 Data Cleaning & Transformation

Performed using **Power Query**:

* Removed duplicates and null values
* Data type standardization
* Date hierarchy creation
* Genre normalization (many-to-many handled)
* Column renaming for clarity
* Surrogate key generation

> Result: clean, analysis-ready dataset

---

## 📐 DAX Measures (20+)

Examples of measures created:

* Total Movies
* Total Revenue
* Average Rating
* Average Budget
* Revenue per Movie
* Top Rated Movies
* Popularity Index
* Movies Released YoY
* Revenue Growth %
* Genre-wise Movie Count

All measures follow **best DAX practices** with:

* Variables (`VAR`)
* Optimized filters
* Readable naming conventions

---

## 📈 Dashboard Features

### Key Visuals:

* KPI Cards (Revenue, Ratings, Movies)
* Genre-wise analysis
* Year-wise trends
* Top & bottom movies
* Rating vs Popularity comparison

### Interactivity:

* Dynamic slicers (Year, Genre, Language)
* Cross-filtering visuals
* Reset slicers button

> Designed with a clean, business-friendly layout

---

## 🖼️ Dashboard Preview

*(Add Power BI screenshots here)*

---

## 📂 Project Structure

```
Intelligent-Movie-Insights-Dashboard
│
├── data/
│   └── extracted_api_data.csv
│
├── python/
│   └── tmdb_api_extraction.py
│
├── powerbi/
│   └── Movie_Insights_Dashboard.pbix
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1️⃣ API Data Extraction

* Get TMDB API key
* Update API key in Python script
* Run Python script to fetch movie data

```bash
python tmdb_api_extraction.py
```

### 2️⃣ Power BI Setup

* Open `.pbix` file in Power BI Desktop
* Refresh data source
* Interact with dashboard

---

## 🎯 Learning Outcomes

* Real-world API data handling
* Star schema modeling
* Advanced Power BI & DAX skills
* Data storytelling through dashboards
* End-to-end BI project experience

---

## 🔮 Future Enhancements

* Incremental data refresh
* Machine learning-based movie predictions
* User rating sentiment analysis
* Deployment to Power BI Service

---

## 🙌 Acknowledgements

* **TMDB** for providing the API
* Power BI & Python communities

---

## 👤 Author

**Mohan Rao**
📌 Data Analyst | Power BI Developer
🔗 GitHub: [https://github.com/mohanrao06](https://github.com/mohanrao06)

---

⭐ *If you like this project, consider giving it a star!*


