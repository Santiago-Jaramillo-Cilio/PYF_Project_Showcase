# **FoodHub Order Analysis**

## **Context**
As the number of restaurants in New York increases, the demand for online food delivery services grows rapidly. Students and busy professionals often rely on these services due to their hectic schedules. FoodHub, a food aggregator, provides access to a wide variety of restaurants through a single smartphone app, streamlining the process of ordering and delivering food.

The app allows restaurants to receive direct online orders from customers, and FoodHub assigns delivery personnel to pick up and deliver these orders. The delivery person uses the app to track the order, confirm pick-up and delivery, and the customer can rate their experience. FoodHub earns revenue by collecting a fixed margin from restaurants for each order.

## **Objective**
As part of the Data Science team at FoodHub, I have been tasked with analyzing the data from the company’s online portal. The goal is to uncover insights regarding customer demand across different restaurants, which will help the company improve its services and overall customer experience.

## **Data Description**
The dataset contains detailed information about food orders placed through the FoodHub app. Each order includes multiple attributes related to the customer, restaurant, and delivery process.

### **Data Dictionary:**
- **`order_id`**: Unique ID of the order.
- **`customer_id`**: ID of the customer who placed the order.
- **`restaurant_name`**: Name of the restaurant.
- **`cuisine_type`**: Type of cuisine ordered by the customer.
- **`cost`**: Total cost of the order.
- **`day_of_the_week`**: Indicates whether the order was placed on a weekday (Monday-Friday) or weekend (Saturday-Sunday).
- **`rating`**: Rating (out of 5) given by the customer for the order.
- **`food_preparation_time`**: Time taken by the restaurant to prepare the food (in minutes).
- **`delivery_time`**: Time taken by the delivery person to deliver the food package (in minutes).

## **Analysis Goals**
The analysis aims to address the following key questions:
- 📅 **What are the busiest days for food orders?**
- 🍽️ **Which restaurants and cuisine types are most popular?**
- ⭐ **What is the relationship between order ratings, preparation time, and delivery time?**
- 💵 **Are there any noticeable trends in the cost of orders based on the day of the week or cuisine type?**

## **Conclusion**
This analysis aims to provide actionable insights to FoodHub, helping the company enhance its customer experience and streamline operations in a competitive online food delivery market.
