# Page 4: Cuisines & Services Analysis

The **Cuisines & Services Analysis** page evaluates the popularity and performance of different food types and dining/delivery services. It helps identify which cuisines drive the most revenue and what service types are preferred by customers.

## Summary of Visuals
**Total Number of Visuals & Elements: ~10**
- **3** KPI Display Cards
- **2** Clustered Bar Charts
- **1** Combo Chart (Line and Clustered Column)
- **1** Table/Matrix Visual
- **2** Slicers (Time Period, Search Cuisine)
- Interactive buttons for switching chart metrics

---

## Detailed Visual Breakdown

### 1. KPI Display Cards (3 Visuals)
- **Total Cuisines**: Displays `105`. *Measure Used:* `[Total Cuisines]` (Distinct count of cuisines offered).
- **Total Services**: Displays `8`. *Measure Used:* `[Total Services]` (Distinct count of service types like Delivery, Dine-out, etc.).
- **Total Restaurants**: Displays `43K` (Top Right). *Measure Used:* `[Total Restaurants]`.

### 2. Table / Matrix Visual
- **Cuisine Popularity**
  - **Purpose:** Ranks cuisines by overall performance metrics.
  - **Columns:** Cuisine, Restaurants (Count), Orders, Avg Rating, Total Revenue.
  - **Measures Used:** `[Total Restaurants]`, `[Total Orders]`, `[Avg Rating]`, `[Total Revenue]` grouped by `Cuisine`.

### 3. Combo Chart (Line and Column)
- **Total Revenue vs Orders vs Customers**
  - **Purpose:** Compares three major metrics against different restaurant service types simultaneously.
  - **Axes:** X-Axis = Service Type (Delivery, Dine-out, Cafes, etc.), Primary Y-Axis = Total Revenue, Secondary Y-Axis = Total Orders / Total Customers.
  - **Measures Used:** `[Total Revenue]` (Bars), `[Total Orders]` (Line), `[Total Customers]` (Line) by `Service Type`.

### 4. Clustered Bar Charts (2 Visuals)
- **Total Restaurants By Cuisine**
  - **Purpose:** Shows the distribution of restaurants across various cuisines (North Indian, Chinese, etc.).
  - **Measure Used:** `[Total Restaurants]` sliced by `Cuisine`.
  - **Note:** Has interactive buttons to switch the view to "Total Customers By Cuisine" or "Total Orders By Cuisine".

- **Total Customers By Restaurant Service**
  - **Purpose:** Highlights customer preference for services like Delivery vs. Dine-out vs. Cafes.
  - **Measure Used:** `[Total Customers]` sliced by `Service Type`.
  - **Note:** Has interactive buttons to switch the view to "Total Revenue By Restaurant Service" or "Total Orders By Restaurant Service".

### 5. Interactive Slicers
- **Time Period Slicer:** A dropdown to filter all page visuals by specific timeframes.
- **Search Cuisine Slicer:** A text search box allowing users to filter the page for a specific cuisine.
