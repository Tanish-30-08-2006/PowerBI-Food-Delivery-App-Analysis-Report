# Page 2: Customer Analytics

The **Customer Analytics** page focuses on understanding user behavior, segmentation, and retention. It provides deep insights into customer types, their spending habits, and geographical distribution.

## Summary of Visuals
**Total Number of Visuals & Elements: ~12**
- **5** KPI Display Cards (Top row)
- **2** Donut Charts
- **1** Clustered Bar Chart
- **2** Table/Matrix Visuals
- **2** Additional KPI Cards (Per Customer Summary)
- **1** Slicer (Time Period)
- **1 set** of Interactive buttons for switching chart metrics

---

## Detailed Visual Breakdown

### 1. KPI Display Cards (5 Visuals)
These cards track overall customer acquisition and retention metrics.
- **Total Customers**: Displays `20K`. *Measure Used:* `[Total Customers]` (Distinct count of customers).
- **Orders Per Customer**: Displays `7.69`. *Measure Used:* `[Orders Per Customer]` (`[Total Orders]` / `[Total Customers]`).
- **Repeat Customers**: Displays `8052`. *Measure Used:* `[Repeat Customers]` (Count of customers with >1 order).
- **Repeat Customer %**: Displays `40%`. *Measure Used:* `[Repeat Customer %]` (`[Repeat Customers]` / `[Total Customers]`).
- **Total Restaurants**: Displays `43K`. *Measure Used:* `[Total Restaurants]`.

### 2. Donut Charts (2 Visuals)
- **Customers By Type**
  - **Purpose:** Segments the customer base into new vs. returning vs. premium.
  - **Categories:** New (10K, 49.73%), Returning (8K, 40%), Premium (2K, 10.02%).
  - **Measure Used:** `[Total Customers]` categorized by `CustomerType`.

- **Customers By CostBucket**
  - **Purpose:** Shows how customers are distributed based on their typical spending range.
  - **Categories:** Budget, Mid Range, Premium.
  - **Measure Used:** `[Total Customers]` categorized by `Cost Bucket`.

### 3. Clustered Bar Chart
- **Title:** Total Customers By Customer Type
- **Purpose:** A bar chart representation of customer segmentation, allowing for easy comparison.
- **Axes:** Y-Axis = Customer Type, X-Axis = Total Customers.
- **Data Shown:** New (9.9K), Returning (8.0K), Premium (2.0K).
- **Measure Used:** `[Total Customers]` sliced by `Customer Type`.
- **Note:** Includes interactive buttons on the right to dynamically change the metric displayed in this chart (e.g., switch from "Total Customers By Customer Type" to "Total Orders" or "Total Revenue").

### 4. Table / Matrix Visuals (2 Visuals)
- **Summary By Customer Type**
  - **Purpose:** A detailed tabular view of revenue and order performance for each customer segment.
  - **Columns:** CustomerType, Total Revenue, Total Orders, Avg Order Value.
  - **Measures Used:** `[Total Revenue]`, `[Total Orders]`, `[Avg Order Value]` grouped by `CustomerType`.
  
- **Customers By City**
  - **Purpose:** Ranks cities by the number of unique customers, highlighting the most popular locations.
  - **Columns:** City, Customers (e.g., BTM: 1875, HSR: 913).
  - **Measure Used:** `[Total Customers]` grouped by `City`.

### 5. Per Customer Summary (2 Sub-Cards)
Located in the bottom middle, this section breaks down averages per individual customer:
- **Average Revenue**: `6.34K`. *Measure Used:* `[Total Revenue]` / `[Total Customers]`.
- **Average Orders**: `7.69`. *Measure Used:* Matches the "Orders Per Customer" KPI.

### 6. Interactive Slicers & Toggles
- **Time Period Slicer:** A dropdown slicer to filter all page visuals by specific timeframes (default: All).
- **Metric Toggle Buttons:** Located next to the Clustered Bar Chart to dynamically switch the chart's values (Total Orders, Total Revenue, Total Customers).
