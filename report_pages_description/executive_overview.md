# Page 1: Executive Overview

The **Executive Overview** page is designed to provide high-level, at-a-glance insights into the overall business performance of the Food Delivery App. It highlights top-line metrics and trends critical for business leaders.

## Summary of Visuals
**Total Number of Visuals & Elements: ~11**
- **5** KPI Display Cards
- **1** Donut Chart
- **1** Area/Line Chart (Trend Analysis)
- **1** Bar Chart
- **1** Table/Matrix
- **1** Slicer (Time Period)
- **1 set** of Navigation & View Toggle Buttons

---

## Detailed Visual Breakdown

### 1. KPI Display Cards (5 Visuals)
These cards present the most critical high-level business measures.
- **Total Revenue**: Displays `94M`. *Measure Used:* `[Total Revenue]` (Sum of order amounts).
- **Total Orders**: Displays `114K`. *Measure Used:* `[Total Orders]` (Count of unique orders).
- **Total Customers**: Displays `15K`. *Measure Used:* `[Total Customers]` (Distinct count of customers).
- **Avg Order Value**: Displays `823.52`. *Measure Used:* `[Avg Order Value]` (`[Total Revenue]` / `[Total Orders]`).
- **Total Restaurants**: Displays `43K`. *Measure Used:* `[Total Restaurants]` (Distinct count of restaurants).

### 2. Donut Chart
- **Title:** Total Orders by OrderStatus
- **Purpose:** Shows the distribution of successful, delayed, and canceled orders.
- **Data Categories:** Delivered (80.14%, 91K), Cancelled (9.96%, 11K), Delayed (9.9%, 11K).
- **Measure Used:** `[Total Orders]` categorized by the `OrderStatus` dimension.

### 3. Area/Line Chart (Trend Analysis)
- **Title:** Revenue Trend (Toggleable to Orders Trend)
- **Purpose:** Tracks the monthly trend of revenue (or orders) over the year to identify seasonality or growth patterns.
- **Axes:** X-Axis = Month (Jan-Dec), Y-Axis = Total Revenue.
- **Measure Used:** `[Total Revenue]` or `[Total Orders]` over a Date Hierarchy (Month).
- **Note:** Includes interactive buttons on the right side to switch between "Revenue Trend" and "Orders Trend".

### 4. Clustered Bar Chart
- **Title:** Revenue By City
- **Purpose:** Ranks cities based on the revenue they generate, highlighting the top-performing locations.
- **Top Cities Shown:** BTM (11.8M), HSR (5.8M), Whitefield (5.0M), etc.
- **Axes:** Y-Axis = City Name, X-Axis = Total Revenue.
- **Measure Used:** `[Total Revenue]` sliced by `City Name`.
- **Note:** Has a toggle group attached to switch between "Bar View" and "Matrix View".

### 5. Table / Matrix Visual
- **Title:** Summary By Restaurant
- **Purpose:** Provides a detailed tabular breakdown of performance metrics for top individual restaurants.
- **Columns:** Restaurant, Total Revenue, Total Orders, Avg Order Value.
- **Measures Used:** `[Total Revenue]`, `[Total Orders]`, `[Avg Order Value]` grouped by `Restaurant Name`.

### 6. Interactive Slicers & Toggles
- **Time Period Slicer:** A dropdown slicer to filter all page visuals by specific timeframes (default: All).
- **Page Navigation Menu:** Buttons located at the top to navigate to other pages: Customer Analytics, Restaurant Performance, Cuisines & Services Analysis, and Orders & Delivery Analysis.
