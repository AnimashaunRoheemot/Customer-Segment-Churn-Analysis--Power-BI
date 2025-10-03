# 🛍 Customer Segmentation & Churn Analysis  

## 📑 Table of Contents  
1. [Project Description](#-project-description)  
2. [Steps Performed](#-steps-performed)  
3. [Business Questions & Insights](#-business-questions--insights)  
   - [Customer Demographic & Behavior Dashboard](#-customer-demographic--behavior-dashboard)  
   - [Product & Sentiment Dashboard](#-product--sentiment-dashboard)  
4. [Visualizations](#-visualizations)  
5. [Skills Demonstrated](#-skills-demonstrated)  
6. [Source of Data](#-source-of-data)  
7. [Recommendations](#-recommendations)  
8. [Conclusion](#-conclusion)  
9. [Author](#-author)  

---

## 📌 Project Description  
This project explores *customer segmentation and churn behavior* using simulated e-commerce data. It aims to uncover *customer insights* from demographics, spending behavior, product preferences, and sentiment analysis.  

The analysis helps answer key business questions such as:  
- Which customer groups contribute the most to revenue?  
- What drives churn vs loyalty?  
- Do product categories influence churn behavior?  
- How do reviews and ratings reflect customer retention?  

Two interactive dashboards were built in *Power BI*:  
- *Customer Demographics & Behavior*  
- *Products & Sentiment*  

Both dashboards feature KPIs, visualizations, and *pop-out slicer menus* for interactivity.  

---

## ⚙ Steps Performed  
1. *Exploratory Data Analysis (EDA)*  
   - Checked for null values  
   - Removed duplicates  
   - Validated data types  

2. *Data Modeling*  
   - Created dimensions for *Gender, Product, Location*  
   - Established relationships between fact and dimension tables  

3. *Measures Created in DAX*  
   - Average Rating  
   - Average Spend  
   - Revenue  
   - Count of Customers  
   - Count of Churned Customers  
   - Count of Loyal (Non-Churn) Customers  
   - Churn Rate  
   - Total Average Spend  

4. *Dashboard Design*  
   - *Demographics & Behavior Dashboard*: KPIs (Customers, Revenue, Avg Spend, Churn Rate)  
   - *Products & Sentiment Dashboard*: Product churn, ratings, sentiment drivers  
   - Added *hidden slicer panel* using bookmarks and buttons  

---

## ❓ Business Questions & Insights  

### 🔹 Customer Demographic & Behavior Dashboard

- **Which age group spends the most on average?**
👉 Customers aged *36–45* have the highest average spend, while the youngest group *(18–25)* spends the least. This highlights the middle-aged group as the most valuable segment for targeted campaigns.![spend vs average](https://github.com/AnimashaunRoheemot/Customer-Segment-Churn-Analysis--Power-BI/blob/main/Screenshot%20(248).png)
-	**Is there a difference in spending behavior between male and female customers?**
👉 Yes. Males account for *₦6.50k (54.2%)* of spend, while females spend *₦5.49k (45.8%)*. This indicates men contribute slightly more to overall revenue, though both genders remain important.![spending vs gender](https://github.com/AnimashaunRoheemot/Customer-Segment-Churn-Analysis--Power-BI/blob/main/Screenshot%20(249).png) 
-	**Which location has the highest number of loyal (non-churn) customers?**
👉 Kano leads with *22* loyal customers, followed by Ibadan with *21*. Loyalty programs can be strengthened in these high-performing cities to increase retention.![loyal vs location](https://github.com/AnimashaunRoheemot/Customer-Segment-Churn-Analysis--Power-BI/blob/main/Screenshot%20(250).png) 
-	**How does purchase frequency relate to customer satisfaction (rating)?**
👉 Customers who purchase *4–6* times per month rate their experience higher *(3.18)* compared to those purchasing only once per month *(2.7)*. This suggests that engaged customers are more satisfied.![purchase vs rating](https://github.com/AnimashaunRoheemot/Customer-Segment-Churn-Analysis--Power-BI/blob/main/Screenshot%20(251).png) 
-	**What percentage of subscribed customers churn vs non-subscribed customers?**
👉 Among churned customers, *50.51%* were non-subscribers while *49.49%* were subscribers. This shows subscription alone does not prevent churn, highlighting a need to improve subscription value.![churn vs subscribe](https://github.com/AnimashaunRoheemot/Customer-Segment-Churn-Analysis--Power-BI/blob/main/Screenshot%20(252).png) 
- **Which segment of customers (loyal, churned) brings the highest revenue?**
👉 Churned customers generate *₦23k (51%)*, slightly more than loyal customers *₦22k (48.9%)*. This indicates that high-value customers are also at risk of leaving, requiring urgent retention strategies.![churn vs revenue](https://github.com/AnimashaunRoheemot/Customer-Segment-Churn-Analysis--Power-BI/blob/main/Screenshot%20(253).png) 

⸻

### 🔹 Product & Sentiment Dashboard
-	**What is the average rating for each product category (Abaya, Scarf, Accessories)?**
👉 Accessories *(33.91%)* slightly outperform Abayas *(33.79%)* and Scarves *(32.3%)*. Ratings are fairly balanced, but accessories lead in customer satisfaction.
-	**Which product category has the highest churn rate?**
👉Accessories *(54.55%)* show the highest churn rate, suggesting issues in quality or customer perception despite high ratings.
-	**Are customers with higher ratings more likely to stay subscribed?**
👉 Surprisingly, no. Among customers giving the highest rating (5), *17* were subscribers while *19* were non-subscribers. High satisfaction does not directly lead to subscription.
- **Is there a correlation between average spend and review rating?**
👉 A negative relationship was observed. Customers with lower ratings spent *₦2.7k* on average, compared to ₦2.2k for higher ratings. Dissatisfied customers often spend more before churning.
- **What are the common keywords in churn-related reviews?**
👉 Sentiment analysis revealed “not worth the price” as the most frequent churn driver, linked to *15* customers. Product quality concerns remain the top issue behind churn.
---

## 📊 Visualizations  

### Customer Demographic & Behavior Dashboard  
![Demographics Dashboard](images/demographic_dashboard.png)  

### Product & Sentiment Dashboard  
![Product Sentiment Dashboard](images/product_sentiment_dashboard.png)  

(Replace the image paths with your actual screenshots from Power BI exports)  

---

## 🛠 Skills Demonstrated  
- Data Wrangling & Cleaning (*Excel, Power Query*)  
- Data Modeling (*Star Schema, Power BI, DAX*)  
- Data Visualization & Dashboard Design (*Power BI*)  
- Exploratory Data Analysis (*EDA techniques*)  
- Business Intelligence & Customer Insights  

---

## 📂 Source of Data  
- The dataset was *simulated using ChatGPT* for learning and practice purposes.  
- It mimics real-world e-commerce data including customer demographics, product categories, purchase frequency, churn status, and sentiment reviews.  

---

## ✅ Recommendations  
- *Customer Retention:* Focus on *Accessories* category to reduce churn.  
- *Target Marketing:* Prioritize *36–45 age group*, the highest spenders.  
- *Subscription Value:* Add stronger benefits to reduce subscriber churn.  
- *Product Improvement:* Address churn drivers around *quality and pricing*.  
- *Engagement Strategy:* Encourage frequent purchases to boost satisfaction.  

---

## 📊 Conclusion  
Customer churn is influenced by *product quality* and *subscription value*. Middle-aged male customers are most profitable, but high spenders are still at risk of leaving.  

Businesses should:  
- Improve *product quality*, especially in accessories  
- Enhance *subscription value proposition*  
- Strengthen *loyalty programs* in Kano and Ibadan  
- Encourage *higher purchase frequency*  

---

## ✍ Author  
*Roheemah Animashaun*  
- Aspiring Data Analyst | Business Intelligence Enthusiast  
- Tools: Power BI, Excel, SQL, Python  
- [LinkedIn Profile](#) | [GitHub Portfolio](#)  

---
