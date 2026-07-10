# 📊 Student Spending Analytics — Power BI Dashboard

> **Interactive 24-page Power BI report analyzing spending patterns of 1,000 students across demographics, majors, income levels, and academic years — built with DAX, Power Query, and advanced data visualizations.**

---

## 🔗 Portfolio Links
- 📄 **[View Full Report (PDF)](./PowerBI%20Navin.pdf)**
- 👤 **[LinkedIn](https://www.linkedin.com/in/navin-elango)**

---

## 📌 Project Overview

This project analyzes fictional student spending data obtained from Kaggle, representing the spending habits of **1,000 students** across various demographic groups and academic backgrounds. The goal was to uncover meaningful insights about how students allocate their budgets across different categories — and how factors like gender, major, income level, and year in school influence spending behavior.

This report demonstrates end-to-end Power BI development skills including data preparation, data modeling, DAX measure creation, and professional dashboard design.

---

## 📂 Dataset

| Field | Description |
|-------|-------------|
| Student ID | Unique identifier for each student |
| Age | Age of the student (in years) |
| Gender | Male, Female, Non-binary |
| Year in School | Freshman, Sophomore, Junior, Senior |
| Major | Biology, Economics, Engineering, Computer Science, Psychology |
| Monthly Income | Monthly income in dollars |
| Financial Aid | Financial aid received in dollars |
| Tuition | Tuition expenses in dollars |
| Housing | Housing expenses in dollars |
| Food | Food expenses in dollars |
| Transportation | Transportation expenses in dollars |
| Books & Supplies | Books and supplies expenses in dollars |
| Entertainment | Entertainment expenses in dollars |
| Personal Care | Personal care expenses in dollars |
| Technology | Technology expenses in dollars |
| Health & Wellness | Health and wellness expenses in dollars |
| Miscellaneous | Miscellaneous expenses in dollars |
| Preferred Payment Method | Cash, Card, Mobile Payment App |

---

## 🛠️ Data Preparation (Power Query)

Three stages of data cleaning and transformation were performed:

**Step 1 — Promoted Headers**
Promoted the first row of data to become column headers, ensuring field names aligned correctly with their respective data values.

**Step 2 — Renamed Columns and Created Primary Key**
The first column was renamed to Student ID and all column names were adjusted to a consistent, readable format. The Student ID column serves as the unique identifier for each row.

**Step 3 — Cleaned Values and Unpivoted Categories**
- Standardized Preferred Payment Method by replacing "Credit/Debit Card" with "Card"
- Corrected invalid Student ID values by assigning new unique IDs
- Unpivoted key expense columns (entertainment, technology, etc.) into Category and Spending Amount to enable flexible category-level analysis

---

## 📐 Data Modeling

- **Star Schema design** with fact and dimension tables
- Created calculated columns and **8 DAX KPI measures** including:
  - Total Spending
  - Average Spending per Student
  - Monthly Spending Trends
  - Savings Rate
  - TuitionAidGap (Max and Min)
  - Average Spending by Category
  - Technology Spending Deviation by Major
  - Top Health Spender by Major

---

## 📊 Dashboard Pages (24 Pages)

| Page | Content |
|------|---------|
| Project Description | Dataset overview and objectives |
| Data Directory | Field definitions and descriptions |
| Data Prep 1 | Promoted headers documentation |
| Data Prep 2 | Column renaming and primary key |
| Data Prep 3 | Cleaned values and unpivoting |
| Question 1 | Spending by Gender and Major |
| SOL REP 1 | Visualizations — Gender and Major analysis |
| Discussion 1 | Insights and interpretation |
| Question 2 | Tuition vs Financial Aid by Year |
| SOL REP 2 | Visualizations — Tuition Aid Gap analysis |
| Discussion 2 | Insights and interpretation |
| Question 3 | Entertainment and Technology by Income Level |
| SOL REP 3 | Visualizations — Income Level analysis |
| Discussion 3 | Insights and interpretation |
| Question 4 | Food and Transportation by Year and Gender |
| SOL REP 4 | Visualizations — Food and Transportation analysis |
| Discussion 4 | Insights and interpretation |
| Question 5 | Health and Books Spending by Major |
| SOL REP 5 | Visualizations — Health and Books analysis |
| Discussion 5 | Insights and interpretation |
| Question 6 | Technology Spending Deviation and Average Spending |
| SOL REP 6 | Visualizations — Technology Deviation analysis |
| Discussion 6 | Insights and interpretation |
| Summary | Key findings and conclusions |

---

## 📈 Visualizations Used

- Clustered Bar Charts
- 100% Stacked Bar Charts
- Pie and Donut Charts
- Area Charts
- KPI Cards
- Treemap Visuals
- Deviation Charts
- Cross-filtering Slicers (Gender, Income Level, Major, Year in School)
- Drill-through functionality

---

## 💡 Key Insights

- **Male students** had the highest total spending ($213,461) compared to Female ($195,852) and Non-binary ($198,175)
- **Engineering majors** were the top health and wellness spenders
- **Biology students** showed the highest technology spending deviation above average (+4.1)
- **Computer Science and Psychology** majors had the lowest deviation in technology spending (-2.3)
- The **Tuition Aid Gap** ranged from a minimum of 994K to a maximum of 1M across academic years
- **High income students** consistently outspent Low and Medium income peers across entertainment and technology categories

---

## 🧰 Tools & Technologies

| Tool | Usage |
|------|-------|
| Power BI Desktop | Dashboard development and publishing |
| Power Query (M) | Data cleaning and transformation |
| DAX | Calculated measures and KPIs |
| Star Schema | Data modeling |
| Kaggle | Data source |
| GitHub | Portfolio hosting |

---

## 👤 About Me

**Navin Elango** — Power BI Developer and Data Analyst based in Dallas, TX

- 🎓 MS in Business Analytics, University of Delaware (GPA 3.8)
- 💼 2.5+ years of full-time BI and analytics experience
- 🔧 Skills: Power BI, DAX, Power Query, SQL, Python, Tableau, Excel
- 🌐 [LinkedIn](https://www.linkedin.com/in/navin-elango)
- 📧 msnavin2000@gmail.com
- 📍 Dallas, TX | Authorized to work in the U.S. (OPT) — No sponsorship required

---

*Built with ❤️ using Power BI Desktop | Data source: Kaggle*
