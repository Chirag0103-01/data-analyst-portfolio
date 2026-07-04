# data-analyst-portfolio

👋 Hi, I'm Chirag

Data Analyst | Python • SQL • Power BI • Pandas • Machine Learning

👨‍💻 About Me

B.Tech graduate and fresher Data Analyst with hands-on project experience in **Python, SQL, and Power BI** across retail, automotive, sports, and e-commerce domains.

I enjoy turning raw data into clear, useful insights — whether that is finding which IPL team wins the most after choosing to field first, spotting that 73% of non-subscribing customers still drive the majority of a retailer's revenue, or showing that higher discounts actually hurt profit margins.

What I work with:


| 🐍 **Python** | Pandas, NumPy, Matplotlib, Seaborn |
| 🗄️ **SQL** | Joins, Aggregations, Window Functions (RANK, LAG, NTILE) |
| 📊 **Power BI** | Dashboards, KPI Cards, Slicers, Drill-through Visuals |
| 📈 **Excel** | Pivot Tables, Charts, Data Cleaning |
| 🤖 **ML & Stats** | Regression, Hypothesis Testing, Feature Engineering |

About Project

1. 🛍️ Customer Shopping Behaviour Analysis
> **Tools:** Python · SQL · Pandas · Power BI

Analyzed **3,900 customer records** across 18 variables — age, gender, category, season, payment method, discount usage, subscription status, and purchase frequency — to find what drives retail buying behaviour.

Key Findings:
- 🏆 Clothing is the most purchased category with **1,737 orders (44.5% of total transactions)**
- 📅 Fall is the highest-revenue season at **$60,018** — Spring ($58,679) and Winter ($58,607) are close behind
- 💡 **73% of customers are non-subscribers** but still make up most of the revenue — a clear opportunity to grow the loyalty programme
- 🏷️ Customers who used a discount spent slightly **less on average ($59.28) vs those who did not ($60.13)** — discounts attract deal-seekers, not high-value buyers

📂 [View Project Files](./03-ipl-cricket-analysis)

 2. 🚗 Cars24 Used Car Price Analysis
> **Tools:** Python · SQL · Pandas · Power BI

Analyzed **10,000+ used-car listings** from Cars24.com to understand how age, mileage, fuel type, transmission, and ownership history affect resale price — with insights to support pricing strategy.

**Key Findings:**
- 📉 Car age has a clear negative correlation with price — depreciation is steepest in the first few years, then slows
- ⛽ Diesel cars and SUV/Luxury body types command noticeably higher resale prices
- 👥 Each additional previous owner is linked to a measurable price drop
- 🔧 Feature engineering (car age, price-per-km) improved the analysis beyond raw variables

📂 [View Project Files](./03-ipl-cricket-analysis)

### 3. 🏏 IPL Cricket Data Analysis (2008–2024)
> **Tools:** Python · SQL · Pandas · Power BI

Analyzed **16+ seasons of IPL data** — 900+ matches and 120,000+ ball-by-ball deliveries — to uncover team performance patterns, top batting and bowling records, toss strategy impact, and season-wise scoring trends.

**Key Findings:**
- 🏆 Mumbai Indians and Chennai Super Kings lead in titles and overall win rates
- 🎯 Toss winners win the match ~52–56% of the time — a real but not decisive advantage
- 🏏 Teams that choose to **field first** after winning the toss have a higher win rate — chasing is the preferred modern T20 strategy
- 📈 Total sixes per season show a clear upward trend from 2008 to 2024 — batting is getting more aggressive every year
- 🏟️ Wankhede Stadium (Mumbai) is consistently one of the highest-scoring venues in the tournament

📂 [View Project Files](./03-ipl-cricket-analysis)

---

### 4. 📦 Sales Performance Dashboard
> **Tools:** Power BI · SQL · Excel

Built an **interactive multi-KPI Power BI dashboard** tracking revenue, profit margin, growth rate, regional performance, and top products — using the Sample Superstore retail dataset (~9,800 orders across 4 years).

**Key Findings:**
- 💸 Higher discounts strongly correlate with lower profit (correlation: **-0.70**) — clear evidence for setting discount thresholds
- 🌍 The East region leads in total sales; performance varies significantly across regions and segments
- 🏪 Technology has the highest average order value; Office Supplies generates the most volume
- 📅 Month-over-month growth calculated using SQL **LAG() window function** for trend tracking

📂 [View Project Files](./04-sales-performance-dashboard)

---

### 5. 🛒 E-Commerce Customer Segmentation (RFM)
> **Tools:** Python · SQL · Pandas · Power BI

Applied **RFM (Recency, Frequency, Monetary) segmentation** on 1M+ real transaction records from a UK-based online retailer (UCI Online Retail II dataset) to classify customers into actionable groups for retention and growth.

**Key Findings:**
- 🥇 **Champions** (recent, frequent, high-spending) — the clearest priority for loyalty investment
- ⚠️ A meaningful **"At Risk (High Value)"** group — customers who used to spend a lot but haven't purchased recently, worth a targeted win-back campaign
- 📊 Loyal Customers are the largest group by count but not always the top revenue contributors — volume ≠ value
- 🔢 RFM scores built using **NTILE() window function** in SQL and quantile binning in Python

📂 [View Project Files](./05-ecommerce-customer-segmentation)










