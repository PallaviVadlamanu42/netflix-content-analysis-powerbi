# 🎬 Netflix Content Analysis & Power BI Dashboard

## 📌 Project Title

**Netflix Content Analysis & Interactive Dashboard – Power BI**

## 📄 Summary

This project delivers a **comprehensive and interactive Power BI dashboard** for analyzing Netflix’s global content library.
It uses publicly available data to explore **content growth trends, genre popularity, ratings distribution, and country-wise availability**, while allowing **drill-down into individual movies and TV shows**.

The dashboard is designed for **media analysts, content strategists, streaming industry researchers, and entertainment decision-makers** who want to understand Netflix’s content distribution strategy and global reach.

---

## 🌟 Features / Highlights

* **📅 Content Trends Over Time** → Growth of movies and TV shows since 2010.
* **⭐ Ratings Breakdown** → Popular content ratings (TV-MA, TV-14, PG, etc.).
* **🎭 Top 10 Genres** → Most common genres across Netflix’s catalog.
* **🌍 Global Availability Map** → Country-wise distribution of Netflix content.
* **🎬 Individual Show Insights** → Details on cast, director, genre, and description for any selected title.
* **📊 Data Model View** → Star schema design for efficient filtering and analysis.

---

## 📊 Data Source

* **Dataset**: [Netflix Movies and TV Shows – Kaggle](https://www.kaggle.com/shivamb/netflix-shows)
* **Formats**: `.csv` and `.xlsx`
* **Key Fields**:

  * Title & Type (Movie/TV Show)
  * Genre (Listed In)
  * Rating
  * Release Year
  * Cast & Director
  * Countries Available

---

## 🎯 Business Problem

Netflix continuously expands its library to cater to global audiences.
**Understanding what type of content is being added, where it’s available, and how trends evolve** is crucial for:

* Strategic content acquisition
* Regional market targeting
* Enhancing viewer engagement

---

## ✅ Goal of the Dashboard

To provide **actionable insights** into Netflix’s content portfolio by visualizing:

* Content addition trends by year
* Genre and rating distribution
* Country-wise availability
* Cast and director networks
* Detailed individual show-level data

---

## 🖥️ Tech Stack

* **Power BI** → Interactive dashboard creation
* **Excel** → Data cleaning and preparation
* **CSV Dataset** → Raw Netflix dataset
* **Star Schema Modeling** → Optimized data relationships

---

## 📈 Business Impact

* **Media companies** → Identify content gaps & opportunities
* **Content producers** → Understand audience preferences by region
* **Analysts** → Track global entertainment trends over time

---

## 📂 Repository Structure

```
Netflix-Data-Analysis-PowerBI/
│── netflix_titles.csv                 # Raw dataset
│── Netflix data.xlsx                   # Cleaned dataset
│── Netflix Dashboard Power BI.pbix     # Dashboard (connects to external dataset)
│── Netflix Dashboard with Data.pbix    # Dashboard with embedded dataset (no setup needed)
│── Screenshot (87).png                 # Individual show insights view
│── Screenshot (88).png                 # Global analysis view
│── Screenshot (89).png                 # Data model view
│── README.md                           # Project documentation
```

---

## 📷 Dashboard Preview

**Individual Show Insights**
![Screenshot 87](Screenshot%20\(87\).png)

**Global Analysis Overview**
![Screenshot 88](Screenshot%20\(88\).png)

**Data Model**
![Screenshot 89](Screenshot%20\(89\).png)

---

## 🚀 How to Use

1. **Quick Start** → Download `Netflix Dashboard with Data.pbix` and open in **Power BI Desktop** (no setup required).
2. **Custom Setup** →

   * Download `Netflix Dashboard Power BI.pbix` and `Netflix data.xlsx`.
   * Open in Power BI Desktop and connect to the Excel dataset.
3. Explore the dashboard using slicers, filters, and interactive visuals.

---

## 📌 Data Source

Dataset sourced from [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/shivamb/netflix-shows).

---

## 📜 License

This project is licensed under the **MIT License** – you are free to use, modify, and distribute with proper attribution.


