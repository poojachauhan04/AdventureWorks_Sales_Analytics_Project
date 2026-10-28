# AdventureWorks Sales Analytics 🚴

An end-to-end Power BI project on 25K orders and $24.9M in revenue from AdventureWorks, a cycling and accessories company, to find out whether sales hit target, which countries, customers, and products drive revenue and profit, and where returns and seasonality hurt performance.

<img width="2400" height="720" alt="banner" src="https://github.com/user-attachments/assets/34677142-001a-44c8-9620-9ab6c5f70f58" />

---

## 📌 Project Overview

This project is framed as a consulting-style case study. The business scenario is fictional, but the data is the well-known AdventureWorks sample dataset from Microsoft.

A sales team has orders, customers, products, returns, and regional data, but no single view of whether revenue is on target, who the best customers are, which products make money, and what causes returns. This project turns that data into a 4-page interactive Power BI dashboard with a navigation panel, synced slicers, and written insights and recommendations on the home page.

**Result at a glance**

| Metric | Value |
|---|---|
| Total Orders | 25K |
| Total Revenue | $24.9M |
| Total Profit | $10.6M |
| Profit Margin | 42.47% |
| Revenue Target | $25.4M (missed by $481.8K, about 2%) |
| Revenue MoM Growth | 7.91% |
| Total Customers | 18K |
| Repeat Customer % | 68.93% |
| Average Order Value | $990.09 |
| Units Sold | 84K |
| Return Rate | 7.26% (about 2K returned orders) |
| Products Sold | 130 |

---

## 🛠️ Tech Stack

- **Data Visualization & Business Intelligence:** Power BI (DAX measures, synced slicers, page navigation, reset-filter bookmark)
- **Analytical Concepts:** KPI Tracking, Target vs Actual Analysis, Customer Segmentation, Product Performance, Return Analysis, Seasonality Analysis

---

## ❓ Business Problems Solved

1. **Is revenue on target?** Compared current revenue with previous month and with the revenue target, by country.
2. **Which countries and regions drive revenue?** Ranked six countries and three continents by revenue and units sold.
3. **Who are the best customers?** Analysed orders and revenue by income group, occupation, and education, plus repeat-customer rate.
4. **Which products and subcategories make money?** Compared top products by units sold and top subcategories by profit margin.
5. **What is being returned and why does it matter?** Found the top 10 returned products and the overall return rate.
6. **When does demand rise and fall?** Tracked monthly revenue and orders to find seasonal peaks and slumps.

**Who uses the dashboard:** executives (overall health vs target), sales managers (country performance), marketing (customer segments and seasonality), and product and operations teams (returns and margins).

---

## 🗂️ Dashboard Pages

| Page | What it shows |
|---|---|
| Home Page | 8 KPI cards, key insights, recommendations, and slicers for Region, Home Owner, Gender, and Country |
| Executive Summary | Revenue vs target and previous month by country, target-achieved flag, and a monthly revenue tracking chart. Slicers: Category, Year, Month |
| Customer & Sales Overview | Orders by income group, revenue and profit by occupation and education, and revenue by country |
| Product Performance | Top 10 returned products, top 5 products by units sold, unit share by continent, top 5 subcategories by profit margin, and orders by month |

**How the target works:** the revenue target is **10% above the previous month's revenue** (for example, $23.1M previous month × 1.10 = $25.4M target). Profit margin is profit divided by revenue.

---

## 📸 Dashboard Preview

**Home Page**
<img width="3075" height="2027" alt="dashboard_1_home" src="https://github.com/user-attachments/assets/c7725281-a8db-4cd9-9381-53e5b72d321c" />

**Executive Summary**
<img width="3075" height="2027" alt="dashboard_2_executive_summary" src="https://github.com/user-attachments/assets/15afb905-bc0d-4414-8eb4-5f5421f38b82" />

**Customer & Sales Overview**
<img width="3075" height="2027" alt="dashboard_3_customer_and_sales" src="https://github.com/user-attachments/assets/644353f2-65af-4e3b-b3b5-77e2ddb183de" />

**Product Performance**
<img width="3075" height="2027" alt="dashboard_4_product_performance" src="https://github.com/user-attachments/assets/b0294bcb-a44d-43c1-bd06-fc600b1cbcd8" />

---

## 💡 Key Insights

- **Target missed:** revenue of $24.9M fell $481.8K short of the $25.4M target. All 6 countries missed their targets, with Australia the furthest behind (-$245K) and the United States next (-$104K).
- **Strong profit:** profit was $10.6M at a 42.47% margin, and revenue grew 7.91% over the previous month.
- **Concentrated revenue:** the United States ($7.9M) and Australia ($7.4M) together bring in about 62% of revenue. Bikes alone make up about 95% of revenue.
- **Seasonality:** revenue peaks in June, drops sharply from July to November, and recovers in December. Orders fall to under 1K in July from about 2.7K in May and June.
- **Loyal customers:** 68.93% of customers are repeat buyers, with an average order value of $990.09.
- **Customer mix:** Average-income (11.6K) and Low-income (10.3K) customers place most orders. Professionals bring the most revenue ($8.5M), and Bachelors-degree holders lead education groups ($8.4M revenue, $3.6M profit).
- **Regional units:** North America sells 48.37% of units, Europe 30.3%, and Pacific 21.33%.
- **Margins:** Tires and Tubes (77.73%) and Helmets (63.66%) have the highest margins, ahead of Mountain Bikes (45.79%), Road Bikes (38.70%), and Touring Bikes (37.84%).
- **High returns:** the return rate is 7.26%. Water Bottle - 30 oz. (155), Patch Kit/8 Patches (95), and Mountain Tire Tube (93) are the most returned products, and they are also among the top sellers.

---

## ✅ Business Recommendations

➢ **Close the Revenue Gap** → Focus on Australia and the United States, which account for most of the shortfall, and set monthly targets for each country.

➢ **Fix the Mid-Year Slump** → Run promotions and bundles from July to November, when orders and revenue drop the most.

➢ **Diversify Beyond Bikes** → Bundle accessories and clothing with bike sales, since bikes are about 95% of revenue.

➢ **Cut Returns** → Audit quality and packaging of the most returned items, such as water bottles, patch kits, and tire tubes.

➢ **Grow Customer Value** → Reward repeat buyers and upsell premium bikes to raise the $990 average order value.

➢ **Protect Profit** → Keep Road Bikes and Mountain Bikes well stocked, and promote high-margin Tires and Tubes and Helmets.

---

## ⚠️ Limitations

- The data is the AdventureWorks sample dataset, so the findings show how the analysis works, not the results of a real business.
- Revenue is a recorded sales amount, and profit depends on the cost values in the dataset.
- The revenue target is a rule-based target (10% above the previous month), not a target set by the business.
- Return rate and returned-product counts come from the returns data and show how often items were sent back, not the reasons for the returns.
- Customer segments (income, occupation, education) describe who buys, but the dataset does not show why.

---
