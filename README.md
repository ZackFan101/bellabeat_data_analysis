# Bellabeat Data Analysis (Google Data Analytics Certificate Capstone)

## 📌 Project Overview
This project was completed as the capstone for the **Google Data Analytics Professional Certificate**.  
The objective was to analyze smart device usage data from non-Bellabeat fitness trackers in order to identify major user trends. Insights were then applied to a Bellabeat product to support marketing strategy, increase customer engagement, and expand Bellabeat’s position in the global smart wellness device market.

---

## 🛠 Tools & Techniques
- **Excel**: Data cleaning and exploratory analysis on *dailyActivity_merged*  
- **SQL**: Data cleaning and transformation of *calories_Intensities_steps_merged*  
- **R (RMarkdown, ggplot2, dplyr)**: Statistical analysis and visualization  
- **Markdown / Documentation**: Report writing and communication  

---

## 🔍 Analysis Process
### Dataset 1: Daily Activity (Excel)
- Cleaned *dailyActivity_merged* dataset in Excel by removing duplicates and formatting inconsistencies.  
- Conducted exploratory analysis directly in Excel.  
- Derived key insights about user activity patterns and their relationship to calories burned.  

### Dataset 2: Calories, Intensities & Steps (SQL + R)
- Cleaned *calories_Intensities_steps_merged* dataset in SQL by standardizing data types, removing outliers, and joining relevant tables.  
- Imported cleaned dataset into R for correlation analysis and visualization.  
- Examined the relationship between activity intensity, steps, and calories burned.  
- Generated interactive visualizations and exported as an HTML report.  

---

## 📊 Key Findings
- **Excel Analysis (Dataset 1)**: Step counts correlate with calorie burn, but the relationship is not fully explanatory.  
- **SQL + R Analysis (Dataset 2)**: Activity intensity has a stronger impact on calorie expenditure than step count alone. Very active minutes show the strongest correlation with calories burned (r ≈ 0.54).  
- **User Efficiency**: Individuals differ in “steps per calorie” efficiency, meaning generic step goals are not effective.  
- **Daily Rhythm**: Activity peaks in the morning and evening, while midday is mostly sedentary.  

---

## ✅ Recommendations for Bellabeat
- **Product Design**: Add efficiency scores, intensity-based goals, and personalized midday reminders.  
- **Marketing Strategy**: Emphasize Bellabeat as the brand that helps users *“move smarter, not just more.”*  
- **User Engagement**: Align nudges with daily rhythms and tailor challenges to individual efficiency levels.  

---

## 📂 Repository Structure
bellabea_data_analysis/
│── README.md # Project introduction (this file)
│── report/
│ ├── bellabeat_final_report.pdf # Full report (Excel + SQL + R results)
│ └── analysis.html # R-based HTML report (Dataset calories_Intensities_steps_merged only)
│── scripts/
│ └── analysis.Rmd # R Markdown source (Dataset calories_Intensities_steps_merged only)
│── data/
├── dailyActivity_merged_cleaned.csv
└── calories_Intensities_steps_merged.csv

---

## 📎 Links
- [Final Report (PDF, full analysis)](report/bellabeat_final_report.pdf)  
- [R Markdown (.Rmd, Dataset 2 only)](scripts/analysis.Rmd)  
- [Interactive HTML Report (Dataset 2 only)](report/analysis.html)  

---

## 👤 Author
**Ziqiang Fan (Zack)**  
Google Data Analytics Certificate Graduate  
