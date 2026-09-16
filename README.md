# 🍕 Pizza Sales Dashboard — Excel

An interactive sales dashboard built entirely in Microsoft Excel using PivotTables, PivotCharts, slicers, and a timeline filter. It turns raw pizza order records into a single-screen view of sales performance, product mix, and customer ordering behavior.

![Dashboard Preview](https://github.com/Shahdelsayed3303/pizza-sales-dashboard-excel/blob/main/pizza%20dashboard.PNG)

## 📊 Overview

| Metric | Value |
|---|---|
| Total Sales | $8,436 |
| Total Quantity | 511 |
| Total Orders | 499 |

## 🗂️ Dataset

The `Data` sheet holds 499 pizza order records with the following fields:

| Column | Description |
|---|---|
| `order_id` | Unique order number |
| `pizza_id` | Pizza identifier (name + size) |
| `Customer Name` | Name of the customer |
| `quantity` | Number of pizzas in the order |
| `order_date` | Date of the order |
| `order_time` | Time of the order |
| `unit_price` | Price per pizza |
| `total_price` | Line total (quantity × unit price) |
| `pizza_size` | S, M, L, XL |
| `pizza_category` | Chicken, Classic, Supreme, Veggie |
| `pizza_ingredients` | Ingredient list |
| `pizza_name` | Full pizza name |

## 📈 Dashboard Visuals

- **Total Sales per Category** — doughnut chart showing the share of Chicken, Classic, Supreme, and Veggie
- **Sales Distribution by Pizza Size** — pie chart (L is the leading size)
- **Hourly Order Trend** — line chart of orders from 11 AM to 11 PM, revealing lunch and dinner peaks
- **Top 5 Most Expensive Pizzas** — bar chart by unit price
- **Top 10 Best-Selling Pizzas** — bar chart by quantity sold
- **KPI cards** — Total Sales, Total Quantity, Total Orders

## 🎛️ Interactivity

The dashboard is fully filterable through:

- **Slicers** for `pizza_size` and `pizza_category`
- **Timeline** on `order_date` for filtering by year, quarter, or month

Every chart updates simultaneously when a filter is applied.

## 📁 Workbook Structure

| Sheet | Purpose |
|---|---|
| `Definition` | Short explanation (in Arabic) of what a PivotTable is and how it works |
| `Data` | The raw order-level dataset |
| `Pivot Table` | All PivotTables feeding the dashboard |
| `Dashboard` | The final interactive report |

## 🛠️ Tools & Skills

- Microsoft Excel
- PivotTables & PivotCharts
- Slicers and Timeline filters
- Data cleaning and formatting
- Dashboard design and layout

## 🚀 How to Use

1. Download or clone the repository.
2. Open `pizza-Sales-Dashboard.xlsx` in Microsoft Excel (desktop version recommended — slicers and timelines don't fully work in some online viewers).
3. Go to the **Dashboard** sheet.
4. Use the slicers and timeline to explore the data.

## 👩‍💻 Author

**Shahd** — Computer And Systems Engineering student, Zagazig University

---

⭐ If you found this project useful, consider giving it a star.
