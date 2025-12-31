# Instagram Influencer Analysis & Prediction

## Overview
This project analyzes Instagram influencer data to understand what factors contribute to higher engagement and influence. Social media metrics such as followers, likes, and engagement rate were explored to identify patterns and relationships. Machine learning models were also applied to predict influencer impact and categorize influencers based on their influence level.

---

## Objective
The main objectives of this project are:
- To analyze engagement patterns among Instagram influencers  
- To understand the relationship between followers and engagement rate  
- To identify factors influencing overall influence score  
- To predict influence score using regression models  
- To classify influencers into Low, Medium, and High influence categories  

---

## Dataset
- **Source:** Top Instagram Influencers Dataset  
- **Records:** Several thousand influencer profiles  
- **Key Columns:**
  - Followers  
  - Average Likes  
  - Engagement Rate (60-day)  
  - Influence Score  
  - Country  

The dataset contained abbreviated values (K, M, %) which required conversion into numeric format before analysis.

---

## Approach
The project was completed using the following steps:
1. Loaded and inspected the dataset  
2. Cleaned social media metrics by converting K, M, and % values  
3. Handled missing values  
4. Performed exploratory data analysis using visualizations  
5. Selected relevant features for modeling  
6. Built regression and classification models  
7. Evaluated model performance and interpreted results  

---

## Analysis & Insights
- Higher follower count does not always result in higher engagement  
- Engagement rate plays a significant role in determining influence  
- Influencers are unevenly distributed across countries  
- Machine learning models can reasonably estimate influencer impact  

---

## How to Run
```bash
pip install -r requirements.txt
python instagram_analysis.py
