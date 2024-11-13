# InsightFit: Predicting Gym Membership Interest through Personal Data Analysis

## Project Overview
**InsightFit** is a data science project aimed at building a predictive model to estimate interest in long-term gym memberships for a globally recognized gym chain expanding into the Polish market. By analyzing personal attributes such as age, location, hobbies, and social network size, this project seeks to identify the characteristics most indicative of gym subscription interest, providing valuable insights to guide targeted marketing strategies.

## Background
To help inform the gym chain’s market entry and optimize customer acquisition, this study investigates patterns within personal data to predict an individual's likelihood of joining a gym. The goal is to direct advertising efforts effectively by identifying high-potential subscriber profiles and tailoring promotions to maximize impact.

## Data and Methodology
This analysis uses a diverse dataset containing various personal attributes from prospective gym members. The project includes the following key steps:

1. **Exploratory Data Analysis (EDA)**: Visualizations and statistical analyses to uncover initial data patterns and correlations.
2. **Feature Engineering**: Transformation of categorical variables, such as hobbies, into binary features, creating a total of 175 new features. K-means clustering is then used to condense these features into broader hobby categories, enhancing interpretability.
3. **Predictive Modeling**: Three models were employed to predict gym subscription interest:
   - Logistic Regression
   - LightGBM (Gradient Boosting)
   - XGBoost (Gradient Boosting)

   LightGBM achieved the highest recall of 0.75 for identifying interested individuals, making it the top-performing model.

## Findings
The analysis identified several key attributes associated with increased likelihood of gym subscription interest:
- Age (20-30 years old)
- Relationship status (single or in a relationship, but not married)
- Gender (primarily male)
- Area population (cities with populations over 50,000)
- Social network size (approximately 200 friends)
- Daily commute distance and specific interests also correlated strongly with interest in a gym subscription.

These insights suggest that marketing strategies should focus on younger, socially connected individuals in urban areas, who may be naturally inclined to join without additional persuasion.

## Recommendations
To maximize the impact of marketing efforts, this analysis recommends targeting campaigns to individuals fitting the identified profile, particularly in urban centres. Other demographic groups may require more tailored, persuasive messaging to encourage gym membership.

## Future Work
Further improvements to the model could include:
- Hyperparameter optimization and cross-validation for model refinement.
- Enhanced NLP techniques for more nuanced exploration of hobbies and interests.
  
This project demonstrates the value of data-driven insights in crafting targeted customer acquisition strategies and can serve as a foundation for similar predictive marketing efforts.
