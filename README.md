# 📦 Supply Chain Analytics Dashboard

## 🚀 Project Overview

This project presents an end-to-end **Supply Chain Analytics System** built using the **Medallion Architecture (Bronze, Silver, Gold layers)**.
It transforms raw data into meaningful business insights through interactive dashboards.

The system helps organizations monitor:

* Inventory levels
* Demand vs Supply balance
* Supplier performance
* Logistics cost and profitability

---

## 🧠 Architecture

This project follows the **Medallion Architecture**:

### 🟤 Bronze Layer (Raw Data)

* Ingests raw data from source (S3 / files)
* Stores data without transformation

### ⚪ Silver Layer (Cleaned Data)

* Data cleaning and preprocessing
* Handling nulls, duplicates
* Standardizing formats

### 🟡 Gold Layer (Business Logic)

* Aggregations and KPI calculations
* Business-ready tables
* Used for dashboards

---

## 📊 Dashboards Overview

### 1️⃣ Inventory Dashboard

**Purpose:** Monitor stock levels and distribution

**Key Metrics:**

* Total Stock
* Total Orders
* Total Order Value

**Insights:**

* Identifies high and low stock products
* Helps prevent stockouts and overstock

---

### 2️⃣ Demand–Supply Analysis

**Purpose:** Analyze imbalance between demand and supply

**Key Features:**

* SKU-level gap analysis
* Classification: Shortage / Excess / Balanced

**Insights:**

* Helps in demand forecasting
* Improves inventory planning

---

### 3️⃣ Supplier Performance Analysis

**Purpose:** Evaluate supplier efficiency

**Key Metrics:**

* Average open quantity
* Average received quantity

**Classification:**

* Excellent
* Good
* Poor

**Insights:**

* Identifies inefficient suppliers
* Improves vendor management

---

### 4️⃣ Logistics Cost & Revenue Analysis

**Purpose:** Analyze logistics operations

**Key Metrics:**

* Revenue by booking type
* Fuel surcharge cost
* Accessorial charges

**Insights:**

* Identifies major cost drivers
* Helps optimize logistics expenses

---

### 5️⃣ Profitability Analysis

**Purpose:** Evaluate profit across operations

**Key Metrics:**

* Revenue
* Cost
* Profit

**Insights:**

* Identifies most profitable booking types
* Supports strategic decision making

---

## 🛠️ Technologies Used

* **Databricks**
* **Apache Spark / PySpark**
* **SQL**
* **Delta Lake**
* **AWS S3 (Data Storage)**
* **Databricks SQL Dashboards**

---

## 🔄 Data Flow

```
Raw Data → Bronze Layer → Silver Layer → Gold Layer → Dashboards
```

---

## 🎯 Key Features

* Real-time analytics dashboards
* Business KPI generation
* Data-driven decision support

---

## 💡 Business Value

This system enables organizations to:

* Improve inventory management
* Optimize supply chain planning
* Evaluate supplier performance
* Reduce logistics costs
* Increase profitability

---

## 🎤 Conclusion

This project demonstrates how raw data can be transformed into actionable insights using modern data engineering practices and visualization techniques.

---

## 👩‍💻 Author

**Sowmya**
Information Technology Student
Supply Chain Analytics Project

---
