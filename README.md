---

# **Project: House Price Prediction Analysis**

---

![Project Overview](House_Price_Prediction_Analysis_image.jpg)


### **Project Description:**

This project aims to build a predictive model for house prices using a comprehensive dataset that includes various house features and attributes. The key objectives of this analysis are to:

- Understand the relationship between different house features and their impact on prices.
- Provide actionable insights for stakeholders in the real estate market, including:
  - **Homebuyers**
  - **Sellers**
  - **Investors**

By examining the dataset, we aim to uncover patterns and trends that can help:

- Improve pricing strategies.
- Identify key factors influencing property values.
- Enhance decision-making for real estate investments.

---

### **Objectives:**

1. **Data Cleaning:**

   - Address missing values, handle data inconsistencies, and manage outliers to ensure the dataset is accurate and reliable.

2. **Data Visualization:**

   - Create visual representations to explore trends in features such as house area, number of bedrooms, and the presence of amenities, focusing on their impact on house prices.

3. **Correlation Analysis:**

   - Investigate the relationships between various house attributes (e.g., number of bedrooms, area, and location) to identify factors strongly correlated with house prices.

4. **Answering Business Questions:**

   - Provide insights into specific business questions related to house features, pricing trends, and location-based preferences.

5. **Feature Engineering and Data Preparation:**

   - Transform categorical features and normalize numerical data to enhance the performance of the predictive model.

---

### **Dataset Overview:**

The dataset contains detailed information on various attributes of houses, which include:

- **House Features:**
  - **Price:** The selling price of the house.
  - **Area:** Total area of the house in square feet.
  - **Bedrooms:** Number of bedrooms.
  - **Bathrooms:** Number of bathrooms.
  - **Stories:** Number of floors or stories in the house.

- **Amenities and Features:**
  - **Mainroad:** Whether the house is connected to a main road (Yes/No).
  - **Guestroom:** Presence of a guest room (Yes/No).
  - **Basement:** Presence of a basement (Yes/No).
  - **Hot water heating:** Availability of a hot water heating system (Yes/No).
  - **Airconditioning:** Availability of air conditioning (Yes/No).
  - **Parking:** Number of parking spaces available.

- **Location and Furnishing:**
  - **Preferred Area (Prefarea):** Whether the house is located in a preferred area (Yes/No).
  - **Furnishing Status:** Furnishing status of the house (Fully Furnished, Semi-Furnished, Unfurnished).

---

### **Analysis Steps:**

⓵ **Data Cleaning:**
   - Handle missing values, data inconsistencies, and outliers to ensure the quality and reliability of the dataset.

⓶ **Data Exploration:**
   - Explore general trends and feature distributions, focusing on key attributes such as area, number of bedrooms, and amenities.

⓷ **Correlation Analysis:**
   - Use correlation analysis to identify strong relationships between features like house area, number of bedrooms, and house prices.

⓸ **Answer Business Questions:**

   ### **Business Questions:**

   1. What is the average price of houses in preferred areas vs. non-preferred areas?
   2. What is the impact of the number of bedrooms on the house price?
   3. How does the presence of air conditioning affect house prices?
   4. Is there a significant difference in prices between houses with and without basements?
   5. What is the relationship between the total area of the house and its price?
   6. How many houses have guest rooms, and what is their average price?

⓹ **Feature Engineering and Data Preparation:**
   - Encode categorical features (e.g., Mainroad, Guestroom, Prefarea) and normalize numerical features for model training.

---

### **Required Libraries:**

- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**

---
