# 📊 Mobile Sales Dashboard – Power BI Project

## 📟 Project Objective
The goal of this project is to design an interactive Power BI dashboard that helps stakeholders analyze mobile phone sales data across various Indian cities. The dashboard provides insights into total sales, top-performing brands and models, sales trends over time, and customer behavior through payment methods and ratings.

---

## 🖼️ Dashboard
<img width="1328" height="750" alt="Screenshot 2025-07-26 004528" src="https://github.com/user-attachments/assets/7f0a5a4b-0102-4802-bb75-5590e9703947" />
<br><br>
<img width="1326" height="749" alt="Screenshot 2025-07-26 004637" src="https://github.com/user-attachments/assets/698bbd13-d850-4689-b23a-8135b048bb63" />



---

## ❓ Business Questions Answered
- What is the total sales revenue, quantity sold, and number of transactions?
- Which mobile brands and models contribute most to overall sales?
- Which cities generate the highest mobile sales?
- What are the most preferred payment methods?
- How are customer ratings distributed?
- Which days of the week have the highest sales?

---

## ⚖️ Data Cleaning & Preparation (Power Query Editor)
- Corrected invalid or inconsistent date formats.
- Generated a new column to extract **Day Name** from the Date field.
- Removed unnecessary and irrelevant columns to streamline the dataset.
- Created a calculated column:  
  **Total Sales = Units sold × Price per unit**
- Ensured data types were set appropriately (e.g., dates, numbers).

---

## 🧺 DAX Measures Created
- **Quantity Sold:** `SUM(Sales_data[Units Sold])`
- **Transactions:** ` COUNTROWS(Sales_data)`
- **Average:** ` AVERAGE(Sales_data[Total Sales])`

---

## 📈 Visualizations Used
- Normal Slicers (Year, Brand, Payment Method, etc.)
- Button Slicer (Month selection)
- Map (Sales by City)
- Line Chart (Monthly Quantity Sold)
- Table (Brand-wise Sales Breakdown)
- Funnel Chart (Customer Ratings)
- Pie Chart (Transactions by Payment Method)
- Clustered Bar Chart (Top Mobile Models)
- Area Chart (Sales by Day Name)

---

## 🔍 Overall Key Insights
- **Apple** led in total sales among all brands, followed closely by **Samsung** and **OnePlus**.
- The **iPhone SE**, **OnePlus Nord**, and **Galaxy Note 20** were the top-selling models.
- **Delhi** and **Mumbai** were among the highest-performing cities.
- **UPI** and **Debit Card** were the most popular payment methods.
- **Saturday and Sunday** had high sales, suggesting strong weekend performance.

---

## ✅ Final Conclusion
This Power BI dashboard offers an intuitive and comprehensive view of mobile sales performance across regions, timeframes, and customer preferences. By combining advanced visualizations with strong data modeling practices, it enables stakeholders to make informed decisions on product strategy, inventory distribution, and marketing campaigns. 

