# FoodHub Order Analysis

## Project Overview

This project analyzes order data from **FoodHub**, a food delivery aggregator service operating in New York. The analysis explores customer ordering patterns, restaurant performance, delivery efficiency, and revenue generation to provide actionable business insights.

**Objective:** Analyze delivery order data to understand demand patterns across restaurants, identify operational inefficiencies, and provide data-driven recommendations to enhance customer experience and business growth.

---

## Dataset

**Source:** FoodHub internal order database  
**Records:** 1,898 orders  
**Time Period:** Restaurant delivery orders in New York  

### Data Dictionary

| Column | Description |
|--------|-------------|
| `order_id` | Unique identifier for each order |
| `customer_id` | ID of the customer who placed the order |
| `restaurant_name` | Name of the restaurant |
| `cuisine_type` | Type of cuisine (American, Japanese, Italian, etc.) |
| `cost_of_the_order` | Total order cost in USD |
| `day_of_the_week` | Weekday or Weekend |
| `rating` | Customer rating out of 5 (or "Not given") |
| `food_preparation_time` | Time (minutes) for restaurant to prepare food |
| `delivery_time` | Time (minutes) for delivery person to deliver order |
---

## Analysis & Key Questions Answered

The analysis addresses the following business questions:

1. **Order Distribution:** How many orders does each restaurant receive?
2. **Cuisine Popularity:** What are the most popular cuisine types?
3. **Order Value:** What percentage of orders cost more than $20?
4. **Revenue Analysis:** What is the net revenue generated based on commission structure?
5. **Customer Ratings:** What proportion of orders receive ratings?
6. **Delivery Performance:** How do delivery times vary between weekdays and weekends?
7. **Operational Efficiency:** What percentage of orders take more than 60 minutes total time?
8. **Restaurant Performance:** Which restaurants receive the highest ratings?

---

## Key Findings

### Customer Behavior
- **Most Popular Cuisines:** American (28%), Japanese (15%), and Italian (13%)
- **Top Restaurants:** Shake Shack, The Meatball Shop, and Blue Ribbon Sushi
- **High-Value Orders:** 29% of orders exceed $20, generating higher commission

### Operational Insights
- **Missing Ratings:** 28.6% of orders lack customer ratings
- **Delivery Times:** Weekend deliveries average 22 minutes vs. 28 minutes on weekdays
- **Long Wait Times:** 10.5% of orders take more than 60 minutes (prep + delivery)

### Revenue
- **Total Net Revenue:** $6,166.30 across all orders
- **Commission Structure:** 25% on orders >$20, 15% on orders >$5

---

## Business Recommendations

### 1. Improve Feedback Collection
- Implement incentives (loyalty points, discounts) for customers who leave ratings
- Send automated rating reminders immediately after delivery
- **Impact:** Better understanding of customer satisfaction and service quality

### 2. Optimize Weekday Operations
- Investigate root causes of slower weekday deliveries despite lower order volume
- Add more delivery personnel during peak weekday hours
- Implement route optimization algorithms
- **Impact:** Reduce delivery times by 20%, improve customer satisfaction

### 3. Targeted Marketing Campaigns
- Weekend promotions for American and Japanese cuisine
- Incentivize high-value orders with "Spend $25, Get Free Delivery" offers
- Partner with top-performing restaurants for exclusive deals
- **Impact:** Increase average order value and weekend revenue

### 4. Restaurant Partnership Optimization
- Work with slow-prep-time restaurants to streamline kitchen operations
- Provide training or resources to improve food preparation efficiency
- Consider removing consistently slow restaurants from the platform
- **Impact:** Reduce total delivery time, fewer customer complaints

### 5. Loyalty Program Development
- Create tiered membership rewards for frequent customers
- Offer exclusive perks to "Gold Members" (e.g., priority delivery)
- **Impact:** Increase customer retention and lifetime value

---

### Analytical Techniques
- **Descriptive Statistics:** Mean, median, percentages, distributions
- **Grouping & Aggregation:** Restaurant performance, cuisine analysis, weekday/weekend comparison
- **Custom Functions:** Revenue calculation based on commission tiers
- **Data Visualization:** Bar charts, histograms, grouped comparisons

---

## 📧 Contact

**Ivy Amexo**  
Data Analyst | Aspiring Data Scientist  
📧 amexoivy22@gmail.com
🔗 https://www.linkedin.com/in/ivyamexo/ 
💼 https://github.com/Vee-108611/Food_Hub_Analysis_Project

---

## License

This project is for educational and portfolio purposes.

---

## Acknowledgments

- Dataset provided by FoodHub (simulated data for analysis)
- Analysis conducted as part of data science training and skill development
