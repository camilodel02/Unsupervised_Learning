# 🛒 InstaCart Recommendation System: Market Basket Analysis & Clustering
This project applies data analysis techniques—Association Rules and Clustering—to optimize product recommendation strategies for both online and physical retail environments. The dataset used is the public Instacart 2017 dataset, consisting of over 1.3 million records.

## 🎯 Business Objectives
Identify frequently co-purchased products to guide shelf placement and digital recommendations.

Tailor recommendations for online vs. in-store shopping experiences.

Segment users into behavioral clusters to enable targeted marketing.

# 🔍 Project Overview
## 🧠 1. Business Understanding
- Performed a strategic assessment of the grocery retail market using:
- PESTLE Analysis (Political, Economic, Social, Technological, Legal, Environmental)
- Porter’s Five Forces
- SWOT Analysis (Strengths, Weaknesses, Opportunities, Threats)
- These helped contextualize customer preferences and identify opportunities to improve product recommendation systems.

## 📊 2. Data Understanding
The dataset includes:
- Customer IDs, Order IDs, Product IDs
- Order sequences (first, second... etc.)
- Day of the week and time of purchase
- Product department/category info
-Performed cleaning, transformation, and exploratory analysis before modeling.

## 🧪 Modeling Techniques
### 📌 Association Rule Mining (Apriori Algorithm)
Used to uncover frequent itemsets and product combinations.

Metrics evaluated: Support, Confidence, and Lift

Applied minimum thresholds of:
- Support > 1%
- Confidence > 1%

### 📌 Clustering (K-Means)
Used to segment users based on:

- Order frequency
- Time of day/week
- Product types/categories
- Features were normalized prior to applying the algorithm.
- Elbow method used to determine optimal number of clusters (k).

## 📈 Results
🧾 Association Rules (Apriori)
Common product combinations discovered:
- Bananas & Organic Strawberries
- Whole Milk & Eggs
High-lift rules identified actionable opportunities for:
- Bundle Promotions
- Product Placement
- Cross-sell strategies

## 👥 K-Means Cluster Summaries
* Group 0: Monthly shoppers (mostly Mondays) with consistent orders focused on dairy, drinks, cleaning, and personal care. Recommend monthly bundles.
* Group 1: Frequent snack buyers (mostly Thursdays, 8–11 a.m.), with high reorder rates. Suggest launches and promotions for Thursday mornings.
* Group 2: Diverse shoppers (Fridays), mix of weekly/monthly habits, focus on fresh lunch products. Recommend lunch combos for Fridays/weekends.
* Group 3: Irregular buyers with no fixed pattern. Purchases vary in time and frequency. Suggest surprise reactivation messages and rewards.
* Group 4: Morning shoppers (Wednesdays), with generalist behavior and mid-week purchases. Recommend promotions and personal care combos.
* Group 5: Health-conscious buyers focusing on fruits and vegetables. Suggest seasonal fresh produce combos and delivery flexibility.

Each segment allows for tailored promotion and communication strategies, increasing personalization and customer satisfaction.

# References
The project is from Kaggle and it can be found [here](https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset)
