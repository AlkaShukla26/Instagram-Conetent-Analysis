# Instagram Content Strategy Analysis 📊

## Overview
This project analyzes Instagram content performance to identify **which content categories drive real follower growth** versus those that generate engagement without long-term impact.  
The goal is to move beyond vanity metrics (likes, reach) and provide **data-backed content strategy recommendations**.

The analysis focuses on:
- Engagement consistency
- Follower conversion efficiency
- Quality of engagement (likes vs saves vs shares)
- Clear “Start / Stop” content decisions

---

## Dataset
- Platform: Instagram  
- Granularity: Post-level data  
- Key fields:
  - content_category  
  - impressions  
  - likes, comments, saves, shares  
  - followers_gained  
  - account_id  

All analysis is performed using **SQL (BigQuery)** and executed in **Google Colab**.

---

## Key Metrics Defined
- **Engagement** = likes + comments + saves + shares  
- **Followers per 1K Impressions** = (followers_gained / impressions) × 1000  
- **Engagement Consistency** measured using **Coefficient of Variation (CV)**  
- **Engagement Quality** assessed via saves and shares (value-driven signals)

---

## Analysis Performed

### 1. Consistency vs Virality
- Measured engagement volatility across content categories
- Identified categories that are **reliable and scalable** vs **spike-driven**
- Key insight: High average engagement can hide high volatility

### 2. Follower Conversion Efficiency
- Normalized follower growth using followers per 1K impressions
- Benchmarked categories against the overall platform average
- Highlighted which categories actually convert reach into followers

### 3. Engagement Quality Analysis
- Compared likes, comments, saves, and shares across categories
- Found that likes and comments are largely uniform
- **Saves and shares show stronger alignment with follower growth**

### 4. “Stop Doing” Analysis
- Identified categories with **below-average follower conversion**
- These categories consume impressions and effort without proportional growth

### 5. “Start / Double Down” Analysis
- Identified categories that **outperform the average on the same metrics**
- Ensured symmetry and fairness in decision-making

---

## Final Recommendations

### ✅ Start / Scale
These categories consistently convert impressions into followers:
- **Music**
- **Lifestyle**
- **Food**
- **Beauty**
- **Fitness**

### 🛑 Stop / Deprioritize
These categories show strong engagement but weak follower conversion:
- **Photography**
- **Travel**
- **Technology**
- **Comedy**
- **Fashion**

---

## Key Takeaways
- Engagement ≠ Growth  
- Likes are weak predictors of follower acquisition  
- **Value-driven engagement (saves & shares) matters most**
- Content strategy should prioritize **conversion efficiency and consistency**, not virality

---

## Tools & Technologies
- SQL (BigQuery)
- Google Colab
- Pandas
- Data-driven decision frameworks

---

## Project Value
This project demonstrates:
- Strong SQL and analytical thinking
- Ability to define meaningful metrics
- Business-oriented decision-making
- Clear translation of data insights into actionable strategy

---

## Future Enhancements
- Account-level strategy personalization
- Time-based performance decay analysis
- A/B testing framework for content formats
- Predictive modeling for follower growth

---

## Author
**Alka Shukla**  
Aspiring Product & Data Analyst  

