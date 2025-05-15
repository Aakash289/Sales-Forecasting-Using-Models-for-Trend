# Sales-Forecasting-Using-Models-for-Trend

This project performs sales forecasting using historical sales data and Prophet time series model.

📁 Dataset Description

Date Range: March 2020 – February 2025

Columns Included:

Order ID

Amount (Sales)

Profit

Quantity

Category, Sub-Category

Payment Mode

Order Date

Customer Info

Location (State, City)

🎯 Project Objective
Forecast monthly sales for the next 6 months

Visualize historical trends and seasonality

Derive actionable insights for business decisions

🧰 Libraries Used
pandas – Data manipulation

matplotlib, seaborn – Data visualization

prophet – Time series forecasting

🧠 Model Used: Prophet
Prophet is a robust time series model that handles:

Trends

Seasonalities (monthly, yearly)

Uncertainty intervals

It automatically detects trend changepoints and models seasonality without manual tuning, making it well-suited for business time series forecasting.

🔮 Forecast Results (March 2025 – August 2025)

| Month           | Insight Summary                                                                       |
| --------------- | ------------------------------------------------------------------------------------- |
| **March 2025**  | Model predicts steady sales and serves as the post-training baseline.                 |
| **April 2025**  | Shows an upward trend; may indicate pre-peak buying season.                           |
| **May 2025**    | Stable continuation; ideal for maintaining existing strategies.                       |
| **June 2025**   | Significant growth with wider confidence interval — potential for high return.        |
| **July 2025**   | **Highest forecasted sales** — critical month for promotions and inventory readiness. |
| **August 2025** | Sharp predicted decline — plan exit promotions or clearance events.                   |

📊 Visual Insights
✅ Monthly Sales Trend
Historical sales show high volatility and seasonal spikes (likely from promotions or holiday cycles).

✅ Forecast with Confidence Interval
Sales are expected to grow from March to July 2025.

Confidence intervals widen, indicating growing uncertainty as we look further into the future.

✅ Prophet Decomposition
Trend: Sales increasing steadily over time.

Seasonality: Recurring patterns peaking around mid-year (June–July).

✅ Month-over-Month Growth
Sales are expected to grow by 20–35% from April to July.

August sees a forecasted drop (~60%), marking the end of the seasonal high.

📌 Business Insights
📦 Inventory Planning
Increase production and inventory in May–July to meet rising demand.

Reduce orders in August and consider clearance strategies.

📈 Marketing Strategy
Focus ad spend in June and July.

Launch retention and referral programs before the August slowdown.

💰 Budgeting & Resource Allocation
Allocate more sales team bandwidth and budget to Q2/Q3.

Use Prophet’s confidence intervals to buffer risk in uncertain months.

🧪 Strategic Testing
Use lower forecast months like March or August to test new pricing or bundling strategies.


