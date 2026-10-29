# 💰 Sales Dashboard 2023 | Tableau

An interactive **Tableau dashboard** for **comparative sales analysis: Current Year (CY) vs Previous Year (PY)**. The user can **pick any year as the Current Year**, and the dashboard compares it with the year before. It tracks total sales, profit and quantity sold, shows which product sub-categories perform best, and highlights weekly sales and profit trends.

**Live Dashboard:** [View on Tableau Public](https://public.tableau.com/views/ComparativePerformance-SalesDashboard/SalesDashboard?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

---

## 📌 Project Objective

- Compare sales performance between the Current Year and the Previous Year
- Let users choose any year as the Current Year for a flexible comparison
- Track total sales, profit and quantity along with their growth vs PY
- Find which product sub-categories bring the most sales and profit, and which ones lose money
- Understand weekly sales and profit patterns across the year

---

## 📊 Dashboard Components

| Component | What it shows |
|---|---|
| **Year Selection** | User picks any year as the Current Year (CY); it is compared with the Previous Year (PY) |
| **Total Sales** | Total sales for the selected year, % change vs PY, and a monthly CY vs PY trend line |
| **Total Profit** | Total profit for the selected year, % change vs PY, and a monthly CY vs PY trend line |
| **Total Quantity** | Total quantity sold, % change vs PY, and a monthly CY vs PY trend line |
| **Sales & Profit by Sub-Category** | Bar chart comparing PY and CY sales for each sub-category, next to a CY profit chart (colour shows profit level, loss-making sub-categories fall below zero) |
| **Weekly Trends** | Weekly sales and profit for the year with average reference lines |
| **Navigation Button** | Button linking to the companion **Customer Dashboard** |

---

## 🔢 Key Metrics (Current Year selected: 2023)

| Metric | Value | vs Previous Year |
|---|---|---|
| Total Sales | **₹733K** | ▲ 20.36% |
| Total Profit | **₹286K** | ▲ 14.24% |
| Total Quantity | **37,873** | ▲ 26.83% |
| Profit Margin (Profit ÷ Sales) | **~39%** | Slightly lower than PY (~41%)* |

---

## 💡 Key Insights

### 1. Strong overall growth
- Sales grew **20.36%**, profit grew **14.24%** and quantity sold grew **26.83%** compared to the previous year.
- **Quantity is growing faster than sales, and sales faster than profit.** This means the business is selling more units, but profit per unit is under some pressure, and the profit margin dipped slightly.

### 2. Seasonal pattern
- **Sales and quantity were lowest around February** and highest around **November**, so the second half of the year is much stronger than the start.
- **Profit peaked around March and was lowest around April**, which means profit does not always follow sales month by month.

### 3. Sub-category performance
- **Phones** are among the biggest sales contributors, and **Chairs, Binders and Storage** also bring high sales.
- **Copiers** give the **highest profit** of all sub-categories, even though their sales are lower than Phones.
- **Tables** have high sales but are the biggest **loss-making** sub-category in CY, a clear case where heavy sales do not mean profit.
- A few other sub-categories (such as **Machines, Bookcases and Supplies**) show small losses or very low profit.
- Action idea: review pricing and discounts on Tables and other loss-making products, and push high-margin sub-categories like Copiers and Phones.

### 4. Weekly trends
- Weekly sales average around **₹14K**, with the highest weeks coming in the **last part of the year (roughly weeks 40 to 50)**.
- Weekly profit is mostly steady, with one big spike around **week 12 to 13** and a few weeks where profit drops below zero.

---

## 🛠️ Tools & Skills Used

- **Tableau** (Desktop / Public): dashboard design, calculated fields and parameters
- Current Year vs Previous Year comparison with a user-selectable year
- KPI cards with % change vs PY and trend (sparkline) charts
- Bar charts with a dual-axis layout for sales and profit by sub-category
- Weekly trend charts with average reference lines
- Dashboard navigation button between dashboards

---

## 🚀 How to Use

1. Download or clone this repository.
2. Open the `.twbx` file in **Tableau Desktop** or **Tableau Public**.
3. Select the year you want as the **Current Year** to compare it with the previous year.
4. Hover over the charts to see details and use the **Customer Dashboard** button to switch to the customer view.

---

## 👤 Author

**Deepak**
English Language Trainer turned Data Analyst

📫 Connect me through:
      1.  Phone: +91-7607146249
      2.  Email: coachdeepaksingh@gmail.com

---

⭐ If you found this project useful, please give it a star!
