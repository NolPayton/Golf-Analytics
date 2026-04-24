# PGA Performance Analysis: What Drives Scoring and Success

## Overview
This project analyzes professional golf performance data to determine which factors most influence scoring and overall success. Using regression analysis and Tableau visualizations, the goal is to move beyond obvious relationships and identify what truly differentiates top-performing players.

---

## Key Questions

1. Is putting or driving more important for scoring?
2. What metrics have the strongest impact on scoring?
3. Do top-performing players share similar performance profiles, or do they excel in specific areas?

---

## Tools Used
- Excel for regression analysis  
- Tableau for data visualization  
- PGA performance dataset including putting, driving, scoring, and earnings  

---

## Key Findings

### Putting vs Driving
The visual analysis shows that putting has a stronger and more consistent relationship with scoring than driving distance. Players with fewer putts per round tend to have lower scoring averages, while driving distance shows a weaker and less differentiating relationship.

### Regression Results
A multiple regression model was used to evaluate the impact of several performance metrics on scoring.

- Average putts per round has the largest impact on scoring and is statistically significant  
- Driving accuracy (drive percentage) is also significant and associated with better scoring  
- Driving distance has a smaller but still meaningful effect  
- One-putt percentage is not statistically significant when other variables are included  

The model has an R² of approximately 0.12, indicating that while these variables matter, most variation in scoring is explained by other factors.

### Top Player Analysis
The highest-earning players were analyzed to determine whether success is driven by specialization or balance. The results show that top players have similar performance across putting, driving accuracy, and distance. Rather than dominating a single category, they maintain strong performance across all key metrics.

This suggests that success at the highest level is driven by a balanced skill set rather than excelling in one area alone.

---

## Conclusions
Putting is the most important driver of scoring performance. Driving contributes to performance, particularly through accuracy, but does not strongly differentiate top players. Overall success appears to come from consistency across multiple areas rather than specialization.

---

## Project Structure
/data – raw dataset  
/analysis – regression outputs  
/visuals – Tableau dashboards  
README.md – project documentation  

---

## Notes
The regression model explains a limited portion of scoring variation, indicating that additional factors such as course conditions, consistency, and tournament context likely play a role.

---

## Author
This project was completed as part of a data analysis and business strategy assignment.
