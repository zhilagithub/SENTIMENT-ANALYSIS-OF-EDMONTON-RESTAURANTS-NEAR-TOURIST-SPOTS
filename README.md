# Sentiment Analysis of Edmonton Restaurants Near Tourist Spots

## Overview

This project analyzes Yelp restaurant reviews to explore how customer sentiment and restaurant ratings relate to proximity to tourist attractions in Edmonton, Canada.

The analysis combines Yelp business and review data with information on 56 Edmonton tourist attractions. It examines 5,573 Edmonton restaurants and 58,539 Edmonton reviews, including 18,792 reviews associated with restaurants near tourist attractions from 2008 to 2021.

The project combines natural language processing, geospatial analysis, statistical analysis, machine learning, and time-series forecasting to identify patterns in customer sentiment and generate insights relevant to restaurant and tourism stakeholders.

## Key Features

- **Sentiment Analysis:** Applied BERT, VADER, and TextBlob to classify sentiment in customer reviews.
- **Geospatial Analysis:** Examined restaurant locations and proximity to Edmonton tourist attractions using geospatial techniques and Folium.
- **Time-Series Forecasting:** Analyzed and forecasted sentiment trends using ARIMA, SARIMA, and Prophet.
- **Feature Engineering:** Created location-based features to investigate the relationship between proximity to attractions and restaurant ratings.
- **Culinary Insights:** Used association rule mining to identify cuisine patterns near tourist attractions.
- **Interactive Visualizations:** Developed maps and visualizations to explore restaurant locations, ratings, and sentiment patterns.

  ## Dataset

- **Yelp Business Dataset:** Contains business information used to identify 5,573 restaurants in Edmonton.
- **Yelp Review Dataset:** Contains 58,539 reviews for Edmonton restaurants used in the analysis.
- **Edmonton Attractions Dataset:** Contains information on 56 tourist attractions used for proximity and geospatial analysis.

## Methodology

### Sentiment Analysis
- **BERT:** Used for contextual sentiment analysis of customer reviews.
- **VADER:** Applied as a lexicon-based sentiment model.
- **TextBlob:** Used as an additional baseline sentiment approach.

### Geospatial Analysis
- Analyzed restaurant proximity to Edmonton tourist attractions.
- Used clustering and interactive maps to explore geographic patterns in restaurant ratings and sentiment.

### Statistical Analysis
- Used Pearson and Spearman correlations to examine relationships between proximity to tourist attractions and restaurant ratings.
- Applied Chi-Square testing to evaluate associations between proximity and higher restaurant ratings.

### Time-Series Forecasting
- Analyzed historical sentiment trends and generated forecasts using ARIMA, SARIMA, and Prophet.
  

## Results

### Sentiment and Location
- Restaurants located closer to tourist attractions showed a positive relationship with higher restaurant ratings.
- Sentiment analysis identified patterns in customer opinions across Edmonton restaurants.

### Cuisine Patterns
- Chinese, Italian, and Indian cuisines were among the most prominent cuisines identified near tourist attractions.

### Forecasting
- Time-series models were used to examine historical sentiment patterns and forecast future sentiment trends.

### Strategic Insight
- The analysis suggests that restaurant location relative to tourist attractions may be associated with customer ratings and review patterns.

 ## Tools & Technologies

- **Python:** pandas, NumPy, scikit-learn
- **NLP:** BERT, VADER, TextBlob
- **Statistical Analysis:** Pearson correlation, Spearman correlation, Chi-Square testing
- **Time-Series Forecasting:** ARIMA, SARIMA, Prophet
- **Geospatial Analysis & Visualization:** Folium
- **Development Environment:** Jupyter Notebook


## Repository Structure

```text
SENTIMENT-ANALYSIS-OF-EDMONTON-RESTAURANTS-NEAR-TOURIST-SPOTS/
│
├── README.md
│
├── data/
│   ├── README.md
│   ├── attractions.csv
│   ├── edmonton_cleaned_business.csv
│   ├── attraction_filtered_reviews.csv
│   └── refined_dataset.csv
│
├── notebooks/
│   ├── README.md
│   ├── 01_business_data_preprocessing.ipynb
│   ├── 02_attraction_data_preprocessing.ipynb
│   ├── 03_review_data_preprocessing.ipynb
│   └── 04_sentiment_modeling_and_forecasting.ipynb
│
└── reports/
    ├── README.md
    ├── final_report.pdf
    ├── literature_review.pdf
    └── sentiment_analysis_presentation.pptx
```
