# Instagram Reach and Engagement Analysis

A data analysis project aimed at understanding the key factors driving Instagram impressions, engagement, and reach. <br>
This project uses real-world data to uncover actionable insights through visualizations and predictive modeling.

---

## Table of Contents
- [Overview](#overview)
- [Project Objectives](#project-objectives)
- [Data Description](#data-description)
- [Analysis and Insights](#analysis-and-insights)
- [Visualizations](#visualizations)
- [Key Findings](#key-findings)

---

## Overview
Social media platforms like Instagram are integral for content creators and marketers to reach their audience. This project analyzes Instagram engagement metrics, reach sources, and content features to provide actionable insights for optimizing post performance.

---

## Project Objectives
- Identify the key metrics that influence Instagram impressions and engagement.
- Analyze the impact of hashtags and caption words on reach.
- Build predictive models to estimate impressions based on likes, saves, shares, and profile visits.
- Provide actionable insights for marketers and content creators.

---

## Data Description
The dataset contains Instagram post metrics, including:
- **Engagement Metrics**: Likes, comments, shares, and saves.
- **Reach Sources**: Impressions from home, hashtags, explore, and other.
- **Content Features**: Captions and hashtags.
- **Derived Metrics**: Engagement rate, save ratio, and follower conversion rates.

The data is located here- https://statso.io/instagram-reach-analysis-case-study/

---

## Analysis and Insights
### Exploratory Data Analysis (EDA)
- Most impressions come from the Home feed, with hashtags being the second-largest contributor.
- Words like 'project' and hashtags like `#python` drive Explore reach significantly.

### Predictive Modeling
- **XGBoost** achieved the highest R² score (0.975) for predicting impressions.
- **Likes** are the most influential feature in determining post impressions.

### Visualizations
- Heatmaps and bar charts illustrate how hashtags and words impact reach sources.

## Key Findings
1. Posts with the hashtag #python receive 20% more impressions from Explore.
2. Captions with the word 'project' increase Home feed visibility by 15%.
3. Likes are the most significant driver of impressions, followed by saves and profile visits.
