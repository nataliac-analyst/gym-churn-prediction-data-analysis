# gym-churn-prediction-data-analysis
This project analyzes customer churn in a fitness club using exploratory data analysis and visualization techniques. The objective is to identify patterns and factors associated with membership cancellation in order to support retention strategies. Tools used: Python, Pandas, Seaborn, Matplotlib, Scikit-learn.

## Project Overview

Customer retention is one of the most important challenges for gyms and fitness clubs. This project explores a dataset of gym members to identify behavioral patterns associated with customer churn.

The analysis includes:

- Data exploration and cleaning
- Descriptive statistics
- Comparison between customers who stayed and those who canceled their membership
- Visualization of behavioral patterns
- Insights for improving retention strategies

  ## Dataset

The dataset contains information about gym members including:

- Promotional offers used (Promos)
- Membership duration
- Customer lifetime
- Visit frequency
- Participation in group classes
- Proximity to the gym location
- Churn status (whether the member canceled the membership)

  ## Results

### Classification Models

Two supervised classification models were developed to predict customer churn (subscription status as the target variable).

The models included:

- Logistic Regression
- Random Forest

Both models achieved strong predictive performance, with **recall values above 0.80**, indicating a high capacity to correctly identify members at risk of canceling their membership.

## Customer Segmentation Unsupervised learning

Using an unsupervised clustering model, gym members were segmented into five behavioral groups.

**Cluster 0 – Loyal long-term members**
Older members who live close to the gym and rarely use promotions. They show the lowest churn rate (~0.5%).

**Cluster 1 – Promotion-driven loyal members**
Members who frequently use promotional codes and maintain long membership lifetimes.

**Cluster 2 – Corporate members living far away**
Members coming from corporate partnerships who live far from the gym and show higher churn levels.

**Cluster 3 – Young members with high churn**
The youngest group with the highest churn rate and the lowest participation in group classes.

**Cluster 4 – Long-contract loyal members**
Members using promotional codes who tend to choose longer contracts and remain loyal.

## Business Insights and Recommendations

The analysis identified three key factors associated with customer retention:

- Proximity to the gym
- Promotional partnerships
- Participation in group classes

While Clusters 0, 1 and 4 already show strong loyalty, retention strategies should focus on Clusters 2 and 3.

Recommended strategies include:

- **Engagement programs for younger members**, such as fitness challenges or attendance rewards.
- **Corporate wellness initiatives** for members coming from partner companies who live far from the gym.
- Incentives that encourage **participation in group classes**, as this behavior correlates strongly with long-term membership retention.
