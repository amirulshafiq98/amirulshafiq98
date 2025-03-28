
# Amirul Shafiq - Aspiring analyst with a background in food science
[![resume](https://img.shields.io/badge/resume-233c67?style=for-the-badge&)](https://drive.google.com/file/d/1x6n97tMACP2pK1ye9MLdkdUSMU23LG0V/view?usp=sharing) <t/> [![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/shafiq-g/)




## 🚀 About Me
Hi, I am Amirul and I am passionate about analysing data. I have a Bachelor's in Food Science where I have spent the last 4 years analysing dozens of datasets to determine the viability of the foods that I have developed in my undergrad. Over the years I have honed my ability not just to analyse data but also in storytelling to engage various stakeholders. In my capstone project, I was tasked to create a novel food product from scratch. This was where I developed skills such as data management, asking insightful questions and understanding stakeholder needs, skills that every analyst can benefit from. As a scientist, I have to be methodical with my approach to solving problems which is a transferable skill in the field of data analytics due to the sheer volume of dealing with messy datasets.

The reason why I chose to move away from the food industry was due to my experience during my internship in Thailand. At Chiang Mai University (CMU), I worked on a project where I helped Thai bee keepers with their storage of honey as they were not sure on how to maintain the quality over a period of time. My job was to find out, the best possible storage condition for two different types of honey in 7 months. After collating all the neccesary parameters, the data was inconclusive despite having 10 weeks worth of data for each type of honey. This led me down the rabbit hole of data analysis to give them an answer before I went back to Singapore. This was the point that started my data analysis journey solving real world problems using data.

Other than data analysis, things I do for fun include reading about history and playing football (soccer for the Americans). I also enjoy learning new skills be it technical like the projects below or communication to be able to learn from others and ask probing questions. I love working in a team as I believe that the best ideas can only be born when working together.



## 🛠 Skills
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft%20sql%20server&logoColor=white) <t/> ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) <t/> ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black) <t/> ![Tableau](https://img.shields.io/badge/Tableau-39477F?style=for-the-badge&logo=realm&logoColor=white) <t/> ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) <t/> ![Microsoft Office](https://img.shields.io/badge/Microsoft_Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white) <t/> ![Google Workspace](https://img.shields.io/badge/Google_Workspace-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

# :blue_book: Table of Contents
- [Portfolio Projects](https://github.com/amirulshafiq98#bar_chart-portfolio-projects)
    - [SQL](https://github.com/amirulshafiq98#sql)
        - [Olist E-commerce Data Exploration](https://github.com/amirulshafiq98#olist-e-commerce-data-exploration)
        - [Cafe Promotions Data Cleaning](https://github.com/amirulshafiq98#cafe-promotions-data-cleaning)
    - [Visualisation (Tableau & Power BI)](https://github.com/amirulshafiq98#tableau-and-power-bi)
        - [Cafe Promotions Daily Insights](https://github.com/amirulshafiq98#cafe-promotions-daily-insights)
        - [Olist E-commerce Sales Data (2016-2018)](https://github.com/amirulshafiq98#olist-e-commerce-sales-data)
    - [Python](https://github.com/amirulshafiq98#python)
        - [Principal Component Analysis (PCA) of boba pearls](https://github.com/amirulshafiq98#principal-component-analysis-pca-of-boba-pearls)
        - [Simple calculator for Texture Profile Analysis (TPA)](https://github.com/amirulshafiq98#simple-calculator-for-texture-profile-analysis-tpa)
- [Education](https://github.com/amirulshafiq98#school-education)





# :bar_chart: Portfolio Projects
In  this section I will outline briefly about the various projects I have worked on and what tools I used to achieve my goals

## SQL
### Olist E-commerce Data Exploration

![Cafe Schema](https://github.com/user-attachments/assets/e9478e37-192e-436b-b85c-347f6858e318)

**Repo:** https://github.com/amirulshafiq98/olist-sales

**Goal:** Prepare data for visualisation to uncover sales insights of sellers and customers on the platform by product category, month and year

**Description:** This dataset was form Kaggle by Olist, a Brazillian e-commerce company that sells all sorts of things from furniture to food and drinks. The products were written in Portugese and had to be translated using the translation file in excel before querying. Steps taken were: data loading, cleaning, preprocessing and exploratory data analysis (EDA)

**Skills:** Data joining, temporary tables (CTEs), v-lookup, entity relationship diagram (ERD)

**Technology:** SSMS, Excel

**Results:** Generated 4 .csv files to be used for DAX in PowerBI with the necessary primary keys for filtering visuals 

### Cafe Promotions Data Cleaning

![Olist E-commerce Schema](https://github.com/user-attachments/assets/6faf6df5-11b6-4118-9d78-eda2bc50451a)

**Repo:** https://github.com/amirulshafiq98/cafe-promos

**Goal:** Prepare data for visualisation to determine which specific promotion had the most number of participations on a given day as well as a breakdown on the number of completions

**Description:** This dataset was from Maven Analytics and contains 8 different types of promotions of two kinds (Buy-one-get-one & Discount). All of the promos ran concurrently ending in either 5, 7 or 10 days after they were given out. The promotions were given to cafe members every 7 days. Each customer only received 1 promotion before they are entitled to another 7 days later (Day 24 the exception). Steps taken were: data loading, cleaning, preprocessing and exploratory data analysis (EDA)

**Skills:** Data cleaning, temporary tables (CTEs), entity relationship diagram (ERD), indexing, calculating 7-day moving average

**Technology:** MySQL

**Results:** Generated 6 .csv files for visualisation in Tableau that corresponds to that given visual type (stacked bar chart, line chart, tree map and table)

## Tableau and Power BI
### Cafe Promotions Daily Insights

![Overall](https://github.com/user-attachments/assets/eaf1bb01-2b88-474c-b035-c99bad541e04)

**Repo:** https://github.com/amirulshafiq98/cafe-promos

**Goal:** Create a dashboard that shows which days have the most participations for a given promotion code and what percent of people claimed the promotion before it expires. 

**Description:** Line-chart for total sales, stacked bar chart for total redemptions, tree map for customer date joined, horizontal stacked bar chart for average age-group and a table to show information of the different promotions over the 30 days

**Skills:** Filtering, tooltips, table with conditional formating, max-min markers on line chart

**Technology:** Tableau Public

**Results:** A dashboard that shows the information of the cafe promotions based on age-group, customer date joined, total sales and total redemptions

### Olist E-commerce Sales Data

![Olist](https://github.com/user-attachments/assets/6cc8e351-309c-4def-b9a4-5aacb0dd5142)

**Repo:** https://github.com/amirulshafiq98/olist-sales

**Goal:** Create a dashboard that shows information on sellers, products and customers that can be sorted by total sales or total orders across categories, months and years

**Description:** Horizontal bar charts for both seller and product, pie-chart for type of payment, tree map for customer city, line chart for total sales and review score in a star rating format.

**Skills:** Slicers, parameters, top N, month sorting, max-min markers on line chart

**Technology:** PowerBI, DAX

**Results:** A dashboard that shows total sales, total orders, AOV, and MoM growth. Sellers and products information were also visualised toggleable by either sales or orders

## Python
### Principal Component Analysis (PCA) of boba pearls

![PCA Biplot](https://github.com/user-attachments/assets/ac3568ce-6e99-4dd7-a738-f20baf6791ae)

**Repo:** https://github.com/amirulshafiq98/pca_2d

**Goal:** Determine the best combination of additives to mimic the texture of high-GI tapioca boba pearls

**Description:** Different additives were added to tapioca starch based on design of experiments (DOE) to find out which combination(s) could retain the texture of tapioca boba pearls. A principal component analysis (PCA) graph was plotted along with a coefficient table to determine which combination(s) had the closests texture profile analysis (TPA) measures to a base tapioca boba pearl

**Skills:** Data inference, plotting graphs, scaling values

**Technology:** matplotlib, scikitlearn, pandas, numpy

**Results:** Plotted a PCA graph with trend lines for the different metrics accompanied with a correlation table to show which combination(s) additives are able to retain the textural properties of tapioca boba pearls

### Simple calculator for Texture Profile Analysis (TPA)

![Table](https://github.com/user-attachments/assets/8f941966-7ad6-43ae-8680-1945e0aaa361)

**Repo:** https://github.com/amirulshafiq98/tpa_calculator

**Goal:** Calculate hardness, chewiness, springiness and cohesiveness from a two-bite compression graph

**Description:** A two-bite compression graph has two peaks which are used to calculate various textural properties of an object. The script is capable of choosing the correct points in the graph to calculate the various metrics by just providing an .xlsx file

**Skills:** Reading/loading files, indexing

**Technology:** scipy, pandas, numpy

**Results:** Calculation of TPA metrics was possible at a large scale as only the raw data had to be inputted into the script to achieve an accurate result


# :school: Education
Bachelor's (Honours) in Food Science and Technology from Singapore Institute of Technology **(Graduation in November 2025)**

