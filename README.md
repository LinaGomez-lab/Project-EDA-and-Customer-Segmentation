## **Project Description**

### **Context:**

The number of restaurants in New York is steadily increasing, catering to students and busy professionals with hectic lifestyles. Online food delivery services offer a convenient solution, providing access to meals from favorite restaurants. FoodHub, a food aggregator company, facilitates this by offering a single app that connects customers with multiple restaurants.

Through the app, restaurants receive direct online orders from customers. Upon order confirmation, a delivery person is assigned to pick up the food. The delivery person uses the app and a map to navigate to the restaurant waits for the food, and then delivers it to the customer. After delivery, the customer can rate the order. FoodHub earns revenue by taking a fixed margin from each delivery order processed through the app.

### **Project Objective:**

The food aggregator company has stored data on various orders made by registered customers through their online portal. They aim to analyze this data to understand restaurant demand better and enhance the customer experience.

In this project, we are employing market segmentation strategies to identify the most effective methods for attracting new customers and orders, and driving business growth.

### **Business Goal:**
"Increase customer acquisition by 15% and customer loyalty by 10% over the next 3 months by implementing targeted marketing campaigns and launching a loyalty program, to contribute to overall revenue growth".


### **Data Description:**

The dataset includes 1,898 food orders placed by 1,200 unique customers in New York City. These orders were made on weekdays, weekends, or both, covering 14 different cuisine types and involving 178 restaurants.

#### **Data Dictionary:**

* order_id: Unique ID of the order
* customer_id: ID of the customer who ordered the food
* restaurant_name: Name of the restaurant
* cuisine_type: Cuisine ordered by the customer
* cost_of_the_order: Cost of the order
* day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
* rating: Rating given by the customer out of 5
* food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
* delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

### **Data Analysis Strategy:**
To conduct a segmentation and targeting analysis, we need to create a customer dataset that identifies key variables such as consumer consumption patterns, frequency of orders, and the top 10 or top 5 cuisine types and restaurants. Additionally, we will analyze how these factors relate to reported food preparation times, delivery times, and customer ratings.

## Summary of Results and Analysis 📈:

1. **Market Overview**

    * Order Distribution: Over 71% of FoodHub’s orders occur on weekends, indicating a strong weekend market presence.
    * Delivery Times: Longer delivery times during weekdays are a significant source of dissatisfaction, potentially affecting customer retention and revenue generation.

2. **Customer Segmentation**

    * Group 1 (Regular Weekend & Weekday Buyers - 57%): This group is the primary revenue driver and shows stable preferences for specific cuisines and restaurants. They contribute significantly to revenue and are crucial to focus on for retention strategies.
    * Group 2 (Weekend One-Timers - 29%): This group has growth potential. They are primarily weekend buyers and could be incentivized to increase their order frequency or spend through targeted marketing and loyalty programs.
    * Group 3 (Weekday Singles - 12%): This segment presents challenges due to lower engagement but offers potential for growth. Addressing weekday delivery times and offering tailored promotions could help in expanding this segment's market presence.

3. **Revenue Drivers**

    Order Size: Orders of $20 or more significantly boost revenue. Implementing loyalty programs and exclusive offers for high-value orders can enhance revenue generation.
    Cuisine and Restaurant Preferences: A higher variety in cuisine types and restaurants positively correlates with revenue. Expanding the range of partners and improving customer experiences with preferred options can drive additional revenue.

4. **Strategic Recommendations**

    * Loyalty Programs: Focus on groups 1 and 2 with loyalty programs designed to increase orders of $20 or more. Tailored rewards and incentives can boost repeat business and average order value.
    * Delivery Time Optimization: Improve weekday delivery times to enhance customer satisfaction, particularly for Group 3, which has potential for growth with better service.
    * Expansion of Quality Partnerships: Increase the number of high-quality restaurant partners to appeal to diverse customer preferences and drive more orders.
    * Attraction Campaigns: Develop targeted marketing campaigns to attract new customers across all segments, with specific promotions to engage Group 2 and Group 3 effectively.

5. **Conclusion**

  The majority of revenue comes from Group 1, making it essential to retain and engage this segment. Group 2 offers significant growth opportunities with targeted strategies, while Group 3 could be developed by addressing delivery times and offering tailored promotions. Overall, expanding quality partnerships, optimizing delivery times, and leveraging loyalty programs are key to driving sustained revenue growth.


  ## **Business Report 📰:**
A report summarizing the main results can be found at the following link: [Business Report](https://infograph.venngage.com/pl/Ym074wQ9ZQ)
