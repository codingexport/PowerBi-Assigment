# 📊 Power BI Assignment – All Tasks in One Workbook

This repository contains solutions to the Power BI Assignment questions, solved in a single `.pbix` file. Each question demonstrates a different concept of Power BI using datasets like Superstore, Finance, and Box Office Mojo.

---

## ✅ Q1. Power BI Platform

**What is Power BI?**  
Power BI is a business intelligence and data visualization tool developed by Microsoft. It allows users to connect to multiple data sources, transform raw data into meaningful insights, and share reports across platforms.

**Platforms of Power BI:**
- **Power BI Desktop** – Used for creating reports and dashboards.
- **Power BI Service (Cloud)** – Online SaaS platform to publish and share reports.
- **Power BI Mobile** – Mobile apps to view reports.
- **Power BI Embedded** – Integrate Power BI visuals into custom apps.
- **Power BI Report Server** – On-premises report server.

📷  
![image](https://github.com/user-attachments/assets/3acbf90a-23cb-446d-9b50-313f7d40e7f2)

---

## ✅ Q2. DAX – This Year vs Last Year Sales with Growth %

Created a **Line and Clustered Column Chart** using the **Superstore Dataset** to compare:
- This Year’s Sales
- Last Year’s Sales
- Growth %
📷  
![image](https://github.com/user-attachments/assets/8ced0c19-21b5-4cb0-bc01-2ae6aa6d2d4d)

**DAX Formulas Used:**
DAX
Sales LY = CALCULATE([Sales], SAMEPERIODLASTYEAR('Order Date'[Date]))
Growth % = DIVIDE([Sales] - [Sales LY], [Sales LY])
## ✅ Q3. Data Modeling – 3-Year Master Table from Box Office Mojo

- Imported data from **2023 Worldwide Box Office – Box Office Mojo**.
- Added past 3 years (2021, 2022, 2023) using Power Query Editor.
- Created a **Master Table** by appending all years’ data.
- Loaded only the Master Table into Power BI Desktop for modeling and visuals.

📷  
![image](https://github.com/user-attachments/assets/5c4fbcb4-5d0b-4308-9801-c3efe4f89c4c)


---

## ✅ Q4. Waterfall Chart – Category-wise Yearly Analysis

Using the **Superstore Dataset**, created a **Waterfall Chart** to visualize how each **Category** contributes to **Year-wise Sales**. This helps in understanding the trends and variations year over year.

📷  
![image](https://github.com/user-attachments/assets/e6cd91cb-98d5-4cd9-8c7b-271c10186d6f)


---

## ✅ Q5. Hierarchy – Location-wise Sales using Location Hierarchy

Built a custom **Hierarchy** called `Location`:
- Levels: Country → State → Region → City → Postal Code  
Displayed **Location-wise Sales** using this hierarchy in a matrix and map visual.

📷  
![image](https://github.com/user-attachments/assets/65fc905b-5d75-40b6-af48-387ea14dd480)


---

## ✅ Q6. Bookmark – Clustered Column Chart with Time Filters

Using the **Finance Dataset**, created a **Clustered Column Chart** based on `Order Date` and `Sales`. Added **Bookmarks** to toggle the view:
- Year-wise Sales  
- Quarter-wise Sales  
- Month-wise Sales  
Also included navigation buttons to switch between bookmarks.

📷  
![image](https://github.com/user-attachments/assets/14d93849-155f-4eb5-ae7e-95d41990242f)


---

## ✅ Q7. Drill-through – Region-wise Profit (Focus on West)

Created a **Donut Chart** using **Superstore Dataset** to display **Region-wise Profit**.  
Applied **Drill-through** functionality to navigate to a separate page for **West Region**, showing detailed profit metrics like sub-category, top products, etc.

📷  
![image](https://github.com/user-attachments/assets/c7993f57-e4cd-4656-aa2d-ea7b4ba1b61f)![image](https://github.com/user-attachments/assets/2555a953-5c10-4834-9097-9c1bca8e26a4)

---

## ✅ Q8. Conditional Formatting – Subcategory Table

Used **Superstore Dataset** to create a table showing:
- Subcategory
- Sales
- Profit
- Quantity
- Discount

**Applied Conditional Formatting:**
- **Sales** → Background color (Red = Lowest, Green = Highest)
- **Profit** → Arrow Icons (Red ↓ for negative, Green ↑ for positive)
- **Quantity** → Data Bars
- **Discount** → Font color (Red = Lowest, Green = Highest)

📷  
![image](https://github.com/user-attachments/assets/c6d95363-b2ef-499f-b519-447a58973b8b)


---

## ✅ Q9. Finance Dashboard

Designed a **Finance Dashboard** using the **Finance Dataset**, including:
- **Cards** showing KPIs (Total Revenue, Expense, Profit, etc.)
- **Bar/Line/Donut Charts** to visualize trends
- **Navigation Buttons** for switching pages or views
- **Slicers** for filtering data
- **Web Link** for external navigation

📷  
![image](https://github.com/user-attachments/assets/4ec52e47-9c65-4c5e-b440-10de80bc3ab8)


---

## 📂 Project File

All above tasks are implemented and saved in a single `.pbix` file.

**Filename:** `PowerBI.pbix`

---

## 🧑‍💻 Author -Akhil

Feel free to reach out for improvements or suggestions!

