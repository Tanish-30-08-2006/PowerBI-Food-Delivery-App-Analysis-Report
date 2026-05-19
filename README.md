## Table of Contents

* [1. Project Overview](#1-project-overview)
    * [1.1 The Problem Statement](#11-the-problem-statement)
    * [1.2 Business Requirements](#12-business-requirements)
    * [1.3 Project Objectives and Scope](#13-project-objectives-and-scope)
* [2. Data Architecture and Preparation](#2-data-architecture-and-preparation)
* [3. Data Dictionary and Business Logic](#3-data-dictionary-and-business-logic)
* [4. Dashboard Anatomy](#4-dashboard-anatomy)
* [5. Key Insights and Business Recommendations](#5-key-insights-and-business-recommendations)
* [6. Technical Setup and Usage Instructions](#6-technical-setup-and-usage-instructions)
* [7. Future Scope and Enhancements](#7-future-scope-and-enhancements)

---

## 1. Project Overview

### 1.1 The Problem Statement
* Data for customers, restaurants, and deliveries is currently scattered.
* Management cannot easily track sales trends or identify poor restaurant performance.
* The exact reasons for late deliveries are unclear.
* The company requires a single, interactive dashboard to consolidate this data and support quick business decisions.

### 1.2 Business Requirements
The management team outlined the following specific needs for the dashboard:

* [cite_start]**Executive View:** A high-level summary of total revenue [cite: 10][cite_start], total orders [cite: 13][cite_start], and average order value[cite: 15]. [cite_start]It must include month-by-month trend lines[cite: 34, 35].
* **Customer Tracking:** Split customers by type, specifically New, Returning, and Premium[cite: 148]. [cite_start]Group them by spending habits such as Budget, Mid Range, and Premium[cite: 159]. [cite_start]Calculate the repeat customer percentage[cite: 128].
* **Restaurant Details:** A table showing every restaurant with their revenue, total orders, average rating, and late orders[cite: 228, 229, 230]. [cite_start]It must include a search bar to easily find specific restaurants[cite: 273, 281].
* **Food Categories:** A list of popular cuisines like North Indian, Chinese, and Fast Food[cite: 370, 376, 388]. [cite_start]It needs to show the number of orders and total revenue for each food type[cite: 367, 368].
* **Delivery and Operations:** Track order status to see if items are Delivered, Cancelled, or Delayed[cite: 549, 550, 553]. [cite_start]Include a daily and monthly heatmap to identify peak ordering times for driver planning[cite: 543, 544].

### 1.3 Project Objectives and Scope

**In Scope:**
* Connect and clean raw business data.
* Build five specific dashboard pages: Executive Overview, Customer Analytics, Restaurant Performance, Cuisines & Services Analysis, and Orders & Delivery Analysis[cite: 30, 31, 124, 125, 126, 127].
* Add filters for time periods and city names[cite: 32, 46].

**Out of Scope:**
* Real-time data tracking. The dashboard relies on historical data.
* Predictive artificial intelligence modeling. The focus is strictly on current and past metrics.