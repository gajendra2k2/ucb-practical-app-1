# ucb-practical-app-1
Repo for using ML Models to determine "Will a customer accept the coupon?"

---

## Notebook

You can view the full analysis in the Jupyter Notebook here:

📓 [Coupon Acceptance Analysis Notebook](assignment5_1_starter_prompt.ipynb)

---

## Files Included
- `assignment5_1_starter_prompt.ipynb`: Notebook with data exploration and visualization
- `data/coupuns.csv`: Dataset used in analysis
- `README.md`: This nontechnical summary report

---

# Coupon Acceptance Analysis - Summary Report

## Overview

This brief report summarizes key differences between customers who **accepted** coupons and those who **did not**, based on our exploratory data analysis of driving and demographic attributes.

The goal of this project is to uncover behavioral and contextual patterns that influence whether a customer accepts a coupon offer while driving.

---

## Key Differences Between Acceptors and Non-Acceptors

### 1. **Time of Day**
- **Accepted**: Most coupons were accepted during **2PM to 6PM**.
- **Not Accepted**: A higher number of rejections occurred during **morning hours (7AM–10AM)**.

### 2. **Destination Purpose**
- **Accepted**: More likely when the destination was labeled as **“No Urgent Place”**, suggesting flexibility in plans.
- **Not Accepted**: Lower acceptance when heading to **urgent or specific destinations**.

### 3. **Companion Type**
- **Accepted**: Often alone or with **friends**.
- **Not Accepted**: More rejections when traveling with **partner or kids**, possibly due to less spontaneity.

### 4. **Weather and Temperature**
- **Accepted**: Slightly higher acceptance on **sunny days** with moderate temperatures (~55-80°F).
- **Not Accepted**: No major difference, but a slight drop in acceptance on **rainy days**.

### 5. **Type of Coupon**
- **Accepted**: Higher for **Restaurant (<$20)** and **Coffee House**.
- **Not Accepted**: More rejections seen with **Carryout & Takeaway** and **Bar** coupons.

### 6. **Expiration Duration**
- **Accepted**: Customers preferred coupons valid for **1 day**.
- **Not Accepted**: Coupons valid for only **2 hours** were rejected more often.

### 7. **Demographics**
- **Age**: Younger adults (21–30) were more likely to accept.
- **Marital Status**: **Unmarried partners** showed a higher acceptance rate.
- **Education**: College-educated individuals were slightly more open to using coupons.

---

## Conclusion

Coupon acceptance appears to be influenced more by **situational context** (like destination, time of day, and expiration) than just demographic variables. Businesses can improve campaign success by tailoring offers to **time-flexible individuals**, especially in the **afternoon**, and by promoting low-cost food coupons with longer validity.

---

## Files Included
- `coupon_analysis.ipynb`: Notebook with data exploration and visualization
- `data.csv`: Cleaned dataset used in analysis
- `README.md`: This nontechnical summary report

