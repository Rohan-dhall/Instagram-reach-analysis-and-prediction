# Instagram Reach Analysis and Prediction

## Overview
This project explores the reach of Instagram posts by analyzing user engagement metrics such as likes, comments, shares, and saves. Using Python, various data visualization techniques were applied to uncover insights, and a machine learning model was trained to predict impressions based on user interactions.

---

## Table of Contents
- [Project Description](#project-description)
- [Features and Insights](#features-and-insights)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Results](#project-results)
- [Contributors](#contributors)
- [License](#license)

---

## Project Description
The primary objectives of this project are:
1. To analyze the sources of impressions on Instagram posts (Home, Hashtags, Explore, etc.).
2. To examine relationships between engagement metrics and impressions.
3. To develop a machine learning model capable of predicting the reach of posts.

---

## Features and Insights

### Data Analysis
- Distribution of impressions across various sources.
- Word clouds to analyze trends in captions and hashtags.
- Relationship analysis:
  - Strong correlation between likes and impressions.
  - Saves significantly boost impressions.
  - Comments and shares have minor influence.

### Visualization
- Pie charts to show the percentage of impressions by source.
- Scatter plots with trendlines to examine relationships.

### Machine Learning
- Model: Passive Aggressive Regressor
- Features: Likes, Saves, Comments, Shares, Profile Visits, Follows
- Target: Impressions
- Performance:
  - Mean Squared Error: *[Insert value]*
  - R-squared Score: *[Insert value]*
  - High conversion rate of 41% from profile visits to follows.

---

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `plotly`, `wordcloud`
  - Machine Learning: `scikit-learn`

---

