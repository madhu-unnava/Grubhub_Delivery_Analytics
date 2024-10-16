# 💼 Grubhub Analytics Project

This project focuses on a comprehensive analysis of Grubhub’s restaurant data to answer key business questions and provide actionable insights for improving delivery times, customer satisfaction, and operational efficiency. Using a wide range of analytical methods, including statistical analysis, clustering, regression, and machine learning models, this project aims to offer strategic recommendations for Grubhub's growth and service optimization.

## 📝 Project Overview

The Grubhub Analytics Project leverages various data science techniques to address critical research questions, helping Grubhub refine its pricing model, improve delivery efficiency, and enhance customer satisfaction. The dataset sourced from Kaggle provides insights into delivery times, customer ratings, subscription-based orders, cuisine preferences, and more.

### Key Objectives:
- **Delivery Time Analysis**: Investigate Grubhub's delivery performance across states and compare it to restaurant self-delivery services.
- **Subscription Order Frequency**: Analyze differences in order frequency between Grubhub Plus subscribers and non-subscribers to identify potential incentives.
- **Cuisine Popularity**: Identify the most popular cuisines by state and recommend targeted marketing strategies.
- **Delivery Time and Rating Correlation**: Examine how delivery time affects customer ratings and how service fees influence both.
- **Geographical Impact**: Analyze how distance from the restaurant affects delivery times, fees, and customer satisfaction.
- **Machine Learning Models**: Explore the potential of clustering and classification models to predict cuisine popularity and optimize marketing efforts.

### Key Variables:
- **Delivery Time**: The time taken for each order to be delivered.
- **Cuisine Type**: The type of cuisine offered by the restaurant (e.g., American, Asian).
- **Review Rating**: Average customer ratings provided for each order.
- **Service and Delivery Fees**: Charges incurred for each order.
- **Geographical Data**: Latitude, longitude, city, and state information for mapping and analysis.

## 🧑‍💻 Methodology

- **Data Extraction:** The dataset was extracted from relevant sources and imported into a Jupyter Notebook environment for further processing.
- **Data Cleaning and Preparation:** The dataset underwent cleaning to handle missing values, remove duplicates, and correct data inconsistencies. Additional features were engineered, such as categorizing cuisine types and grouping delivery times for better analysis.
- **Data Transformation:** Transformations were applied to ensure the dataset was in an analysis-ready format. This included feature engineering and restructuring data to enhance its usability for subsequent analyses.

### Analytical Methods Used:

- **Descriptive Statistics**:
  - Used to summarize delivery times, review ratings, and order frequencies across states and subscription statuses.
  - **Tools**: Python (`Pandas`, `NumPy`), R, and Excel.
- **ANOVA (Analysis of Variance)**:
  - Applied to determine whether there are statistically significant differences in delivery times across various states.
  - **Tools**: Python (`SciPy`), R.
- **Regression Analysis**:
  - Performed to explore the relationship between geographical distance (latitude and longitude) and delivery times, as well as service fees.
  - **Tools**: Python (`scikit-learn`), R, GeoPandas for geospatial analysis.
- **Clustering**:
  - Applied clustering models to group regions and customer types based on cuisine preferences, providing valuable insights for targeted marketing.
  - **Tools**: Python (`scikit-learn`, `KMeans`), R.
- **Time Series Analysis**:
  - Used time series analysis to identify patterns in delivery delays over time, particularly during peak hours.
  - **Tools**: Python (`statsmodels`), R (`tsibble`, `forecast`).
- **Correlation and Hypothesis Testing**:
  - Conducted correlation analysis to investigate relationships between delivery times, customer ratings, service fees, and delivery fees.
  - **Tools**: Python (`Pandas`, `SciPy`), R (`correlation`, `t-tests`).
- **Machine Learning Models**:
  - Implemented classification models (e.g., decision trees, random forests) to predict cuisine popularity and inform restaurant partnerships.
  - Applied clustering techniques to segment regions based on delivery times and cuisine preferences.
  - **Tools**: Python (`scikit-learn`, `TensorFlow`), R (`caret`).

## 📈 Results

### Delivery Time Insights:
- Grubhub outperforms restaurant self-delivery services by 10-24 minutes on average.
- Certain states, such as New York and New Jersey, experience significant delays during peak hours, highlighting the need for optimized resource allocation.

### Subscription Order Insights:
- Subscribers order more frequently than non-subscribers, indicating opportunities to enhance loyalty through exclusive deals and personalized recommendations.

### Cuisine Popularity:
- American cuisine is the most ordered in most states, with Asian cuisine being highly popular in New Jersey. This presents opportunities for localized marketing campaigns.

### Correlation Analysis:
- A positive correlation was found between delivery times and customer ratings; shorter delivery times tend to result in higher ratings.
- Longer distances increase delivery times but do not always correlate strongly with higher service fees, suggesting opportunities for dynamic pricing optimization.

### Clustering Insights:
- Clustering analysis revealed distinct regional preferences for certain cuisines, guiding marketing and restaurant partnership strategies.

## 🛠️ Recommendations

- **Optimize Delivery Routes**: Implement predictive analytics for route optimization, especially in cities like New York where peak-hour traffic causes significant delays.
- **Subscription Campaigns**: Target non-subscribers with promotions that emphasize the benefits of subscribing to Grubhub Plus, leveraging data from subscriber behavior analysis.
- **Cuisine-Specific Promotions**: Use cuisine clustering insights to run targeted marketing campaigns that promote popular local cuisines.
- **Dynamic Pricing**: Introduce dynamic pricing based on delivery distance, traffic conditions, and peak demand to better match fees with service quality.
- **Machine Learning for Cuisine Prediction**: Utilize classification models to predict high-demand cuisines in specific regions and onboard new restaurant partners accordingly.

## 🚀 Future Work

- **Advanced Machine Learning Models**: Further develop classification and clustering models to refine cuisine prediction and restaurant onboarding strategies.
- **Enhanced Time Series Forecasting**: Use time series models to predict future delivery trends, helping Grubhub plan for high-demand periods.
- **Backtesting**: Perform extensive backtesting of pricing strategies and delivery models to validate findings and improve operational efficiency.
