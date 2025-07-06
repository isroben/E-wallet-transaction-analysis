# 💳 E-Wallet Customer Segmentation & Spending Behavior Analysis

This project analyzes E-Wallet customer data to understand **demographics, spending patterns, and actionable customer segments**, helping the business design smarter marketing strategies, loyalty programs, and upselling campaigns.

---

##  **Dataset**
    https://www.kaggle.com/datasets/datascientistanna/customers-dataset?select=Customers.csv
## **Key Business Questions & Insights**

### **General Demographic Questions**

1️. **Gender Distribution**  
**Q:** What is the gender distribution? Are there more male or female customers?  
**Method:** Countplot.  
**Insight:** Helps target gender-specific campaigns.

2️. **Age Distribution**  
**Q:** What is the age distribution? Which age group uses the E-Wallet the most?  
**Method:** Histogram, age bins.  
**Insight:** Identifies key user age brackets.

3️. **Average Annual Income**  
**Q:** What is the average annual income of E-Wallet users?  
**Method:** Descriptive stats, boxplot.  
**Insight:** Understands purchasing power.

4️. **Family Size**  
**Q:** How is family size distributed? Do large families tend to use the E-Wallet more?  
**Method:** Countplot, average spending score by family size.  
**Insight:** Guides family-based promotions.

---

###  **Spending Behavior Questions**

5️. **Income vs Spending Score**  
**Q:** Is there a relationship between annual income and spending score?  
**Method:** Scatterplot, correlation.  
**Insight:** Do higher earners spend more?

6️. **Age vs Spending Score**  
**Q:** Does age impact spending? Are younger customers spending more?  
**Method:** Scatterplot.  
**Insight:** Identifies age-based spending trends.

7️. **Work Experience vs Spending**  
**Q:** Do more experienced customers spend more or less?  
**Method:** Scatterplot, group averages.  
**Insight:** Finds opportunity for tailored offers.

8️. **Spending by Profession**  
**Q:** Which profession spends the most, on average?  
**Method:** Bar chart.  
**Insight:** Targets high-value professions.

9️. **Income by Profession**  
**Q:** Which profession has the highest average income?  
**Method:** Bar chart.  
**Insight:** Spots segments with spending potential.

---

### **Trend & Segmentation Questions**

10. **Clusters:** Are there noticeable clusters based on income & spending?  
**Method:** K-Means clustering, Elbow/Silhouette method.

11. **High Income, Low Spend:** Which group has high income but low spending? Why?  
**Insight:** Opportunity to design upselling offers.

1️2. **Low Income, High Spend:** Which cluster represents this? How to retain them?  
**Insight:** Suggests loyalty rewards for high-value customers.

1️3. **Family Size vs Spending:** Do larger families spend more?  
**Insight:** Tailors family-focused promotions.

1️4. **Age + Profession:** Are certain age groups in certain professions bigger spenders?  
**Insight:** Builds precise customer personas.
---

## 🗃️ **Tools & Methods**

- **Language:** Python, SQL
- **Libraries:** pandas, numpy, seaborn, matplotlib, scikit-learn
- **Techniques:** EDA, visualization, K-Means clustering, scaling, correlation analysis

---

## 📌 **Impact**

✅ Delivered clear demographic and spending insights to help the company:
- Understand its customer base
- Target valuable segments with promotions & loyalty rewards
- Retain and upsell to underserved high-income groups
- Design data-driven marketing strategies

---

## 📈 **Sample Visualizations**

- Gender & Family Size Countplots  
- Age & Income Distributions  
- Scatterplots (Income vs Spend)  
- Bar charts by Profession  
- Clusters in Income-Spend space  
- Correlation Heatmap

---

## 🚀 **Next Steps**

✅ Deploy as Streamlit dashboard for business users  
✅ Add churn prediction model for retention  
✅ Test real-time segmentation with new customer data

