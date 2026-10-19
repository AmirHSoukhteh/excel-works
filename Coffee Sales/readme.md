
# ☕ Coffee Sales Dashboard | Excel

An interactive Excel dashboard for analyzing coffee sales from 2019 to 2022. This project transforms raw order, customer, and product data into visual insights that help explore sales performance, compare coffee types, identify key markets, and understand customer purchasing behavior.

## 📊 Dashboard Preview

![Coffee Sales Dashboard](pics/Excel%20Coffee%20Dashboard.PNG)

## 🎯 Project Objectives

- Analyze coffee sales trends over time.
- Compare sales performance across different coffee types.
- Identify the countries contributing the most to total sales.
- Highlight top customers based on sales.
- Explore how roast type, package size, and loyalty card status relate to sales.
- Build an interactive dashboard that makes business data easier to explore.

## 📈 Dashboard Features

### 1. Sales Trends by Coffee Type

A time-series visualization comparing sales for four coffee varieties:

- Arabica
- Excelsa
- Liberica
- Robusta

The chart covers multiple years, making it possible to explore changes in sales over time and compare performance across coffee types.

### 2. Sales by Country

A horizontal bar chart showing sales across countries, helping identify the strongest markets and compare their contributions to overall sales.

### 3. Top 5 Customers

A ranking of the five highest-selling customers, highlighting the customers who contribute the most sales.

### 4. Interactive Filters

The dashboard includes filters for:

- **Order Date:** Explore sales across different periods.
- **Size:** Filter by coffee package size (0.2 kg, 0.5 kg, 1.0 kg, and 2.5 kg).
- **Roast Type:** Compare Dark, Light, and Medium roasts.
- **Loyalty Card:** Analyze purchases by customers with and without loyalty cards.

These filters allow users to explore the data from different business perspectives without manually editing the underlying dataset.

## 🗂️ Dataset

The Excel workbook contains order, customer, and product data organized into separate worksheets.

| Worksheet | Description |
|---|---|
| `orders` | Order dates, quantities, customer and product identifiers, coffee types, roast types, sizes, and sales-related information |
| `customers` | Customer details, location information, and loyalty card status |
| `products` | Coffee type, roast type, package size, unit price, price per 100 g, and profit |
| `Total Sales` | Aggregated sales by year, month, and coffee type |
| `Sales by Country` | Total sales grouped by country |
| `Top Customers` | Customers ranked by sales |
| `Dashboard` | Main interactive dashboard |

The `orders`, `customers`, and `products` worksheets each contain approximately 1,000, 1,000, and 48 data rows, respectively, including their headers where applicable.

## 🛠️ Tools & Techniques

- **Microsoft Excel**
- PivotTables and PivotCharts
- Interactive dashboard design
- Timeline and slicer-based filtering
- Data aggregation and comparison
- Date-based sales analysis
- Customer and geographic analysis
- Data visualization and reporting

## 🚀 How to Use

1. Download or clone this repository.
2. Open the Excel workbook.
3. Navigate to the `Dashboard` worksheet.
4. Use the date timeline and filters to explore sales by period, package size, roast type, and loyalty card status.
5. Compare coffee-type trends, country sales, and top customers.

**Recommended:** Use the desktop version of Microsoft Excel for the best experience with interactive dashboard controls.

## 💡 Key Takeaways

This project demonstrates how Excel can be used to turn transactional data into an interactive business dashboard. It combines time-series analysis, geographic comparisons, customer ranking, and interactive filtering in a single view.

The dashboard provides a practical example of using spreadsheet-based business intelligence to explore sales performance and support data-informed decisions.

## 👤 Author

**Amir Hossein Soukhteh**

- Portfolio: [amirhsoukhteh.github.io](https://amirhsoukhteh.github.io)
- GitHub: [@AmirHSoukhteh](https://github.com/AmirHSoukhteh)

