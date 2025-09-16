# 🍴 Swiggy Sales Analysis Dashboard  

## 📌 Project Objective  
The **Swiggy Sales Analysis Dashboard** is designed to provide an end-to-end analysis of Swiggy’s business performance using **Excel, Power Query, DAX, and Power BI**.  

The goal of this project is to deliver actionable insights into:  
- Order and Sales performance across multiple cities  
- Customer demographics and purchasing behavior  
- Food category analysis (Veg, Non-Veg, Others)  
- User engagement through ratings and repeat orders  
- Long-term growth trends of sales and customers  

This project bridges the gap between **raw sales data** and **business decision-making**, enabling stakeholders to make data-driven choices for expansion, marketing, and customer retention.  

---

## 📊 Dashboard Overview  

The solution consists of **3 interactive dashboards**, each focusing on a different aspect of the business.  

---

### 1️⃣ City Overview Dashboard  
![City Overview](City%20Overview.png)  

The **City Overview Dashboard** gives a high-level picture of how different cities contribute to Swiggy’s overall performance.  
It is designed to help identify **where the business is performing well** and **which locations need attention**.  

#### 🔑 Key Features:  
- 🌍 **Map Visualization** – Interactive map showing the distribution of **sales and orders across Indian cities**, making it easy to spot regional demand clusters.  
- 📊 **City-wise Performance Table** – A detailed table that lists **Total Sales, Orders, and Current Year Sales** for every city. This enables granular comparison of performance at the city level.  
- 🏙️ **Top Cities Bar Chart** – A ranked bar chart that highlights the **highest revenue-generating cities**. The chart makes it simple to identify where Swiggy’s strongest customer base is located.  
- 👥 **User & Ratings Metrics** – Cards showing **total number of users** in each city along with the **ratings count**, which provides a quick snapshot of engagement and satisfaction levels.  

#### 💡 Business Value:  
- Helps Swiggy identify **key hotspot cities** where revenue and orders are the highest.  
- Assists leadership teams in making **data-driven expansion strategies** by focusing on regions with high sales and customer adoption.  
- Allows regional managers to track **customer engagement levels** through ratings, which can be used to measure service quality.  
- Offers a **clear and comparative view** of sales dominance across multiple cities, supporting decisions like **where to invest more marketing budget** or **where to optimize delivery operations**.  
- Facilitates **benchmarking of cities** against each other to understand best-performing markets and underperforming ones.  

---

### 2️⃣ User Performance Dashboard  
![User Performance](User%20Performance.png)  

The **User Performance Dashboard** focuses on **customer demographics and purchasing behavior**.  
It gives a breakdown of who the customers are, what age groups they belong to, their marital status, and their professional background.  

#### 🔑 Key Features:  
- 👤 **KPI Cards** – High-level metrics showing **total user count, contribution of top 10% customers, and year-on-year sales trends**.  
- 🧑‍🤝‍🧑 **Demographic Segmentation** –  
  - **Gender Split** – Distribution of male and female customers, useful for understanding gender preferences in online food ordering.  
  - **Age Group Distribution** – A breakdown of customers into different age brackets, highlighting the **most active customer groups**.  
  - **Marital Status Segmentation** – Split between **single and married users**, which helps understand lifestyle-driven consumption patterns.  
  - **Occupation Categories** – Insights into whether the majority of users are **Students, Employees, Self-Employed, or Homemakers**.  

#### 💡 Business Value:  
- Reveals **the real customer base** of Swiggy by highlighting demographics that contribute the most to sales.  
- Highlights **age groups** with the highest order frequency, enabling targeted campaigns (e.g., student discounts, office lunch offers).  
- Provides marketing teams with data on **occupation-based consumption**, showing whether the app is more popular among working professionals or students.  
- Marital status insights help in designing **personalized offers**, e.g., family combo meals for married customers or budget-friendly options for singles.  
- Helps in **segmentation-based strategy building** – Swiggy can tailor promotions, loyalty programs, and partnerships based on who their customers are.  
- Guides long-term decision-making by showing how **demographics influence order behavior**, helping management allocate resources efficiently.  

---

### 3️⃣ Orders & Sales Dashboard  
![Orders & Sales Dashboard](Dashboard.png)  

The **Orders & Sales Dashboard** provides an overall picture of Swiggy’s growth in terms of orders, sales, and customer preferences.  
It combines **historical trend analysis with category-wise performance**, giving both a time-based and product-based view of business performance.  

#### 🔑 Key Features:  
- 📦 **Overall KPIs** – Cards displaying **Total Orders, Number of Users, Contribution of Top 10% Customers, and Ratings Count**, giving stakeholders a quick snapshot of business health.  
- 🍲 **Food Category Insights** – Donut/Bar charts showing how much of the sales come from **Veg, Non-Veg, and Other categories**, along with their **average prices**. This shows both demand and revenue impact.  
- 📈 **Yearly Trend Analysis** – A line chart showing the **growth in sales and orders from 2017 to 2020**, helping stakeholders measure business momentum.  
- 🏆 **Top City Comparisons** – A flexible visualization that allows users to analyze performance by **Top 10, Top 20, Top 100 cities**, depending on the required detail.  

#### 💡 Business Value:  
- Provides visibility into **customer food preferences** – e.g., while Veg items may have more order volume, Non-Veg items contribute more to revenue due to higher pricing.  
- Tracks **long-term growth trends** across multiple years, helping management evaluate whether business initiatives are paying off.  
- Identifies **top-performing cities over different ranges (Top 10/20/100)**, allowing Swiggy to **prioritize operational improvements** where the demand is highest.  
- Helps in understanding the **revenue contribution of loyal customers (Top 10%)**, which supports customer retention strategies like loyalty points, coupons, or personalized offers.  
- Enables **performance comparison across time and regions**, which is critical for planning promotions, festival campaigns, and partnerships with restaurants.  
- Acts as a **decision-support tool** for the leadership team by consolidating both product performance and market performance into a single view.  

---

## ⚙️ Technical Workflow  

### 🔹 Step 1 – Data Import  
- Collected raw data in **Excel format**  
- Imported into Power BI  

### 🔹 Step 2 – Data Cleaning & Transformation (Power Query)  
- Removed duplicates  
- Standardized city names & categories  
- Filled missing/null values  
- Converted datatypes  

### 🔹 Step 3 – Data Modeling  
- Designed a **star schema** with fact & dimension tables  
- Built relationships between multiple datasets (Food, Menu, Orders, Restaurant, Users)  

### 🔹 Step 4 – DAX Calculations  
Created calculated columns and measures for business KPIs, such as:  
- Total Sales  
- Current vs Previous Year Sales  
- Orders Count  
- Top 10% Customer Contribution  
- Average Food Price by Category  

### 🔹 Step 5 – Dashboard Development  
- Built 3 dashboards with **cards, bar charts, line charts, maps, and donut charts**  
- Applied **Swiggy theme (orange/black)** for consistency  
- Added **interactive slicers, drill-downs, and filters**  

---

## 🚨 Business Problems Solved  

- 📍 Which **cities contribute most** to Swiggy’s revenue?  
- 👥 What are the **key customer demographics** (age, gender, occupation)?  
- 🍲 Which **food categories dominate** (Veg vs Non-Veg)?  
- 📊 How have **orders & sales trended** across years?  
- ⭐ What is the impact of **ratings & repeat customers** on growth?  

---

## ✅ Key Insights  

- **Tirupati, Electronic City, Baner (Pune)** emerged as top-performing regions  
- **Users aged 22–24** form the largest customer base  
- **Employees and Students** dominate the customer segments  
- **Veg food items** lead in quantity, while **Non-Veg has higher average order value**  
- **Top 10% customers contribute a significant share** of sales  

---

## 🛠️ Tech Stack  

- **Excel** → Raw Dataset  
- **Power Query** → Data Cleaning & Transformation  
- **DAX** → Business KPIs & Measures  
- **Power BI** → Interactive Dashboard Development  

---

## 📂 Project Structure  

```
📦 Swiggy-Sales-Analysis-Dashboard
┣ 📊 City Overview.png
┣ 📊 User Performance.png
┣ 📊 Dashboard.png
┣ 📄 README.md
┗ 📁 Dataset (Not uploaded – use your own dataset)
```
---

## 📌 Notes  

⚠️ **Dataset not included in this repo.**  
Due to licensing and privacy concerns, the raw Excel/CSV dataset used in this project is not shared here.  
However, you can replicate the project by:  
- Downloading any Swiggy/Zomato dataset from **Kaggle**  
- Cleaning & transforming data using **Power Query**  
- Rebuilding visuals in **Power BI** with your own dataset  

---

## 👨‍💻 Author  

**Kamal Nayan Tiwary**  
**Data Analyst**

📧 **kamalnayantiwary73@gmail.com**  
🔗 [LinkedIn](https://www.linkedin.com/in/kamal-nayan-tiwary-2022-2026-/)  

---

