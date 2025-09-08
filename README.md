# Bellabeat Data Analysis (Google Data Analytics Certificate Capstone)

## 📌 Project Overview
This project was completed as the capstone for the **Google Data Analytics Professional Certificate**.  
The objective was to analyze smart device usage data from non-Bellabeat fitness trackers in order to identify major user trends. Insights were then applied to a Bellabeat product to support marketing strategy, increase customer engagement, and expand Bellabeat’s position in the global smart wellness device market.

---

## 🛠 Tools & Techniques
- **SQL**: Data cleaning and consolidation  
- **Excel**: Additional wrangling and data formatting  
- **R (RMarkdown, ggplot2, dplyr)**: Data analysis and visualization  
- **Markdown / Documentation**: Report writing and communication  

---

## 🔍 Analysis Process
1. **Ask**: Define the business task — how Bellabeat can use smart device data to grow.  
2. **Prepare**: Import and join datasets (*dailyActivity_merged*, *calories_Intensities_steps_merged*) using SQL queries.  
3. **Process**: Remove duplicates, outliers, and incomplete records; standardize data formats.  
4. **Analyze**: Use R to explore relationships between steps, activity intensity, and calories burned.  
5. **Share**: Summarize findings with visualizations and a comprehensive report.  
6. **Act**: Translate insights into product and marketing recommendations for Bellabeat.  

---

## 📊 Key Findings
- **Intensity matters more than steps**: Very active minutes show the strongest correlation with calories burned (r ≈ 0.54). Activity intensity overall is a stronger driver of energy expenditure than step count.  
- **User efficiency varies**: Individuals differ in “steps per calorie” efficiency. Step goals alone are not effective; personalized guidance is needed.  
- **Daily rhythm**: Activity peaks in the morning and evening; midday shows long sedentary periods. Higher-intensity activities sometimes increase calorie burn without proportional step increases.  

---

## ✅ Recommendations for Bellabeat
- **Product Design**: Introduce efficiency scores, intensity-based goals, and personalized midday reminders.  
- **Marketing Strategy**: Position Bellabeat as helping users *“move smarter, not just more.”*  
- **User Engagement**: Align nudges with natural daily rhythms and adapt challenges to different efficiency levels.  

---

## 📂 Repository Structure
bellabeat-data-analysis/
│── README.md # Project introduction (this file)
│── report/
│ ├── bellabeat_final_report.pdf # Final project deliverable
│ └── analysis.html # Interactive HTML report (knit from Rmd)
│── scripts/
│ └── analysis.Rmd # R Markdown source file
│── data/
├── dailyActivity_merged_cleaned.csv
└── calories_Intensities_steps_merged.csv

---

## 📎 Links
- [Final Report (PDF)](report/bellabeat_final_report.pdf)  
- [R Markdown (.Rmd)](scripts/analysis.Rmd)  
- [Interactive HTML Report](report/analysis.html)  

---

## 👤 Author
**Ziqiang Fan (Zack)**  
Google Data Analytics Certificate Graduate  
