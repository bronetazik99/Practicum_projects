# Video Game Sales Analysis Project

## Introduction

The video game industry has experienced remarkable growth over the years, driven by rapid advancements in technology, the proliferation of gaming platforms, and increasing consumer engagement. For companies like **Streamchik**, a global online store for video games, staying ahead of the competition means understanding what makes a game successful and leveraging this knowledge to drive sales.

This project is an in-depth analysis of historical video game sales data to uncover trends and insights that can guide **Streamchik's** strategy. By examining the relationships between game attributes—such as genre, platform, and ratings—and their sales performance, this project aims to identify key patterns and actionable recommendations. The ultimate goal is to help the company prioritize potential bestsellers and plan impactful marketing campaigns for the year 2017.

While the analysis focuses on preparing for 2017, the methodology and findings can be adapted for broader applications, including predicting future trends and optimizing marketing strategies for subsequent years.

---

## Objectives

The main objectives of this project are:

1. **Discover Key Patterns**:
   - Analyze the factors that contribute to a video game's success.
   - Understand how game genres, platforms, and ratings influence sales performance.

2. **Prioritize Bestsellers**:
   - Use data insights to identify potential top-performing games.
   - Assist in product selection for the 2017 lineup.

3. **Strategic Marketing**:
   - Plan effective advertising campaigns using region-specific insights.
   - Tailor marketing strategies to target audiences based on preferences and behaviors.

---

## Dataset Description

The dataset used in this analysis contains historical data on video game sales, user ratings, critic scores, and other attributes. Below are the key columns:

- **Name**: Name of the video game.
- **Platform**: The platform on which the game was released (e.g., Xbox, PlayStation).
- **Year_of_Release**: The year the game was released.
- **Genre**: The genre of the game (e.g., Action, Sports).
- **NA_sales**: Sales in North America (in millions of copies).
- **EU_sales**: Sales in Europe (in millions of copies).
- **JP_sales**: Sales in Japan (in millions of copies).
- **Other_sales**: Sales in other regions (in millions of copies).
- **Critic_Score**: Critics’ rating of the game (out of 100).
- **User_Score**: Users’ rating of the game (out of 10).
- **Rating**: ESRB rating categorizing games by age-appropriateness (e.g., “E for Everyone,” “T for Teen”).

> **Note**: Data for 2016 may be incomplete.

---

## Project Workflow

The project is divided into the following steps:

### 1. Data Preprocessing
   - Cleaning and transforming data to handle missing values and inconsistencies.
   - Adjusting data types and addressing specific issues, such as 'tbd' in user scores.

### 2. Exploratory Data Analysis (EDA)
   - Analyzing trends in game releases and sales over time.
   - Identifying top-performing platforms and their sales dynamics.
   - Exploring the relationship between ratings (user and critic) and sales.
   - Evaluating the profitability of various game genres.

### 3. Regional Analysis
   - Profiling user preferences in North America, Europe, and Japan.
   - Analyzing regional popularity of platforms and genres.
   - Examining the impact of ESRB ratings on regional sales.

### 4. Hypothesis Testing
   - Testing if average user ratings for Xbox One and PC games are equal.
   - Testing if average user ratings differ significantly between Action and Sports genres.

### 5. Conclusion
   - Summarizing findings and providing actionable recommendations for 2017 marketing strategies.

---

## Deliverables

1. **Key Insights**:
   - Patterns and trends in video game sales.
   - Characteristics that contribute to a game’s success.

2. **Actionable Recommendations**:
   - Targeted marketing strategies tailored to regional and platform-specific preferences.
   - Suggestions for prioritizing best-selling games in 2017.

3. **Technical Outputs**:
   - Cleaned and preprocessed dataset.
   - Visualizations and reports summarizing findings.
   - Hypothesis test results supporting data-driven conclusions.
