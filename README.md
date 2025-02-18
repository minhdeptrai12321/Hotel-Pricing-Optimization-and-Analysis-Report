# 📊 Hotel Pricing Optimization and Analysis Report

## 📌 1. Introduction
The provided hotel dataset contains information about bookings, payments, customer services, and additional services. This report leverages **data analysis** and **machine learning** to analyze booking performance, optimize room pricing, classify customers, and detect anomalies in hotel operations.

## 🎯 2. Analysis Objectives
- 🔹 **Analyze booking performance**
- 🔹 **Evaluate revenue and customer services**
- 🔹 **Optimize room pricing**
- 🔹 **Predict and classify customers**
- 🔹 **Detect anomalies in transactions**

---

## 📈 3. Hotel Data Analysis

### 📌 3.1. Booking Performance
- The **occupancy rate** of different rooms was analyzed.
- The **Executive** and **Suite** rooms had the **lowest occupancy rates**.
- Booking performance **fluctuates seasonally**, peaking during **May - July** and dropping in **January & February**.

### 📌 3.2. Revenue & Service Analysis
- The most frequently used services include:
  - 🏨 **Room Service**
  - 🎟 **Tour Packages**
  - 🏅 **VIP Lounge**
- These services contribute significantly to total revenue.

### 📌 3.3. Room Pricing Optimization
- Analyzed **the impact of pricing on booking trends**.
- **No strong correlation** was found between room price and the number of bookings.
- **Adjusting prices based on seasons** may help optimize revenue.

### 📌 3.4. Booking Cancellation Rate
- The **cancellation rate** stands at **34.04%**.
- The highest cancellation rates occur in **April & October**.
- **Premium rooms** (Presidential, Executive) have higher cancellation rates.

---

## 🤖 4. Customer Prediction and Classification

### 📌 4.1. VIP Customer Segmentation
- **K-Means clustering** was used to segment customers into **4 groups**.
- **VIP customers** tend to **spend more** but **stay for shorter durations**.
- **Loyal customers** stay longer but spend moderately.

### 📌 4.2. Customer Churn Prediction
- **Random Forest model** predicted **352 customers** at risk of leaving.
- Customers with **high cancellation rates** or **unpaid bookings** are at higher risk.

---

## ⚠️ 5. Anomaly Detection

### 📌 5.1. Fraudulent Payment Transactions
- **Isolation Forest model** detected **58 anomalous transactions**.
- Some transactions showed **unusually high or low payments**.

### 📌 5.2. Customers Exploiting Cancellation Policy
- Identified **10 customers** with **abnormally high cancellation rates**.
- Possible indications of **fraudulent booking behavior**.

---

## 🎯 6. Key Takeaways
| **Aspect** | **Findings** |
|------------|-------------|
| **Booking Trends** | Peaks in **May - July**, drop in **Jan & Feb** |
| **Most Used Services** | **Room Service, VIP Lounge, Tour Packages** |
| **Price Impact** | No strong correlation, but **seasonal pricing works** |
| **Cancellation Rate** | **34.04%**, highest in **April & October** |
| **VIP Customers** | High spenders, but shorter stays |
| **Churn Prediction** | **352 customers** at risk of leaving |
| **Fraud Detection** | **58 suspicious transactions** detected |

---

## 🚀 7. Recommendations
- ✅ **Adjust room pricing seasonally** to maximize revenue.
- ✅ **Track customers with high cancellation rates** to mitigate risks.
- ✅ **Use Machine Learning to detect fraudulent activities** in bookings & payments.

---


