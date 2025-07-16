## GENDATA-CAPSTONE_1
    
# 📚 Kenyan High Schools Dropout and Completion Analysis

## 1. Business Problem / Research Question

This project seeks to answer:

**How have dropout and completion rates among high school students in Kenya evolved over time, and how do these patterns vary by gender, age group, and region?**

By analyzing these patterns, the study aims to identify the most vulnerable student groups and recommend data-driven interventions to improve school retention and policy outcomes.

## 2. Data Sources

### ✅ Kenya National Bureau of Statistics (KNBS)
- **Economic Survey 2024 (Education Section)**  
  Contains yearly enrollment, dropout, and completion stats by gender and region.  
  🔗 [https://www.knbs.or.ke](https://www.knbs.or.ke)

- **Census Analytical Report on Education**  
  Historical context and dropout data by region, gender, and age group.

### ✅ UNESCO Institute for Statistics (UIS)
- Global education indicators on:
  - Dropout rates (secondary)
  - Gross and net enrollment ratios
  - Completion rates
  - Gender disparities  
  🔗 [https://uis.unesco.org](https://uis.unesco.org)

## 3. SQL Database Design

### 🗃️ Tables and Relationships:

#### `regions`
#### `dropout_statistics`
#### `completion_statistics`
#### (Optional) `students` *(if simulating individual data)*

**Relationships:**  
- `dropout_stats.region_id` → `regions.region_id`  
- `completion_stats.region_id` → `regions.region_id`


## 4. SQL Queries (BigQuery or MySQL)

### a) Dropout Rate by Year and Gender

### b) Regional Dropout Comparison

### c) Age Group Dropout Trends


## 5. Tableau Dashboard

### Visualizations :
- Dropout rate by year and gender
- Dropout rate by region
- Dropouts by age group
- Completion trend by gender
- View trends by region, year, and gender


## 6. Stretch goals

###Data Gaps:
- Reasons for dropout (e.g. fees, teen pregnancy, early marriage) are not recorded
- Real-time data is not available — most datasets lag by 1–2 years
- County-level breakdowns could be more detailed

###Future Opportunities:
- Apply machine learning to predict dropout risks using socioeconomic data
- Link to **school infrastructure and teacher availability** data


## Target audience/client
The long-term goal is to support education policymakers, school administrators, and NGOs with actionable insights to improve school retention and re-enrollment programs, particularly for vulnerable students.

    

