# 🌆 Luxury Housing Bangalore 

> A premium analytics solution for visualizing real-estate trends, builder reliability, and market conversion rates in the Bangalore Luxury sector.

---

### 📋 Project Overview
The **Luxury Housing Bangalore (LHB)** analytics project transforms raw transaction data into actionable business intelligence. It focuses on the high-end segment, providing granular visibility into property configurations and pricing strategies.

### ✨ Key Deliverables
- **Data Cleanup Engine**: Python-based pipeline for removing outliers and invalid data points.
- **Interactive Dashboard**: Power BI visual suite for stakeholder reporting.
- **KPI Tracking**: Automated calculation of Revenue, Bookings, and Conversions.

### 🛠️ Technology Stack
| Layer | Technology |
| :--- | :--- |
| **Data Processing** | Python 3.x, Pandas Library |
| **Business Intelligence** | Power BI Desktop |
| **Data Format** | Optimized CSV (Flat File) |

### 📁 Directory Structure
```text
LHB_Analytics/
├── 📊 PowerBI_Tables/
│   └── Luxury.pbix             # Power BI Workspace
├── 🐍 Scripts/
│   └── clean_final.py          # Data Processing Engine
└── 📄 Data/
    ├── Raw_Data.csv            # Original Dataset
    └── Final_Cleaned_Data.csv  # Production-Ready Data
```

### 📈 Business Metrics & KPIs
- **Revenue (Cr)**: Sum of all property transactions in Crores.
- **Booking Conversion**: Ratio of Successful Bookings to total enquiries.
- **Market Benchmarking**: Average Price per Sqft vs. Market standard.
- **Builder Performance**: Top N developers by revenue and unit volume.

### 🚀 Quick Start Guide
1. **Refresh Data**: Run the cleaning script to prepare the latest CSV:
   ```bash
   python clean_final.py
   ```
2. **Open Dashboard**: Launch `Luxury.pbix` in Power BI.
3. **Connect Source**: Map the model to `Final_Cleaned_Luxury_Housing.csv`.
4. **Deploy**: Update visuals to reflect the latest market trends.

---
