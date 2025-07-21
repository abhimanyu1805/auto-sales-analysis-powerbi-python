# auto-sales-analysis-powerbi-python
# 🚗 Auto Sales Dashboard — Power BI + Python (Pandas)

This is an end-to-end Business Intelligence project that analyzes auto sales data. It involves:

- 🔍 Data Cleaning and Transformation using **Python (Pandas in Jupyter)**
- 📊 Interactive Dashboard creation using **Power BI**
- 📈 KPIs, Charts, Slicers, and Filters to extract insights

---

## 📌 Tools Used

- 🐍 **Python (Pandas, Jupyter Notebook)** — for data cleaning, feature engineering
- 📊 **Power BI** — for data visualization and dashboard creation
- 📄 **CSV files** — for data storage and exchange between tools

---

## ⚙️ Data Cleaning (Jupyter Notebook)

Key preprocessing done using Pandas:
- Removed duplicates and nulls
- Created `TotalOrders`, `TotalRevenue`, and `AOV (Average Order Value)`
- Cleaned `ProductLine` names
- Converted date formats
- Exported clean dataset as `.csv` for Power BI use

> ✅ See: [data-cleaning-script.ipynb](data-cleaning-script.ipynb)

---

## 📊 Power BI Dashboard Features

![dashboard](images/dashboard.png)

- **KPIs**: Total Orders, Total Revenue, Average Order Value
- **Slicers**: ProductLine, Country, Year
- **Graphs**: Bar Charts, Line Charts, Pie Charts for Category Breakdown
- **Filters**: Applied across pages for dynamic reporting

---

## 📁 Files in This Repo

| File | Description |
|------|-------------|
| `SalesDashboard.pbix` | Final Power BI report |
| `data-cleaning-script.ipynb` | Python notebook for cleaning and transformation |
| `cleaned_auto_sales_data.csv` | Final dataset used in Power BI |
| `images/` | Screenshots used for README display |

---

## 🧠 Insights Gained

- SUVs generate the highest revenue
- 2022 saw the peak in order volume
- USA and Germany lead in sales
- Average order value varies by product line and region

---

## 💼 Why This Project Matters

This project simulates a **real-world BI/DA role**, where:
- Raw data is cleaned using **Python**
- Visual analytics are created in **Power BI**
- Business stakeholders can explore data using **filters and slicers**

---

## 📬 Contact

**Abhimanyu Rajput**  
📧 [Your Email]  
🔗 [LinkedIn Profile]  
🌐 [Portfolio/Website if any]

---

