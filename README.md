# Lanka Fresh Mart – Sales, Cost & Profit Analysis Dashboard

An interactive **Power BI** dashboard built for **Lanka Fresh Mart**, a supermarket chain in Sri Lanka. It turns raw Excel sales data into clear business insights on sales performance, operating cost and profitability, to support better decision-making.

>  Academic project – Data Analysis & Business Intelligence

---

## Project Overview

Supermarkets generate large amounts of transaction data every day, but raw spreadsheets make it hard to see what is really happening. This project solves that by:

- Cleaning and transforming the raw Excel dataset in **Power Query**
- Building a clean data model with **DAX measures**
- Designing a multi-page, interactive dashboard with KPIs and visuals
- Adding dedicated **Cost Analysis** and **Profit Analysis** pages for deeper drill-down

## Objectives

- Track overall **Net Sales, Total Cost and Profit** at a glance
- Identify **top-performing and low-performing products**
- Understand **cost distribution** across branches, provinces and categories
- Analyse **profit by customer segments** (age group, gender, loyalty tier, district)
- Monitor **sales and profit trends over time**

## Dashboard Pages

| Page | Description |
|------|-------------|
| **Navigation** | Landing page with buttons to move between all report pages |
| **Dashboard** | Main executive summary with KPI cards (Net Sales, Total Cost, Profit) and key charts |
| **Cost Analysis** | Where the money goes – cost by branch, category, product, delivery time and date |
| **Profit Analysis** | Who and what drives profit – by product, category, gender, age group, loyalty tier, branch and district |

### Visuals Used

- **KPI Cards:** Net Sales, Total Cost, Profit
- **Line Chart:** Net Sales vs Profit trend over time
- **Ribbon Charts:** Product ranking changes over time (sales and profit)
- **Donut Charts:** Cost by province; profit by category and gender
- **Clustered Column Charts:** Profit by product; cost by order date
- **Area Chart:** Net Sales vs Total Cost by branch
- **Scatter Chart:** Quantity vs Total Cost with delivery days, branch and category
- **Decomposition Trees:** Interactive drill-down of cost and profit by multiple dimensions
- **Navigation buttons** for a smooth, app-like experience

## Data Cleaning & Preparation (Power Query)

- Imported the Excel dataset into Power BI
- Removed duplicates, blanks and inconsistent entries
- Corrected data types (dates, numbers, text)
- Standardised column names and category values
- Created calculated columns/measures for Net Sales, Total Cost and Profit

## 💡 Key Insights

**Dataset:** 9,350 line items across 4,236 orders (Jan 2024 – Dec 2025), 8 branches, 6 provinces, 8 product categories.

**Overall performance:** Net Sales **11.12M**, Total Cost **8.99M**, Profit **2.12M** (about **19.1%** margin).

### Most Profitable Products
| Rank | Product | Profit | Margin |
|------|---------|--------|--------|
| 1 | Body Lotion 400ml | 117K | 31% |
| 2 | Malted Milk Drink 400g | 99K | 16% |
| 3 | Instant Coffee 100g | 94K | 16% |
| 4 | Cashew Nuts 100g | 94K | 25% |
| 5 | Laundry Powder 1kg | 93K | 34% |

- **Beverages** is the most profitable category (408K), followed by **Household** (318K) and **Personal Care** (301K).
- **Rice & Grains** has the highest sales (2.63M) but only a **10% margin**, e.g. Keeri Samba 5kg: 814K sales but just 75K profit.
- Lowest-profit products: Coconut, Wheat Flour 1kg and Sandwich Bread. 141 line items were sold at a loss.

### Highest Cost by Branch & Province
- **Branches:** Colombo 07 (1.69M), Nugegoda (1.64M), Kandy (1.25M).
- **Province:** **Western** carries about **50%** of total cost (4.47M), followed by Central and Southern.
- Cost follows sales volume, since all branches earn a similar 18–20% margin.

### Customer Segments Driving Profit
- **Age group:** 26–35 contributes the most profit (659K, about 31%), then 36–45 (463K) and 46–60 (414K). 60+ is the smallest (188K).
- **Loyalty tier:** Bronze contributes the most (1.03M, about 48%), then Silver (617K) and Gold (477K). Gold members contribute the least, which suggests the loyalty programme could be reviewed.
- **Gender:** Almost equal (Male 1.07M, Female 1.05M).

### Sales & Profit Trends
- Sales grew from **5.22M (2024)** to **5.90M (2025)**, up **13%**. Profit grew from **988K** to **1.14M**, up **15%**.
- **April and December** are peak months every year (highest: Dec 2025 with 780K sales and 126K profit), likely due to the New Year and Christmas seasons.
- **January and February** are the weakest months.
- **Saturday and Sunday** record the highest sales.

### Recommendations
- Review pricing and supplier costs for low-margin Rice & Grains and Dairy items.
- Promote high-margin Household and Personal Care products.
- Stock up and plan promotions ahead of April and December.
- Encourage Bronze customers to upgrade, and reassess Gold-tier benefits.


## How to Open the Project

1. Download or clone this repository
2. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows)
3. Open `lanka_fresh_supermarket.pbix`
4. Use the navigation buttons to explore each page

