# Tailwind Traders Executive Dashboard
![Dashboard Preview](https://raw.githubusercontent.com/jhapriyanshu16/Power-BI-Capstone-Project/main/Images/dashboard.png)


## 📌 Overview
This project is an **Executive Dashboard** built in **Power BI** for Tailwind Traders. The dashboard provides key insights into **Sales and Profit** data, including core visualizations, KPIs, and alerts. Additionally, it includes **automated subscriptions** to keep stakeholders informed.

---

## 🛠️ Data Preparation and Modeling
### 1️⃣ Data Generation
- The dataset was generated using a **Python script**, simulating sales and profit data.
- The script created structured data for different product categories, revenue, and profit margins.

### 2️⃣ Data Storage & Schema
- Data was **stored in Snowflake** following a **Star Schema**.
- **Fact Table**: Contains aggregated sales & profit data.
- **Dimension Tables**:
  - `DimProduct` (Product details)
  - `DimCustomer` (Customer details)
  - `DimDate` (Date-related attributes)
  - `DimLocation` (Geographical details)

### 3️⃣ Data Transformation
- Used **Power Query Editor** to clean and transform the data.
- Created **calculated columns** and **measures** using **DAX**.

---

## 📊 Dashboard Creation Steps
### 1️⃣ Create a New Dashboard
- **Workspace:** Created `Tailwind Traders Executive Dashboard` in Power BI.
- **Reports:** Used `Sales Overview` & `Profit Overview` pages.

### 2️⃣ Add Core Visualizations
- **Sales Overview:**
  - `Loyalty Points by Country` (Bar Chart)
  - `Quantity Sold by Product` (Column Chart)
  - `Median Sales Distribution by Country` (Pie Chart)
  - `Median Sales Over Time` (Line Chart)
- **Profit Overview:**
  - `Net Revenue by Product` (Bar Chart)
  - `Yearly Profit Margin by Country` (Donut Chart)
  - `Yearly Profit Margin Over Time` (Area Chart)

### 3️⃣ Add KPI & Card Visualizations
- `Sum of Stock`
- `Sum of Quantity Purchased`
- `Median Sales`
- `YTD Profit`
- `Sum of Net Revenue USD`
- `Sum of Gross Revenue USD KPI`

### 4️⃣ Mobile View Configuration
- Adjusted visuals for **responsive layout**.
- Used **Mobile Layout Editor** in Power BI.

---

## 🔔 Alerts & Subscriptions Setup
### 1️⃣ Alerts Configuration
- **Created a Daily Alert for Gross Revenue USD**
  - Condition: **Below $400**
  - Frequency: **Every 24 hours**

### 2️⃣ Subscriptions Setup
- **Sales Weekly Summary**
  - Frequency: **Weekly (Monday, 5:00 AM)**
- **Profit Weekly Summary**
  - Frequency: **Weekly (Monday, Wednesday, Friday, 6:00 AM)**

---

## 📸 Screenshots
![Report Preview](https://raw.githubusercontent.com/jhapriyanshu16/Power-BI-Capstone-Project/main/Images/Report1.png)
![Report Preview](https://raw.githubusercontent.com/jhapriyanshu16/Power-BI-Capstone-Project/main/Images/Report2.png)

---

## 🚀 Conclusion
This project showcases the **end-to-end process of building an executive dashboard**, from **data preparation and modeling** to **dashboard creation, mobile view optimization, and automated alerts**. This dashboard enables **real-time monitoring** of key business metrics for Tailwind Traders.

---




