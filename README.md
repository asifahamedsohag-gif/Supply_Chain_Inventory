# 📦 Inventory, Shipment Performance & Stock Replenishment Analysis

## 📊 Supply Chain Inventory Dashboard

An interactive **Supply Chain Inventory & Shipment Performance Dashboard** designed to analyze inventory levels, shipment performance, stock replenishment requirements, and delivery delays across different product categories.

The dashboard provides a consolidated view of key supply chain KPIs to help identify inventory risks, monitor shipment performance, and understand stock replenishment requirements.

---

## 🖼️ Dashboard Preview

![Supply Chain Inventory Dashboard](./image/Supply%20Chain.png)

---

## 🎯 Project Objective

The primary objective of this project is to analyze supply chain and inventory data to answer key business questions such as:

- How much inventory is currently available?
- Which product categories hold the most stock?
- Which categories are understocked?
- How well are shipments performing?
- What percentage of shipments are delivered on time?
- How many shipment days are delayed?
- Which categories require stock replenishment?
- How does inventory compare with reorder points?
- How do shipment delays change over time?

The dashboard transforms raw supply chain data into an easy-to-understand visual format for inventory and shipment performance analysis.

---

## 📌 Key KPIs

The dashboard highlights several important supply chain performance indicators:

| KPI | Value |
|---|---:|
| **Total Stock** | 7.64K |
| **On-Time Delivery Rate** | 54.55% |
| **Average Delay** | 1.64 Days |
| **Total Shipments** | 220 |
| **Total Delay Days** | 360 |

---

## 📈 Dashboard Components

### 1. Total Stock by Category

The dashboard compares inventory levels across product categories:

- Stationery
- Electronics
- Groceries
- Apparel
- Furniture
- Hardware

This visualization helps identify categories with relatively high and low inventory levels.

---

### 2. Shipment Count by Status

Shipment performance is categorized into four shipment statuses:

- 🟢 On Time
- 🟠 Delayed
- ⚫ In Transit
- ⚪ Cancelled

The dashboard provides both the shipment count and percentage distribution for each status.

---

### 3. Stock Status

The inventory table compares:

- Current Stock
- Reorder Point
- Stock Status
- Product

Categories/products can be monitored to identify items that require replenishment.

---

### 4. On-Time Delivery Performance

The dashboard provides category-level shipment performance, including:

- On-Time Delivery Rate
- Total Delay Days

This allows shipment reliability and delay patterns to be analyzed across different categories.

---

### 5. Stock vs. Reorder Point

A comparative visualization displays:

**Total Stock vs. Total Reorder Point**

for each category.

This helps identify categories where available inventory needs to be monitored against replenishment thresholds.

---

### 6. Delay Trend Analysis

The dashboard includes a time-based visualization of **Sum of Delay Days by Day**.

This helps identify:

- High-delay periods
- Changes in delivery performance
- Potential shipment disruption patterns
- Days requiring further investigation

---

## 🔍 Key Insights

Based on the dashboard:

- The overall inventory level is approximately **7.64K units**.
- The overall **on-time delivery rate is 54.55%**.
- The average shipment delay is approximately **1.64 days**.
- A total of **220 shipments** are represented in the dashboard.
- The dashboard records **360 total delay days**.
- **Stationery** has the highest total stock among the displayed categories.
- **Electronics** also represents a significant portion of the overall inventory.
- Several categories are identified as **understocked**, indicating potential replenishment requirements.
- Comparing current stock with reorder points provides a way to prioritize inventory monitoring.

> **Note:** These observations are based on the dataset represented in the dashboard and are intended for analytical and demonstration purposes.

---

## 🛠️ Tools & Technologies

This project focuses on data analysis, supply chain analytics, and interactive dashboard visualization.

**Tools / Concepts:**

- 📊 Data Visualization
- 📦 Inventory Analysis
- 🚚 Shipment Performance Analysis
- 📈 KPI Analysis
- 🔄 Stock Replenishment Analysis
- ⏱️ Delivery Delay Analysis
- 📋 Supply Chain Analytics
- 📊 Interactive Dashboard Design

---

## 💡 Business Questions Addressed

This project can help supply chain teams answer questions such as:

1. Which categories have the highest inventory levels?
2. Which categories may require replenishment?
3. How does current stock compare with reorder points?
4. What percentage of shipments are delivered on time?
5. Which shipment statuses contribute most to overall shipment volume?
6. How many total days are lost due to shipment delays?
7. Are there specific periods with unusually high delivery delays?
8. Which product categories should be monitored more closely from an inventory perspective?

---

## 📊 Dashboard Features

### Inventory Analysis
- Total inventory overview
- Category-wise stock analysis
- Stock vs. reorder point comparison
- Understock identification

### Shipment Analysis
- Shipment status distribution
- On-time delivery performance
- Delayed shipment analysis
- Category-wise delivery performance

### Delay Analysis
- Average delay calculation
- Total delay days
- Daily delay trend
- Identification of high-delay periods

---

## 📁 Project Structure

```text
Inventory-Shipment-Performance-Analysis/
│
├── README.md
│
└── image/
    └── Supply Chain.png
