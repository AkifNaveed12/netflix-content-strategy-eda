# Netflix Content Strategy – Exploratory Data Analysis

## 📌 Project Overview
This project performs an Exploratory Data Analysis (EDA) on Netflix’s Movies and TV Shows dataset to
analyze content composition, regional dependence, genre diversity, audience targeting, and temporal trends.
The goal is to derive data-driven insights that can support Netflix’s long-term content strategy.

---

## 🎯 Business Objectives
- Understand the overall composition of Netflix’s content library
- Compare Movies and TV Shows across multiple dimensions
- Analyze how Netflix’s content additions have evolved over time
- Identify dominant genres, ratings, and producing countries
- Detect potential strategic risks in content sourcing and audience focus

---

## 📊 Dataset Description
- **Source:** Netflix Movies & TV Shows dataset (CSV format)
- **Each row represents:** One Netflix title (Movie or TV Show)
- **Key columns:** Type, Country, Release Year, Date Added, Rating, Duration, Genres

---

## 🧹 Data Cleaning & Preprocessing
The following steps were applied to prepare the dataset:
- Converted `date_added` to datetime format
- Extracted `year_added` from `date_added`
- Filled missing values in categorical columns (`country`, `rating`)
- Removed duplicate records
- Handled multi-value columns such as country and genres

---

## 🛠 Feature Engineering
- Created **Content Age** feature:
Content Age = Year Added − Release Year

- This helped analyze whether Netflix prefers newer or older content.

---

## 📈 Exploratory Data Analysis
The analysis covered:
- Distribution of Movies vs TV Shows
- Top content-producing countries and their content share
- Trends in content addition over time
- Distribution and evolution of content ratings
- Most frequent genres and genre diversity growth
- Comparison of content age between Movies and TV Shows

Visualizations used include bar charts, line plots, box plots, and pie charts.

---

## 🔍 Key Insights
- Netflix hosts more Movies than TV Shows
- Content supply is concentrated in a small number of countries
- Rapid increase in content additions after 2015
- Mature-rated content dominates the catalog
- Genre diversity has expanded over time
- Movies generally have higher content age than TV Shows

---

## ⚠️ Strategic Risk Identified
Netflix shows dependency on limited content-producing countries and mature-rated content.
This concentration could pose long-term risks if audience preferences or regional regulations change.

---

## 📂 Repository Structure

├── Netflix_EDA_Case_Study.ipynb
├── netflix_cleaned.csv
├── README.md
└── requirements.txt


---

## 🚀 Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## ✅ Conclusion
This project demonstrates a complete data analysis lifecycle, from data understanding and cleaning to
insight generation and strategic interpretation. The methodology followed is aligned with real-world
data analyst workflows.
