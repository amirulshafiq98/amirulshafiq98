
# 📊 Amirul Shafiq - Data Analytics Portfolio

Hi, I'm Amirul — a data enthusiast with a Bachelor's in Food Technology from the Singapore Institute of Technology (convocation October 2025). Over the past four years, I've immersed myself in analysing diverse datasets to assess the viability of novel food products developed during my undergraduate studies. This experience honed my skills in data analysis and storytelling to effectively engage stakeholders.

My pivotal moment came during an internship at Chiang Mai University, Thailand, where I assisted local beekeepers in determining optimal honey storage conditions. Despite collecting extensive data over 12 weeks, initial results were inconclusive. This challenge sparked my deep interest in data analysis, driving me to uncover actionable insights before returning to Singapore.

Beyond data, I enjoy exploring history, playing football (soccer), and continuously learning new skills — be it technical projects or enhancing communication abilities. I thrive in collaborative environments, believing that the best ideas emerge through teamwork.

[![resume](https://img.shields.io/badge/resume-233c67?style=for-the-badge&)](https://drive.google.com/file/d/1IGMmaLnnzJNvhCa6661vu9-cgEqVvhd9/view?usp=drive_link) <t/> [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/shafiq-g/)

---

# 🛠 Skills
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) <t/> ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) <t/> ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) <t/> ![Tableau](https://img.shields.io/badge/Tableau-39477F?style=for-the-badge&logo=realm&logoColor=white) <t/> ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) <t/> ![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white) <t/> ![Google Workspace](https://img.shields.io/badge/Google_Workspace-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

# :blue_book: Table of Contents
- [Portfolio Projects](https://github.com/amirulshafiq98#-highlighted-projects)
    - [SQL](https://github.com/amirulshafiq98#sql)
        - [Olist E-commerce Data Exploration](https://github.com/amirulshafiq98#olist-e-commerce-data-exploration)
        - [Cafe Promotions Data Cleaning](https://github.com/amirulshafiq98#cafe-promotions-data-cleaning)
        - [Mochi Sensory Database Setup](https://github.com/amirulshafiq98#mochi-sensory-database-setup)
    - [Visualisation (Tableau & Power BI)](https://github.com/amirulshafiq98#visualisation-tableau-and-power-bi)
        - [Cafe Promotions Daily Insights](https://github.com/amirulshafiq98#cafe-promotions-daily-insights)
        - [Superstore Data](https://github.com/amirulshafiq98#superstore-data)
        - [Olist E-commerce Sales Data](https://github.com/amirulshafiq98#olist-e-commerce-sales-data)
    - [Python](https://github.com/amirulshafiq98#python)
        - [Principal Component Analysis (PCA) of boba pearls](https://github.com/amirulshafiq98#principal-component-analysis-pca-of-boba-pearls)
        - [Honey Analysis for Optimal Storage](https://github.com/amirulshafiq98#honey-analysis-for-optimal-storage)
        - [University Allocation Based on WEF Report (2025)](https://github.com/amirulshafiq98#university-allocation-based-on-wef-report-2025)
        - [Mochi Ice-Cream Sensory Analysis](https://github.com/amirulshafiq98#mochi-ice-cream-sensory-analysis)
- [Education](https://github.com/amirulshafiq98#-education)
- [Certification](https://github.com/amirulshafiq98#-certification)

# 📌 Highlighted Projects

## SQL

### Olist E-commerce Data Exploration

![Olist E-commerce Schema](https://github.com/user-attachments/assets/b742b3d3-a93f-4870-8e9b-655eef152693)

**Repository:** [Olist Sales](https://github.com/amirulshafiq98/olist-sales)

**Objective:** Prepare data for visualisation to uncover sales insights of sellers and customers on the platform by product category, month, and year

**Description:** Utilised a Kaggle dataset from Olist, a Brazilian e-commerce company. Translated product categories from Portuguese using an Excel translation file. Performed data loading, cleaning, preprocessing, and exploratory data analysis (EDA)

**Skills:** Data joining, Common Table Expressions (CTEs), VLOOKUP, Entity Relationship Diagram (ERD)

**Tools:** SQL Server Management Studio (SSMS), Excel

**Outcome:** Generated four CSV files for Power BI with necessary primary keys for filtering visuals

### Cafe Promotions Data Cleaning

![Cafe Schema](https://github.com/user-attachments/assets/e9478e37-192e-436b-b85c-347f6858e318)

**Repository:** [Cafe Promos](https://github.com/amirulshafiq98/cafe-promos)

**Objective:** Prepare data for visualisation to determine which specific promotion had the most participations on a given day, along with a breakdown of completions

**Description:** Analysed a Maven Analytics dataset containing eight different promotions (Buy-One-Get-One & Discount). Promotions ran concurrently, ending in 5, 7, or 10 days. Each customer received one promotion every 7 days, with Day 24 as an exception. Conducted data loading, cleaning, preprocessing, and EDA

**Skills:** Data cleaning, CTEs, ERD, indexing, calculating 7-day moving averages

**Tools:** MySQL

**Outcome:** Generated six CSV files for Tableau visualisations, including stacked bar charts, line charts, tree maps, and tables

### Mochi Sensory Database Setup

![Flowchart](https://github.com/user-attachments/assets/a3cfbffe-b068-46ec-bf2f-2e086ad224d5)

**Repository:** [Mochi Ice cream](https://github.com/amirulshafiq98/mochi_icecream)

**Objective:** Build a full-stack sensory analytics pipeline to identify the most preferred Mochi formulation based on consumer feedback.

**Description:** The raw, wide-format Excel sensory panel data was first ingested into PostgreSQL via a Python script. It was then cleaned and transformed into a normalized, analysis-ready structure using dbt within PostgreSQL, preparing it for subsequent analytical processes.

**Skills:** Data Modeling, SQL Transformation (dbt, PostgreSQL), Python Scripting (Data Ingestion), Data Cleaning, Data Normalisation.

**Tools:** PostgreSQL, dbt, SQLAlchemy, Python

**Outcome:** A clean, normalized, and analysis-ready dataset hosted in PostgreSQL, serving as the foundational input for advanced sensory analytics.

---

## Visualisation (Tableau and Power BI)
### Cafe Promotions Daily Insights

![Overall](https://github.com/user-attachments/assets/eaf1bb01-2b88-474c-b035-c99bad541e04)

**Repository:** [Cafe Insights](https://github.com/amirulshafiq98/cafe-promos)

**Objective:** Create a dashboard showcasing daily participations for each promotion code and the percentage of claims before expiration.

**Description:** Developed a dashboard featuring line charts for total sales, stacked bar charts for redemptions, tree maps for customer join dates, horizontal stacked bar charts for average age groups, and tables displaying promotion details over 30 days.

**Skills:** Filtering, tooltips, conditional formatting, max-min markers on line charts

**Tools:** Tableau Public

**Outcome:** Delivered an interactive dashboard presenting promotion insights based on age group, customer join date, total sales, and redemptions.

---

### Superstore Data

![Updated BI](https://github.com/user-attachments/assets/b4a53c24-aa30-481e-af83-f853f8080554)

**Repository:** [Superstore Sales](https://github.com/amirulshafiq98/Superstore)

**Objective:** Identify consumer trends and sales insights across different segments and product categories

**Description:** Used a sample Superstore dataset to build a Power BI report featuring sales KPIs, segment-wise profit/loss analysis, and demographic visuals (e.g., waffle charts and customer location maps). Final dashboard highlights which segments to target based on profit margins and sales contribution

**Skills:** Native waffle chart visualisation, KPI cards, bar graphs, area charts

**Tools:** Power BI

**Outcome:** Delivered a compelling dashboard story useful for internal sales and marketing teams

---

### Olist E-commerce Sales Data

![Olist](https://github.com/user-attachments/assets/6cc8e351-309c-4def-b9a4-5aacb0dd5142)

**Repository:** [Olist Sales](https://github.com/amirulshafiq98/olist-sales)

**Objective:** Visualise seller and customer behavior across Brazil from 2016 to 2018.

**Description:** Built Power BI dashboards showing delivery times, order statuses, customer satisfaction, and top-selling product categories by state and year. The data was prepared in SQL Server, cleaned, and joined before visualization

**Skills:** DAX formulas, calculated columns, KPI cards, filters, slicers, star rating system

**Tools:** Power BI, SQL Server

**Outcome:** Created an interactive dashboard with dynamic filters by year, seller location, product category, and delivery time

---

## Python

### Principal Component Analysis (PCA) of Boba Pearls

![PCA Biplot](https://github.com/user-attachments/assets/575be2c8-bb36-4bd9-a3c0-c721a91f497b)

**Repository:** [PCA of Boba Pearls](https://github.com/amirulshafiq98/PCA_2d)

**Objective:** Reduce dimensionality of textural data from machine analysis and identify trials closest to a store-bought sample

**Description:** Conducted PCA on force-based variables like hardness, cohesiveness, and springiness from tapioca pearl formulations. Also estimated the correlation factors of hardness, cohesiveness and chewiness for the different formulations to aid in more focussed trials during sensory evaluation

**Skills:** PCA, matplotlib, seaborn, NumPy, scikit-learn, distance metrics

**Outcome:** Identified optimal trial combinations and visualised product similarity for formulation development

---

### Honey Analysis for Optimal Storage

![Bacillus](https://github.com/user-attachments/assets/73ac5db9-4f72-4771-b598-121c5ede8374)

**Repository:** [Honey Storage Recommendation](https://github.com/amirulshafiq98/honey)

**Objective:** Identify optimal honey storage conditions by analysing microbial changes over 6 weeks

**Description:** Ran descriptive statistics, two-way ANOVA and Tukey HSD tests for honey stored in analyse microbial growth across temperatures (4°C, 25°C, 37°C) and conditions (aerobic vs. anaerobic). Final recommendation was tailored for bee farmers in Northern Thailand

**Skills:** Statsmodels (ANOVA), Seaborn, matplotlib, pandas

**Outcome:** Provided a scientifically-backed recommendation on honey storage to reduce spoilage

---

### University Allocation Based on WEF Report (2025)

![Histogram](https://github.com/user-attachments/assets/547ae0b4-e766-4676-aa00-2319680fae04)

**Repository:** [University Allocation Optimisation](https://github.com/amirulshafiq98/Uni_Allocation)

**Objective:** Allocate students to majors using an optimisation model with realistic demand curves and constraints

**Description:** Designed an Integer Linear Programming (ILP) model using PuLP, factoring in costs, major demand, and budget constraints. Simulated multiple demand curve options (exponential, sigmoid, power law) to model student preferences

**Skills:** PuLP, matplotlib, numpy, pandas, ILP, smoothing

**Outcome:** Produced visually realistic student allocation plans for use by education planners

---

### Mochi Ice-Cream Sensory Analysis

![Boxplot](https://github.com/user-attachments/assets/cca2bcf0-b35f-46cb-9614-4b8769cddaa5)

**Repository:** [Mochi Ice cream](https://github.com/amirulshafiq98/mochi_icecream)

**Objective:** Apply advanced analytics to identify key sensory drivers and optimal Mochi formulations for upscaling.

**Description:** Utilising a Jupyter Notebook, Python was used to connect to the analysis-ready data in PostgreSQL. Principal Component Analysis (PCA) reduced data dimensionality to uncover key sensory profiles, while K-Means Clustering grouped similar Mochi formulations based on their sensory attributes. Finally, boxplots were plotted to visualise the cluster that had the highest acceptability score to determine the best formulation for upscaling. Each insight was visualised through various plots to guide decision-making.

**Skills:** Principal Component Analysis (PCA), K-Means Clustering, Data Visualization, Statistical Analysis, Python (Pandas, Scikit-learn, Plotly), Database Connectivity

**Tools:** Python, Jupyter Notebook, Scikit-learn, Pandas, Plotly.

**Outcome:** Generated a comprehensive analysis, including detailed visualizations and cluster assignments, to recommend the optimal Mochi formulation for upscaling based on insightful sensory data.

---

## 🎓 Education

**Bachelor (Tech) of Food Technology with Honours**  
***Singapore Institute of Technology (SIT)*** 

Expected Graduation: **October 2025**  
Relevant Modules: Applied Data Science, Design of Experiments (DOE), Sensory Evaluation, Market Research, Python Programming

## 📜 Certification

[Microsoft Excel Professional.pdf](https://drive.google.com/file/d/1B3BQ0u035_QRV_Z3mAUG9yNkwePIvwbU/view?usp=drive_link)

[Tableau Intelligence Analyst.pdf](https://drive.google.com/file/d/1h6Xj_F41INBYqER8P5C40wtB3CPs_sBa/view?usp=drive_link)

[Google Business Intelligence.pdf](https://drive.google.com/file/d/1q5w6OtSWzeQ-k4bUJhQW7Piwypb5kJqg/view?usp=drive_link)

[Google Cloud Analytics.pdf](https://drive.google.com/file/d/11wdgNZMMxaOcmbUs2Bvajf218BibwmKg/view?usp=drive_link)

[Google Advanced Data Analytics.pdf](https://drive.google.com/file/d/1AJC_e8AbeMTDd1UOZ48wzohlbpJQe19h/view?usp=drive_link)






