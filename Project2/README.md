# Real Estate Market Analysis in St. Petersburg

This project analyzes historical real estate listings from **Yandex Real Estate**, focusing on properties in St. Petersburg and surrounding areas. The goal is to determine the key factors influencing property prices, identify trends, and establish an automated system to detect anomalies and potential fraudulent activities.

---

## Table of Contents
- [About the Project](#about-the-project)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Project Workflow](#project-workflow)
- [Installation](#installation)
- [Results and Insights](#results-and-insights)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project
The project leverages a dataset containing property listings, including user-provided and automatically generated data, such as proximity to the city center, parks, and other geographic features. This analysis aims to:
- Understand factors influencing real estate prices.
- Identify and handle anomalies and outliers in the data.
- Optimize pricing strategies by understanding market trends.

---

## Objectives
1. Perform exploratory data analysis (EDA) to uncover key patterns.
2. Preprocess data to address missing values, inconsistencies, and duplicates.
3. Engineer new features for enhanced analysis (e.g., price per square meter, proximity in kilometers).
4. Identify the most significant factors affecting property prices.
5. Analyze property sales dynamics and trends.

---

## Dataset
The dataset includes the following columns:
- **Numerical Features**:
  - `total_area`: Total area of the apartment (m²).
  - `living_area`: Living area (m²).
  - `kitchen_area`: Kitchen area (m²).
  - `last_price`: Listing price (currency units).
  - `days_exposition`: Time on the market (days).
  - `cityCenters_nearest`: Distance to city center (m).
- **Categorical Features**:
  - `locality_name`: Name of the locality.
  - `floor`: Apartment floor type (`first`, `last`, or `other`).
- **Boolean Features**:
  - `studio`: Indicates if it is a studio apartment.
  - `is_apartment`: Specifies if it is an apartment.
- **Date Features**:
  - `first_day_exposition`: Date of publication.

For more details, refer to the dataset documentation.

---

## Technologies Used
- **Python**:
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Jupyter Notebook** for analysis and visualization
- **Git** and **GitHub** for version control
- **Markdown** for documentation

---

## Project Workflow
1. **Data Exploration**:
   - Load and inspect the dataset.
   - Visualize distributions of key features.
2. **Data Preprocessing**:
   - Handle missing values and incorrect data types.
   - Remove duplicates and clean categorical data.
3. **Feature Engineering**:
   - Add calculated columns like price per square meter, publication date breakdown, and proximity in kilometers.
4. **Exploratory Data Analysis**:
   - Investigate relationships between features and prices.
   - Study sales dynamics and outliers.
5. **Insights and Conclusions**:
   - Summarize key findings.
   - Highlight recommendations for improving real estate market strategies.

---



