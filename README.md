# 🏠 Housing Sales Analytics

This repository contains my end-to-end workflow of **housing sales analysis and visualization**, starting from data preparation in **Google Cloud** to building an **interactive Power BI dashboard**.

---

## 🚀 Project Workflow

### 1️⃣ Data Preparation (Google Cloud & SQL)
- Imported housing sales dataset into **Google Cloud BigQuery**.
- Performed basic **SQL queries** for:
  - Cleaning null and duplicate values
  - Standardizing columns
  - Preparing sales and purchase data for visualization
- Connected the cleaned dataset to **Power BI**.

---

### 2️⃣ Power BI Dashboard
I developed an interactive **Power BI report** with 3 main tabs:

#### 📊 Tab 1: House Market View
- Year-over-year (YOY) sales growth (12 months trend).
- Median sales price by region.
- Units sold.
- Custom **DAX formulas** used to calculate growth and KPIs.

#### 📈 Tab 2: Sales Performance
- Sales by region (Zealand, Jutland, Fyn & Islands, Bornholm).
- Detailed table with **Total YTD sales** and **Sum of purchase price**.
- **Key Influencer Visual**: Explains increase/decrease in purchase price based on average buyer age.

#### 🏡 Tab 3: House Type Analytics
- Interactive slicers for **Area, City, Sales Type, and Region**.
- KPIs:
  - Average purchase price
  - Yield, interest, and inflation comparison
  - Average sqm and sqm price by house type (Apartment, Villa, Townhouse, etc.)

---

## 📂 Files in Repository
- **/data** → Raw and cleaned datasets (Google Cloud SQL exports).
- **/reports** → Power BI files (`.pbix`).
- **/docs** → PDF report snapshots (for quick view).

---


