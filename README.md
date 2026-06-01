# 📊 Task 2 – Data Visualization and Storytelling

**Internship:** Data Analyst Internship – Elevate Labs  
**Task:** Task 2 – Data Visualization and Storytelling  
**Tool Used:** Power BI Desktop  
**Dataset:** Superstore Sales Dataset (300 orders, 2022–2024)

---

## 🎯 Objective

Create visualizations that convey a compelling business story using the Superstore sales dataset — focusing on sales performance, profitability, and regional trends.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `superstore_dataset .csv.xlsx` | The dataset used for analysis (300 rows, 9 columns) |
| `Screenshot 2026-06-01 185014.png` | Power BI Dashboard screenshot |

---

## 📌 Dashboard Overview

The Power BI dashboard was built to answer key business questions at a glance.

### KPI Cards (Top Row)
| Metric | Value |
|--------|-------|
| 💰 Total Sales | **$156.07K** |
| 📈 Total Profit | **$7.82K** |
| 🧾 Total Orders | **300** |

### Visualizations Included

1. **Line Chart – Sum of Sales by Order Date**  
   Tracks sales trends over time (2022–2024). Reveals seasonal spikes and overall growth pattern.

2. **Bar Chart – Sum of Profit by Region**  
   West leads in profitability ($2,419), followed by South, East, and Central.

3. **Bar Chart – Sum of Sales by Category**  
   Furniture ($54.6K) and Office Supplies ($53.3K) are neck-and-neck; Technology trails slightly at $48.2K.

4. **Pie Chart – Sum of Sales by Segment**  
   Corporate (36.23%) and Consumer (35.69%) dominate; Home Office accounts for 28.07%.

5. **Slicers (Filters)**  
   Interactive filters for Category, Sub-Category, and Segment allow dynamic exploration of the data.

---

## 🔍 Key Business Insights

- **West region** is the most profitable — ideal for increased investment or campaign focus.
- **Central region** has the lowest profit ($1,488) despite decent sales — possible pricing or cost issue.
- **Furniture** generates the highest sales but should be analyzed for profit margins separately.
- **Corporate segment** drives the most revenue — a key customer base to retain and grow.
- **Sales trend** shows consistent growth from 2022 to 2024 with notable peaks, likely seasonal demand.

---

## 🛠 Steps Followed

1. Loaded the Superstore dataset into Power BI Desktop.
2. Cleaned and verified data types (dates, numbers, categories).
3. Created KPI cards for Sales, Profit, and Order Count.
4. Built charts for each business dimension: time, region, category, segment.
5. Added slicers for interactive filtering.
6. Applied a consistent purple/pink color theme for visual coherence.
7. Arranged the layout for storytelling: KPIs → Trends → Breakdowns.

---

## 💡 Design Choices

- **Bar charts** used for category/region comparisons (easy to compare values).
- **Line chart** used for time-series sales trend (shows change over time).
- **Pie chart** used for segment share (limited to 3 segments — appropriate use case).
- **Consistent color palette** to avoid visual clutter.
- **Minimal text** — visuals speak for themselves with clear titles and axis labels.

---

## ❓ Interview Q&A

**1. What is the importance of data visualization?**  
It transforms raw numbers into understandable visuals, enabling faster decision-making and uncovering patterns that are invisible in spreadsheets.

**2. When do you use a pie chart vs bar chart?**  
Pie charts work for part-to-whole relationships with few categories (≤5). Bar charts are better for comparing values across many categories or when differences are subtle.

**3. How do you make visualizations more engaging?**  
Use consistent colors, add context through titles/labels, highlight key insights, use interactivity (slicers/filters), and keep the layout clean.

**4. What is data storytelling?**  
It's the process of combining data, visuals, and narrative to communicate insights in a way that drives understanding and action.

**5. How do you avoid misleading visualizations?**  
Start axes at zero, avoid cherry-picking data, use appropriate chart types, label data clearly, and provide context (time period, sample size).

**6. What are best practices in dashboard design?**  
Place KPIs at the top, use a grid layout, maintain visual hierarchy, limit colors, ensure mobile responsiveness, and prioritize insights over decoration.

**7. What tools have you used for visualization?**  
Power BI (used in this task) — also familiar with Excel charts and Python (matplotlib/seaborn).

---

## 📸 Dashboard Preview

![Power BI Dashboard](Screenshot%202026-06-01%20185014.png)
 
