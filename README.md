# 🎬 Netflix Content Analysis (Pandas Capstone Project)

## 📌 Project Overview
This project analyzes the **Netflix Movies and TV Shows dataset** using **Python (Pandas)**.  
The goal is to clean the dataset, handle missing values, perform feature engineering, and extract meaningful insights about Netflix content trends.

---

## 🎯 Objective
- Perform complete **data cleaning** and preprocessing
- Handle **missing values** and duplicates
- Create new useful columns using **feature engineering**
- Perform **EDA (Exploratory Data Analysis)** using Pandas
- Generate key insights about Netflix content (Movies/TV Shows, genres, countries, ratings, trends)

---

## 📂 Dataset Information
- **Source:** Kaggle – Netflix Movies and TV Shows dataset  
- **File:** `netflix_titles.csv`
- **Main Columns:**
  - `show_id`, `type`, `title`, `director`, `cast`, `country`
  - `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Google Colab

---

## 🔧 Data Cleaning Steps
- Checked missing values in all columns
- Filled missing values:
  - `director`, `cast`, `country` → `"Unknown"`
  - `rating` → filled using mode
- Removed duplicate rows
- Converted `date_added` to datetime format
- Extracted duration into:
  - `duration_num`
  - `duration_type`

---

## 🧠 Feature Engineering
Created new columns for better analysis:
- `year_added` from `date_added`
- `month_added` from `date_added`
- `duration_num` and `duration_type` from `duration`

---

## 📊 Exploratory Data Analysis (EDA)
Some analysis questions covered:
- Movies vs TV Shows count
- Top 10 countries producing Netflix content
- Content added each year
- Most common ratings
- Most common genres
- Longest movies
- Most frequent directors and actors

---

## 🔥 Key Insights
- Netflix contains more **Movies** than **TV Shows**
- Most content was added after **2016**
- **USA** is the top country producing Netflix content
- **Drama** and **International Movies** are the most common genres
- Most common ratings include **TV-MA** and **TV-14**
- Movies generally have higher duration compared to TV Shows
- Netflix has a strong focus on international content growth

---

## 📁 Output Files
- `Netflix_Capstone.ipynb` → Full project notebook
- `netflix_cleaned.csv` → Cleaned dataset exported after preprocessing

---

## ✅ Conclusion
This project demonstrates complete end-to-end data analysis using Pandas.  
It improved my skills in data cleaning, handling missing values, feature engineering, and EDA, while extracting useful insights from a real-world Kaggle dataset.

---

## 🚀 Future Improvements
- Add visualizations using Matplotlib/Seaborn
- Build dashboards using Power BI / Tableau
- Apply ML models for prediction or recommendation

---

### 👤 Author
**Harsh Mishra**
