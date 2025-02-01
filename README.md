# KWANZA TUKULE DATA ANALYSIS.
![front_image](images/image1.jpg)
## Project Overview  
I completed this project as part of the **Kwanza Tukule Data Analyst Assessment**. It involves analyzing anonymized sales data, providing insights, and creating a **dashboard** for visualization. The goal is to help **street food vendors and kiosks in low-income areas** access affordable and nutritious food by improving **sales performance analysis, customer segmentation, and demand forecasting**.  

## 📂 Dataset  
The dataset consists of anonymized sales transactions, including:  
- **DATE** – The transaction date  
- **ANONYMIZED CATEGORY** – Product category  
- **ANONYMIZED PRODUCT** – Purchased product  
- **ANONYMIZED BUSINESS** – Business that made the purchase  
- **QUANTITY** – Number of units sold  
- **UNIT PRICE** – Price per unit  
- **VALUE** – Total sales value (Quantity × Unit Price)  

## Key Analysis and Features  
### 1️⃣ **Exploratory Data Analysis (EDA)**  
✔ Sales trends over time  
✔ Top-performing Products and categories   
✔ Business performance comparison  

![plot](images/newplot.png)
### 2️⃣ **Customer Segmentation**  
✔ Grouped businesses into **High Value, Medium Value, and Low Value** segments  
✔ Used **K-Means clustering** to analyze purchasing patterns  

### 3️⃣ **Forecasting**  
✔ Used **ARIMA time series forecasting** to predict total sales value for the next 3 months  

### 4️⃣ **Anomaly Detection**  
✔ Identified unusual **sales spikes or drops** using **moving averages and standard deviation**  

### 5️⃣ **Interactive Dashboard**  
- I leveraged streamlit.io  
✔ **Filters**: By Category and Business selection  
✔ **Visualizations**:  
- **Sales by Category** (Bar Chart)  
- **Top Products & Businesses** (Pie & Bar Charts)  
- **Sales Trends** (Time Series Line Chart)  
- **Customer Segmentation Insights**  

## Deployment.  
### **🔗 Streamlit App**  
🌐 [View the Live Dashboard](https://kwanza-tukule-app.streamlit.app/)  
>## *“Data is the new oil. It's valuable, but if unrefined, it cannot really be used.”* - Clive Humby.


