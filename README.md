# Golf-Analytics
# 📊 PGA Performance Analysis: What Drives Scoring & Success

## 📌 Overview
This project analyzes professional golf performance data to determine what factors most influence scoring and overall success. Using regression analysis and Tableau visualizations, the goal is to move beyond obvious relationships and identify what truly differentiates top-performing players.

---

## 🎯 Key Questions

### 1. Is putting or driving more important for scoring?
Compare the relationship between putting, driving distance, and scoring performance.

### 2. What metrics impact scoring the most?
Use regression analysis to determine which variables have the strongest effect on scoring.

### 3. Do top-performing players share similar performance profiles?
Analyze the highest-earning players to determine whether success is driven by specialization or a balanced skill set.

---

## 🛠️ Tools Used
- **Excel** → Multiple regression analysis  
- **Tableau** → Data visualization and comparison  
- **Dataset** → PGA player performance metrics (putting, driving, scoring, earnings)

---

## 📈 Key Findings

### 🟢 Putting vs Driving
- Putting shows a **stronger and more consistent relationship** with scoring  
- Driving distance has a **weaker and less differentiating impact**  
- Lower putts per round are associated with better scoring outcomes  

---

### 🔵 Regression Results (Full Model)
Using a multiple regression model including all key variables:

- **Avg Putts Per Round (Strongest Impact)**  
  - Largest coefficient (+0.205)  
  - Highly significant  
  - More putts → higher (worse) scores  

- **Driving Accuracy (Drive %)**  
  - Significant negative relationship (-0.045)  
  - Higher accuracy → better scores  

- **Driving Distance**  
  - Smaller but significant effect (-0.029)  
  - Contributes to performance, but less than accuracy  

- **One-Putt Percentage**  
  - Not statistically significant  
  - Limited impact when other variables are considered  

📌 Model Performance:  
- **R² ≈ 0.1186**  
- Indicates that while these variables matter, **most variation in scoring is explained by other factors**

---

### 🟡 Top Player Insight (Question 3)
- The highest-earning players show **very similar performance across key metrics**
- No single player dominates one category  
- Instead, they demonstrate a **balanced skill set across putting, accuracy, and distance**

👉 **Key Insight:**  
Success at the highest level is not driven by excelling in one area, but by maintaining consistent performance across all aspects of the game.

---

## 🧠 Final Takeaways
- Putting is the **most important driver** of scoring  
- Driving matters, but is **less impactful and less differentiating**  
- A **balanced performance profile** is key to success  
- Core metrics explain only part of performance—other factors also play a major role  

---


---

## 📌 Notes & Limitations
- The regression model has a relatively low R², meaning results should be interpreted with caution  
- Additional variables (course difficulty, consistency, tournament conditions) could improve the model  
- Findings are based on aggregate player data and may not capture situational performance  

---

## 👤 Author
Data analysis project focused on applying statistical and visualization tools to real-world performance insights.
