# Page 5: Orders & Delivery Analysis

The **Orders & Delivery Analysis** page focuses on the operational side of the business. It tracks order fulfillment, delivery punctuality, booking methods, and temporal patterns of orders.

## Summary of Visuals
**Total Number of Visuals & Elements: ~15**
- **7** KPI Display Cards (Top row)
- **3** Donut Charts
- **2** Bar Charts
- **1** Matrix/HeatMap
- **2** Table Visuals
- **2** Slicers (Time Period, Search Restaurant)

---

## Detailed Visual Breakdown

### 1. KPI Display Cards (7 Visuals)
These cards track the volume and efficiency of order processing.
- **Total Orders**: Displays `154K`. *Measure Used:* `[Total Orders]`.
- **Total Buyers**: Displays `20K`. *Measure Used:* `[Total Customers]` (or Buyers).
- **Orders Per Customer**: Displays `8`. *Measure Used:* `[Orders Per Customer]`.
- **Delivered Orders**: Displays `123K`. *Measure Used:* `[Total Orders]` filtered by Status = Delivered.
- **Late Orders**: Displays `74K`. *Measure Used:* Count of orders flagged as Late.
- **Cancelled Orders**: Displays `15K`. *Measure Used:* `[Total Orders]` filtered by Status = Cancelled.
- **Late Delivery %**: Displays `48`. *Measure Used:* `[Late Delivery %]` (`[Late Orders]` / `[Total Orders]`).

### 2. Donut Charts (3 Visuals)
- **Online vs Offline Orders:** Shows orders placed online (Yes, 67.92%) vs offline (No, 32.08%).
- **Table Pre-Booking:** Shows orders with table pre-booking (No, 86.96% vs Yes, 13.04%).
- **Total Orders By Order Status:** Distribution of Delivered (80.19%), Cancelled (9.91%), and Delayed (9.9%).

### 3. Bar Charts (2 Visuals)
- **Total Orders By CostBucket:** A horizontal bar chart showing orders in Budget (88K), Mid Range (50K), and Premium (16K) buckets.
- **Total Orders by Delivery Status:** A horizontal bar chart comparing On Time (80K) vs Late (74K) deliveries.

### 4. Matrix / HeatMap Visual
- **Total Orders By Day HeatMap**
  - **Purpose:** Identifies the busiest days and months to help with operational planning.
  - **Structure:** Rows = Day Name (Monday - Sunday), Columns = Month (Jan - Dec).
  - **Measure Used:** `[Total Orders]` with conditional formatting (color scale) to create the heatmap effect.

### 5. Table Visuals (2 Visuals)
- **Orders By RatingBucket:** Shows `[Total Orders]` distributed across Average, Excellent, Good, and Low rating buckets.
- **Restaurant Name (Late Orders):** A ranking table highlighting restaurants with the highest number of late orders (e.g., Onesta 155, Cafe Coffee Day 150), allowing management to identify bottlenecks.

### 6. Interactive Slicers
- **Time Period Slicer:** A dropdown to filter all page visuals by specific timeframes.
- **Search Restaurant Slicer:** A searchable checklist to filter the entire page for specific restaurants.
