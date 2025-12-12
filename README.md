# Youth Unemployment Data Analysis Dashboard  
Using MongoDB Atlas, MongoDB Compass, and MongoDB Charts

## 👥 Group Members
- **Soumya Batra – 341107**  
- **Arpita Gupta – 341068**  
- **Avni Singla – 341071**

## 1. Project Overview
This project analyzes global youth unemployment trends using MongoDB Atlas and MongoDB Charts.  
The objective is to visually explore how youth unemployment varies across countries, regions, and time.  
All visualizations were created in MongoDB Charts and combined into a single interactive dashboard.  
This work corresponds to Project B of the DBMS coursework.

## 2. Dataset Used
**Dataset:** Global Youth Unemployment Dataset  
**Source:** Kaggle  
**Format:** CSV  
**Rows:** Approximately 17,000  

### Columns:
- Country  
- CountryCode  
- Year  
- YouthUnemployment  

The dataset provides annual youth unemployment percentages for countries across the world.

## 3. Steps Followed

### Step 1: MongoDB Atlas Setup
A cloud cluster was created on MongoDB Atlas.

### Step 2: Data Import
The CSV dataset was imported into a database named **global_unemployment** and a collection named **youth_unemployment** using MongoDB Compass.

### Step 3: Connection to MongoDB Charts
The database was linked to MongoDB Charts for visualization.

### Step 4: Chart Creation
Multiple visualizations were created to answer different analytical questions.

### Step 5: Dashboard Construction
All charts were combined into a single public dashboard.

## 4. Visualizations Included

1. **Trend of Youth Unemployment in India (1991–2023)**  
2. **Top 30 Countries With Highest Average Youth Unemployment**  
3. **Youth Unemployment Trends in BRICS Nations**  
4. **Global Youth Unemployment Choropleth Map**  
5. **Youth Unemployment Heatmap (2004–2023)**  
6. **Regional Share of Global Youth Unemployment (2000–2023)**  
7. **Share of Average Youth Unemployment Among Selected Countries (Donut Chart)**  

These charts cover time-series patterns, rankings, regional differences, and global comparisons.

## 5. Public Dashboard Link
Paste your MongoDB Charts public dashboard link here:

**[Dashboard Link](https://charts.mongodb.com/charts-project-0-lixddbm/public/dashboards/d9cc5f5c-9dcf-4e46-9898-ca1bc55051b1#)**

## 6. Key Insights

- Several African and Middle Eastern countries consistently show high youth unemployment.  
- BRICS nations display contrasting patterns: China has low unemployment while South Africa remains high.  
- India experienced rising unemployment until 2019, followed by improvement.  
- The heatmap highlights sudden spikes and year-wise variations.  
- Regional analysis shows improvements in South Asia and East Asia but persistent challenges in Sub-Saharan Africa.  
- The choropleth map reveals global inequality in youth employment opportunities.

## 7. Tools Used
- MongoDB Atlas  
- MongoDB Compass  
- MongoDB Charts  
- Kaggle Dataset  

## 8. Course Information
This project is submitted as part of the DBMS coursework under the guidance of  
**Professor Ashok Kumar Harnal, FORE School of Management**.

