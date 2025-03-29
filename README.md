# 📦 2024 Shipping Data Dashboard – J.M. Huber Case Study

An interactive Power BI dashboard developed as part of a case study for J.M. Huber, analyzing 2024 shipping data across carriers, shipping methods, regions, and pack types.

## 📊 Dashboard Overview

The dashboard consists of **three main pages**:

### 1️⃣ Overview (Executive Summary)
- **KPIs**: Total Shipments, Revenue, Freight, Margin, Avg Costs
- **Trends**: Monthly shipment volume and cost/revenue comparisons
- **Breakdowns**:
  - Freight by Carrier ID
  - Revenue vs. Freight by Shipping Method

### 2️⃣ Map View
- Interactive map of **total shipments by destination**
- Filterable by month for geographic shipment trends

### 3️⃣ Table View
- Tabular summary by **month** including:
  - Total Freight
  - Total Revenue
  - Count of Active Carriers
- Filterable by Pack Type

---

## 🔁 Features

- **Drillthrough Enabled**: Right-click on a carrier to explore carrier-specific metrics
- **Slicers**: Interactive filters for Month, Carrier, Pack Type, etc.
- **Custom DAX Measures**:
  - Margin = Revenue - Freight
  - Average Freight / Shipment
  - Total Shipments, Revenue, and more

---

## 🛠 Tools & Technologies

- **Power BI Desktop (Report Server Edition)**
- DAX for custom KPIs
- Excel (data prep and cleaning)
- Power Query for transformation (e.g., removing null pack types)

---

## 📁 Data Fields Used

| Field             | Description                        |
|------------------|------------------------------------|
| `Actual Shipment Date` | Shipment date (used for Month, Year, Week) |
| `Carrier ID`      | Shipping provider ID              |
| `Pack Type`       | Type of shipment packaging        |
| `Freight Expense` | Cost of shipment                  |
| `Order Revenue`   | Revenue generated from the shipment |
| `Ship To Location`| Destination of shipment           |
| `MODE_OF_TRANSPORT` | Truck, Rail, etc.                |

---

## ✅ Instructions to Use

1. Open the `.pbix` file in Power BI Desktop (Report Server)
2. Interact using slicers or click to drillthrough
3. Use the map and trend visuals to explore volume and efficiency patterns

---

## 📈 Business Insights

- Identified carriers with high freight costs and lower margins
- Certain pack types like **BULK** are more cost-efficient
- Shipping activity drops sharply after June, raising seasonal insights
- Strong geographic concentration in **North America** and **Europe**

---

## 🧑‍💼 Author

**Harshal Kamble**  
Built for the J.M. Huber interview (March 2024)  
For inquiries, connect via [LinkedIn] https://www.linkedin.com/in/harshalka/


---

