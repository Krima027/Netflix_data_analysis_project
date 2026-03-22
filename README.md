# 🎬 Netflix Data Analysis & Dashboard

## 📌 Overview
This project analyzes Netflix's content dataset to understand trends in content distribution, growth over time, popular genres, and audience targeting. An interactive dashboard is also built using Power BI.

---

## 🛠️ Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Power BI  

---

## 📂 Project Structure
```
Netflix-Data-Analysis/
├── data/
├── notebooks/
├── dashboard/
├── images/
└── README.md
```

---

## 🔧 Data Preparation
- Handled missing values using column-wise approach  
- Converted `date_added` to datetime  
- Extracted `year_added` and `month_name`  
- Removed duplicates  
- Split and exploded multi-value columns (genres, country, cast)  
- Created `rating_group` for audience analysis  

---

## 📊 Key Insights
- Movies dominate Netflix content  
- Rapid growth in content after 2015  
- USA and India are top content producers  
- Drama and International Movies are most common  
- Majority content targets Adults and Teens  

---

## 📈 Dashboard Features
- KPI cards (Total Titles, Movies, TV Shows)  
- Movies vs TV Shows distribution  
- Content growth over years  
- Top genres and countries  
- Rating-based audience analysis  
- Interactive filters  

---

## 🚀 How to Use
- Run the notebook for analysis  
- Open the Power BI file to explore the dashboard  
