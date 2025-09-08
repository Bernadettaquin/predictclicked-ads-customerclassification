# Predict Clicked Ads Customer Classification using Machine Learning

This project predicts whether a customer will **click on an online advertisement** based on their online behavior and demographic data. By applying **machine learning**, businesses can optimize ad targeting, reduce wasted spend, and increase profits.

---

## 📌 Project Overview
Companies spend heavily on online ads without knowing which users are likely to click. This project applies data-driven approaches to classify customers and improve marketing efficiency.

**Goals:**
- Identify factors influencing ad clicks  
- Improve marketing campaign effectiveness  
- Optimize ad budget allocation for maximum profit  

---

## 📊 Dataset
- **Population:** 1000 customers  
- **Split:** 80% training, 20% testing  
- **Balanced Data:** 500 clicked, 500 not clicked  

**Features include:**
- Daily Time Spent on Site  
- Age  
- Area Income  
- Daily Internet Usage  
- Gender, City, Province, Category  
- Clicked on Ad (target variable)  

---

## 🔎 Exploratory Data Analysis
- Users aged **30–40** dominate (productive group).  
- Higher **internet usage → fewer clicks** (ad fatigue).  
- Women clicked slightly more ads than men.  
- Jakarta & West Java are the most active regions.  

---

## ⚙️ Data Preprocessing
- Missing values handled (mean/mode).  
- Label Encoding for categorical features.  
- Extracted year, month, day, hour, minute from timestamp.  
- StandardScaler applied for normalization.  

---

## 🤖 Models & Performance
Performance before/after normalization:

📌 **Best Model:** Logistic Regression with normalization

---

## 📈 Business Impact
- **Without ML:** Profit = Rp 24,500,000  
- **With ML (LogReg):** Profit = Rp 43,000,000  
- **Profit Increase:** **+75.5%** with the same ad budget  

---

## 💡 Recommendations
- Focus on **high-engagement categories** (Furniture, Travel, Electronics)  
- Prioritize **geo-targeting** (Jakarta Selatan, Jakarta Pusat, Samarinda)  
- Optimize **ad timing** by day/month/hour  
- Segment by **internet usage & time spent**  
- Tailor ads by **income & age group**  
