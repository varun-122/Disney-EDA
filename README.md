# Disney+ Content Intelligence & Recommendation Analytics

## Project Overview

This project analyzes the Disney+ content catalog using data analytics, business intelligence, and recommendation system techniques to uncover insights into content strategy, audience targeting, catalog freshness, and personalized content discovery.

The project combines:

* Exploratory Data Analysis (EDA)
* Business & Content Strategy Analytics
* Tableau Dashboard Development
* Content-Based Recommendation System
* Collaborative Filtering Recommendation System

The objective is to understand how Disney+ structures its content portfolio and demonstrate how recommendation systems can improve content discoverability and user experience.

---

## Dataset

**Disney+ Movies and TV Shows Dataset**

The dataset contains metadata for Disney+ titles, including:

* Title
* Type (Movie / TV Show)
* Director
* Cast
* Country
* Release Year
* Date Added
* Rating
* Duration
* Genre
* Description

### Engineered Features

Additional features were created to support analytics and recommendation modeling:

* `year_added`
* `month_added`
* `content_age`
* `content_segment`
* `release_lag`
* `audience_segment`
* `genre_count`
* `cast_count`
* `era`

---

## Project Objectives

### Content Analytics

* Analyze Disney+'s content growth strategy
* Evaluate catalog freshness and legacy content dependence
* Identify audience targeting patterns
* Assess geographic content distribution
* Measure content acquisition efficiency

### Recommendation Analytics

* Improve content discoverability
* Reduce search friction
* Generate personalized content recommendations
* Evaluate recommendation relevance and coverage

---

## Key Business Insights

### Catalog Freshness

* 49.7% of titles were classified as Legacy Content (>10 years old)
* 21.1% of titles were classified as New Content (≤2 years old)

### Audience Strategy

* Family-oriented content represents the largest audience segment
* Disney+ maintains strong focus on family entertainment and franchise-driven content

### Seasonal Acquisition Trends

* Content additions peak during specific periods of the year, indicating structured release planning

### Content Acquisition Efficiency

* Release lag analysis revealed a hybrid acquisition strategy combining newly released content with historical catalog additions

---

## Recommendation System

### Content-Based Filtering

Implemented using:

* TF-IDF Vectorization
* Cosine Similarity

Metadata used:

* Genres
* Cast
* Directors
* Descriptions
* Countries

### Collaborative Filtering

Implemented using:

* Pearson Correlation
* K-Nearest Neighbors (KNN)
* Cosine Similarity

Simulation Environment:

* 1,000 synthetic users
* 25,000 user-item interactions
* 1,365 Disney+ titles

### Performance

* Recommendation relevance achieved approximately 80–100% genre-match accuracy
* Recommendation coverage evaluated across the Disney+ catalog

---

## Tableau Dashboard

The Tableau dashboard provides an executive view of Disney+ content strategy and recommendation analytics.

### Dashboard Features

* Content Growth Analysis
* Audience Segmentation
* Catalog Freshness Analysis
* Global Content Footprint
* Content Lifecycle Matrix
* Audience vs Freshness Heatmap
* Recommendation Analytics

---

## Technologies Used

### Programming

* Python

### Data Analysis

* Pandas
* NumPy

### Data Visualization

* Matplotlib
* Seaborn
* Tableau

### Machine Learning

* Scikit-Learn

### Recommendation Systems

* TF-IDF Vectorization
* Cosine Similarity
* Pearson Correlation
* K-Nearest Neighbors (KNN)

---

## Repository Structure

```text
DisneyPlus-Content-Analytics/

├── datasource/
│   └── disney_plus_analytics_final.csv
│
├── notebooks/
│   ├── Disney+_EDA_Recommender_System.ipynb
│
├── tableau_dashboard/
│   └── DisneyPlus_Analytics_Dashboard.twbx
│
├── images/
│   └── dashboard_preview.png
│
└── README.md
```

---

## Business Impact

This project demonstrates how data analytics and recommendation systems can support streaming platforms by:

* Improving content discoverability
* Increasing catalog utilization
* Supporting content investment decisions
* Enhancing audience targeting strategies
* Providing personalized recommendation experiences

---

## Author

Varun Sharma

B.Tech Computer Science Engineering

Aspiring Data Analyst | Data Scientist
