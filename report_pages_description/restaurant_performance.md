# Page 3: Restaurant Performance

The **Restaurant Performance** page provides a deep dive into how individual restaurants are performing across the platform. It highlights revenue generation, customer satisfaction (ratings), and operational metrics like late orders.

## Summary of Visuals
**Total Number of Visuals & Elements: ~9**
- **5** KPI Display Cards (Top row)
- **1** Donut Chart
- **1** Table/Matrix Visual
- **2** Slicers (Time Period, Search Restaurant)

---

## Detailed Visual Breakdown

### 1. KPI Display Cards (5 Visuals)
These cards track high-level metrics related to restaurant operations and satisfaction.
- **Total Restaurants**: Displays `43K`. *Measure Used:* `[Total Restaurants]`.
- **Average Rating**: Displays `3.68`. *Measure Used:* `[Average Rating]` (Average of all customer ratings).
- **Revenue Per Restaurant**: Displays `2.93K`. *Measure Used:* `[Revenue Per Restaurant]` (`[Total Revenue]` / `[Total Restaurants]`).
- **Average Votes**: Displays `278`. *Measure Used:* `[Average Votes]` (Average number of votes/reviews per restaurant).
- **Total Revenue**: Displays `127M`. *Measure Used:* `[Total Revenue]`.

### 2. Donut Chart
- **Customers Ratings**
  - **Purpose:** Shows the distribution of customer feedback across different rating buckets.
  - **Categories:** Average (81K, 65.34%), Excellent (32K, 25.88%), Good (7K, 6.03%), Low.
  - **Measure Used:** Count of ratings or `[Total Orders]` categorized by the `Rating Bucket` dimension.

### 3. Table / Matrix Visual
- **Restaurant Summary**
  - **Purpose:** A comprehensive, scrollable table detailing the performance of every restaurant on the platform.
  - **Columns:** Restaurant Name, Revenue, Total Orders, Avg Order Value, Revenue YTD (Year-To-Date), Late Orders, Avg Rating.
  - **Measures Used:** `[Total Revenue]`, `[Total Orders]`, `[Avg Order Value]`, `[Revenue YTD]`, `[Late Orders]`, `[Avg Rating]` grouped by `Restaurant Name`.

### 4. Interactive Slicers
- **Time Period Slicer:** A dropdown slicer to filter visuals by specific timeframes (default: All).
- **Search Restaurant Slicer:** A searchable checklist slicer that allows users to filter the entire page's data for one or more specific restaurants (e.g., searching for "Cafe Coffee Day" or "Domino's Pizza").
