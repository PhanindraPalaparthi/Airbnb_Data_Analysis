# 🏠 An Exploration of Airbnb’s New York City Listings  
*Through the Use of Data Mining Tools*  

**Authors**: John Cognetti, Aayushi Jayaswal, Phanindra Palaparthi  
**Institution**: George Mason University  

📄 Full Paper: [project-report.pdf](./paper/project-report.pdf)  

---

## 📖 Abstract  
Utilizing data from Inside Airbnb, this research focuses on:  
1. Predicting property prices based on listing details and customer reviews  
2. Understanding popular amenities and their influence on booking rates  
3. Exploring the impact of property availability on reviews  
4. Analyzing price differences across various neighborhoods  

We apply **exploratory data analysis, feature engineering, and machine learning models** (Lasso regression, Random Forest, K-Means clustering) to uncover insights that can assist hosts in optimizing their listings and pricing strategies:contentReference[oaicite:1]{index=1}.  

---

## 🛠 Methods  
- **Exploratory Data Analysis (EDA)**: Data cleaning, handling nulls, outlier removal  
- **Price Prediction**: Lasso regression with borough-level splits  
- **Booking Rates**: Amenity matrix + Random Forest, Logistic Regression, Gradient Boosted models  
- **Availability vs Reviews**: Logistic & Linear regression  
- **Neighborhood Clustering**: K-Means on price/location  

---

## 📊 Key Findings  
- Property size (beds, bedrooms, accommodates) is most correlated with price  
- Essential amenities (Wi-Fi, heating, kitchen) drive higher booking rates  
- Properties with more consistent availability get reviewed more frequently  
- Pricing disparities exist across NYC boroughs, with distinct clusters emerging  

---

## 📂 Repository Contents  
- `/paper` → PDF of the full report  
- `/notebooks` → Jupyter notebooks for EDA, models, clustering  
- `/data` → Instructions to access InsideAirbnb dataset  
- `/src` → Python scripts (if applicable)  

---

## 📄 Citation  

If you use this work, please cite:  

