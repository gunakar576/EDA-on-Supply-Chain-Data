# EDA-on-Supply-Chain-Dataset

# 📦 Supply Chain & Sales Data Analysis

## 🔹 Project Overview

This project analyzes **sales, operations, and shipping data** of a consumer products company to gain actionable insights. The analysis aims to:  

- Optimize **inventory management**  
- Reduce **lead times and defects**  
- Improve **shipping efficiency and costs**  
- Understand **customer purchasing behavior**  

The analysis is performed using **Python (Pandas, Seaborn, Matplotlib)** with **tables, charts, and KPI metrics**.

---

## 📊 Sales Analysis

### 🔹 Objective

- Analyze **units sold and revenue** to assess sales performance  
- Identify **customer segments** driving purchases  
- Evaluate **stock levels and product availability**  

### 🔹 Results

#### Product Sales & Revenue

| Product Type | Units Sold | Revenue Generated (₹) |
| ------------ | ---------- | ------------------- |
| Cosmetics    | 11,757     | 161,521.27          |
| Haircare     | 13,611     | 174,455.39          |
| Skincare     | 20,731     | 241,628.16          |

*Visualization placeholder:* Pie chart for **sales share by product type** 

#### Customer Demographics vs Product Purchases

| Customer Group | Cosmetics | Haircare | Skincare |
| -------------- | --------- | -------- | -------- |
| Female         | 4,012     | 936      | 7,853    |
| Male           | 2,304     | 2,292    | 2,911    |
| Non-binary     | 2,607     | 2,820    | 5,153    |
| Unknown        | 2,834     | 7,563    | 4,814    |

*Visualization placeholder:* Bar chart for **customer group vs product purchases**  

#### Stock Levels & Availability

| Product Type | Stock Levels | Availability |
| ------------ | ------------ | ------------ |
| Cosmetics    | 1,525        | 1,332        |
| Haircare     | 1,644        | 1,471        |
| Skincare     | 1,608        | 2,037        |

*Visualization placeholder:* Bar chart **stock vs availability**  

---

### 🔹 Business Insights

- **Skincare** is the top-performing product → drives most revenue and demand  
- Female customers are the key buyers; unknown segment is significant in haircare → hidden demand opportunities  
- Skincare inventory moves fast, whereas cosmetics & haircare may face slower fulfillment  

### 🔹 Business Recommendations

- Prioritize **Skincare production and stock replenishment** to avoid stockouts  
- Launch **targeted campaigns for the unknown customer group** to capture hidden demand  
- Reallocate inventory for cosmetics & haircare to improve availability  
- Use sales trends to plan **promotions and bundle offers** for slower-moving products  

---

## ⚙️ Operations Analysis

### 🔹 Objective

- Analyze **lead times, order quantities, and production volumes** to improve inventory planning  
- Evaluate **manufacturing costs and quality** to identify savings opportunities  

### 🔹 Results

#### Lead Time, Orders & Production

| Product Type | Avg. Lead Time (days) | Avg. Order Quantity | Avg. Production Volume |
| ------------ | --------------------- | ----------------- | -------------------- |
| Cosmetics    | 13.54                 | 51.65             | 479.27               |
| Haircare     | 18.71                 | 43.53             | 586.97               |
| Skincare     | 18.00                 | 52.48             | 609.15               |

*Visualization placeholder:* Bar chart **lead time vs production volume**  

#### Manufacturing Lead Time vs Costs

- Shorter lead times → higher costs (~₹68–70/unit)  
- Moderate lead times → medium costs (~₹30–50/unit)  
- Longer lead times → lower costs (~₹20–42/unit)  

*Visualization placeholder:* Line chart **lead time vs cost**  

#### Defect Rates & Quality

| Product Type | Inspection Result | Avg. Defect Rate (%) |
| ------------ | ---------------- | ------------------- |
| Cosmetics    | Fail             | 2.19                |
| Haircare     | Pass             | 2.92                |
| Skincare     | Pass             | 1.68                |

*Visualization placeholder:* Bar chart **defect rate by product type & inspection**  

---

### 🔹 Business Insights

- Skincare & Haircare have **long lead times** and high production → risk of delayed order fulfillment  
- Haircare has the **highest defect rates**, indicating production challenges  
- Faster production increases costs → need balance between cost and time  

### 🔹 Business Recommendations

- Optimize **production scheduling** to reduce lead times for high-demand products  
- Introduce **quality standardization** to reduce defects in haircare  
- Implement **lean manufacturing practices** to reduce costs for faster lead times  
- Monitor lead times & production volumes regularly to avoid stockouts  

---

## 🚚 Shipping Analysis

### 🔹 Objective

- Analyze **shipping costs, carriers, and modes** to optimize logistics  
- Monitor **shipping times** for timely deliveries  
- Identify **cost-saving opportunities**

### 🔹 Results

#### Shipping Costs by Carrier

| Shipping Carrier | Shipping Costs (₹) |
| ---------------- | ----------------- |
| Carrier A        | 155.54            |
| Carrier B        | 236.90            |
| Carrier C        | 162.38            |

*Visualization placeholder:* Pie chart **cost distribution by carrier**  

#### Revenue by Carrier

| Shipping Carrier | Revenue Generated (₹) |
| ---------------- | -------------------- |
| Carrier A        | 142,629.99           |
| Carrier B        | 250,094.65           |
| Carrier C        | 184,880.18           |

*Visualization placeholder:* Bar chart **revenue by carrier**  

#### Transportation Modes & Routes Costs

| Mode | Route   | Costs (₹) |
| ---- | ------- | ---------- |
| Air  | Route A | 5,800.89  |
| Rail | Route B | 7,007.41  |
| Road | Route C | 2,932.39  |
| Sea  | Route C | 1,367.13  |

*Visualization placeholder:* Stacked bar chart **mode vs route costs**  

#### Shipping Times by Carrier & Mode

| Carrier   | Air  | Rail | Road | Sea  |
| --------- | ---- | ---- | ---- | ---- |
| Carrier A | 5.60 | 7.43 | 5.18 | 7.00 |
| Carrier B | 4.21 | 6.33 | 4.91 | 6.67 |
| Carrier C | 6.57 | 6.17 | 3.71 | 7.33 |

*Visualization placeholder:* Grouped bar chart **shipping times by carrier & mode**  

---

### 🔹 Business Insights

- Carrier B is **fastest and highest revenue**, despite highest costs → ideal for urgent/high-value shipments  
- Sea mode is cheapest → suitable for bulk, non-urgent deliveries  
- Road & Rail costs vary widely → optimization opportunities for routing  

### 🔹 Business Recommendations

- Use **Carrier B for priority shipments** to ensure customer satisfaction  
- Leverage **Sea mode for bulk shipments** to reduce costs  
- Negotiate contracts or optimize routes for **Road & Rail shipments**  
- Monitor **carrier performance regularly** to maintain efficiency and cost-effectiveness  

---

## 📌 Key KPIs Summary

| KPI | Metric / Value | Insight |
| --- | -------------- | ------- |
| **Top-selling Product** | Skincare (45% units sold) | Highest revenue & demand |
| **Customer Segment** | Female & Unknown | Key revenue contributors |
| **Avg. Lead Time** | Skincare: 18 days, Haircare: 18.7, Cosmetics: 13.5 | Stockout risk for high-demand products |
| **Avg. Order Quantity** | Skincare: 52.48 | Requires production planning |
| **Avg. Defect Rate** | 2.27% (Haircare highest: 2.92%) | Quality improvement needed |
| **Shipping Cost** | Carrier B: ₹236.90 | Most expensive but efficient |
| **Shipping Times** | Carrier B: 4.21–6.67 days | Fastest delivery |
| **Cheapest Shipping Mode** | Sea | Best for bulk shipments |

---

