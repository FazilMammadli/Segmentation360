# Segmentation360 📊🛒  

This project leverages **machine learning-based customer segmentation** to analyze purchasing behavior in an **E-commerce platform**. Using **clustering and classification techniques**, it provides businesses with **data-driven insights** to optimize marketing strategies, customer retention, and sales growth.

---

## 🚀 Project Overview

Customer segmentation plays a **crucial role** in understanding shopping patterns. This project aims to:
- **Identify customer groups** based on their purchasing behavior.
- **Predict future transactions** from new customers.
- **Optimize marketing efforts** by targeting the right audience.

By using **historical transaction data**, we extract key features to cluster customers and develop a classification model that anticipates **buying trends**.

---

## 📊 Dataset Information

The dataset consists of **~4000 customer records** from an E-commerce platform. Each entry contains:
- **Order details** (InvoiceNo, Product Code, Description)
- **Transaction information** (Date, Quantity, Unit Price)
- **Customer identifiers** (Customer ID, Country)

📌 **Source:** UCI Machine Learning Repository  

### 🔍 Feature Breakdown
1. **InvoiceNo** → Unique identifier for each transaction.  
2. **StockCode** → Unique product identifier.  
3. **Description** → Name of the purchased product.  
4. **Quantity** → Number of items purchased.  
5. **InvoiceDate** → Timestamp of purchase.  
6. **UnitPrice** → Price per unit of product.  
7. **CustomerID** → Unique identifier for customers.  
8. **Country** → Country where the order was placed.  

![data init head](https://user-images.githubusercontent.com/25388109/86505675-d220f580-bdbf-11ea-8260-c165bf645c63.png)

---

## 🛠️ Setting Up the Project

Follow these steps to run the project on your local machine:

1️⃣ **Clone the Repository**
```sh
git clone https://github.com/FazilMammadli/Segmentation360.git
cd Segmentation360
```

2️⃣ **Create and Activate a Virtual Environment**
```sh
python -m venv .venv
.venv\Scripts\activate  # Windows
source .venv/bin/activate  # Mac/Linux
```

3️⃣ **Install Required Libraries**
```sh
pip install -r requirements.txt
```

4️⃣ **Run the Jupyter Notebook**
```sh
jupyter notebook
```
Open and execute `E-Commerce Customer Segmentation.ipynb` to explore the dataset and train models.

---

## 🔬 Data Processing & Analysis

### **1️⃣ Data Cleaning**
- Removed **duplicate, missing, and inconsistent values**.
- Standardized **numerical and categorical variables**.
- Created new **behavioral metrics** for deeper analysis.

### **2️⃣ Exploratory Data Analysis (EDA)**
- **Geographic distribution of customers**
  ![](https://user-images.githubusercontent.com/25388109/86505481-152d9980-bdbd-11ea-9d45-5a8292671f31.png)

- **Top spending countries**
  - 🇬🇧 **United Kingdom** → `19,857 customers`
  - 🇩🇪 **Germany** → `603 customers`
  - 🇫🇷 **France** → `458 customers`
  - 🇮🇪 **EIRE** → `319 customers`
  - 🇧🇪 **Belgium** → `119 customers`

### **3️⃣ Customer Segmentation**
- Applied **K-Means Clustering** and **PCA Analysis**:
  ![](https://user-images.githubusercontent.com/25388109/86505918-18775400-bdc2-11ea-9508-40b33ddc3da9.png)

- Extracted customer **morphology insights**:
  ![](https://user-images.githubusercontent.com/25388109/86505974-a81d0280-bdc2-11ea-9eb7-cc42b2fe055a.png)

---

## 🤖 Machine Learning Models Used

### **1️⃣ K-Means Clustering**
✅ **Identified customer groups based on Recency, Frequency, and Monetary (RFM) Analysis**.  
✅ **Used the Elbow Method to determine optimal clusters**.  

### **2️⃣ Classifiers for Prediction**
Trained multiple models to predict customer behavior:
| Model        | Learning Curve |
|-------------|--------------|
| AdaBoost    | ![](https://user-images.githubusercontent.com/25388109/86506016-1feb2d00-bdc3-11ea-81bc-5ca083bf8916.png) |
| Decision Tree | ![](https://user-images.githubusercontent.com/25388109/86506017-211c5a00-bdc3-11ea-8813-0f0d7f3b2222.png) |
| Gradient Boost | ![](https://user-images.githubusercontent.com/25388109/86506018-21b4f080-bdc3-11ea-916e-ee4270d2579b.png) |
| KNN | ![](https://user-images.githubusercontent.com/25388109/86506019-224d8700-bdc3-11ea-992c-e43120a2d454.png) |
| Logistic Regression | ![](https://user-images.githubusercontent.com/25388109/86506021-24afe100-bdc3-11ea-87ab-110886ca2f91.png) |
| Random Forest | ![](https://user-images.githubusercontent.com/25388109/86506022-25487800-bdc3-11ea-88a8-5ba35d71c89f.png) |

🏆 **Best Model:** Gradient Boosting performed the best in classification accuracy.

---

## 🔑 Key Insights

- **High-value customers** shop frequently and spend more.  
- **At-risk customers** haven’t purchased in a long time.  
- **New customers** have a lower frequency but high potential.  
- **Seasonality plays a role in customer behavior.**  

---

## 📌 Business Recommendations

💡 **Personalized Marketing:**  
- Offer **loyalty rewards** to frequent buyers.  
- Use **targeted email marketing** to engage inactive customers.  

💡 **Inventory Optimization:**  
- Adjust stock levels based on **customer demand trends**.  
- Improve product recommendations using **clustered customer profiles**.  

💡 **Predictive Analytics:**  
- Use historical data to **forecast seasonal demand spikes**.  
- Implement **AI-powered dynamic pricing models**.  

---

## 🎯 Conclusion

This project demonstrates how **customer segmentation with machine learning** enables businesses to **optimize sales, improve customer retention, and drive revenue growth**. 

By leveraging **data-driven insights**, companies can create **more effective marketing campaigns** and enhance the overall customer experience. 

---

## ⭐ Support & Contributions

If this project was useful, **drop a ⭐ on GitHub**!  
For feedback or contributions, **submit a pull request**! 🚀  
