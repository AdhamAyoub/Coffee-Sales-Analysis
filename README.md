# ☕ Coffee Shop Sales Analysis  

## 📌 Project Overview  
This project analyzes sales data from a coffee shop using **Excel**. It focuses on **data cleaning, transformation, and visualization** to uncover insights about revenue, customer behavior, and product performance.  
![Sales Pivot Chart](Coffee-Shop-Sales-Analysis/Visuals/DashBoard.png)

## 📂 Dataset Description  
The dataset consists of the following fields:  
- **Customers Information:** `Customer ID`, `Name`, `number`,`Address`, `City`, `Email`, `Country` 
- **Product Details:** `Coffee ID`, `Coffee Type`, `Roast Type`, `Size`, `Quantity`, `Price`  
- Some fields were missing and were filled using **VLOOKUP** and **MATCH** functions.  

## 🛠️ Techniques & Functions Used  
- 🔹 **VLOOKUP & MATCH** – Used to fill missing data from reference tables  
- 🔹 **IF Conditions** – Categorized coffee sizes (e.g., `M → Medium`, `L → Large`)  
- 🔹 **Calculated Columns** – Computed total salary (`Quantity * Price`)  
- 🔹 **Pivot Tables** – Analyzed sales performance across months and countries  
- 🔹 **Slicers & Charts** – Created interactive visuals for better data exploration  

## 📊 Key Insights  
- 📈 Identified **top 5 customers** based on total purchases  
- 🌍 Analyzed **monthly and country-wise sales trends**  
- ☕ Found the **most popular coffee types and sizes**  
