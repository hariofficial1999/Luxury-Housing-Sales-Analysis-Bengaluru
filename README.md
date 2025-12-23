# 🌆 Luxury Housing Bangalore 


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

### 💹 Business Metrics & KPIs
- **Revenue (Cr)**: Sum of all property transactions in Crores.
- **Booking Conversion**: Ratio of Successful Bookings to total enquiries.
- **Market Benchmarking**: Average Price per Sqft vs. Market standard.
- **Builder Performance**: Top N developers by revenue and unit volume.

### 💼 Business Use Cases
- **Market Intelligence**: Identify high-performing localities, builder-wise trends, and configuration demand shifts.
- **Sales Optimization**: Use booking and inquiry data to uncover drop-off patterns.
- **Buyer Persona Building**: Use Buyer Type and Comment sentiment to group and understand buyer personas.
- **Competitive Pricing**: Analyze pricing strategies across builders and market segments.
- **Amenity Score & Conversion**: Determine the correlation between amenities and booking rates.
- **Quarterly Trend Tracking**: Track real estate patterns across fiscal quarters to aid investment decisions.

### 🚀 Quick Start Guide
1. **Refresh Data**: Run the cleaning script to prepare the latest CSV:
   ```bash
   python clean_final.py
   ```
2. **Open Dashboard**: Launch `Luxury.pbix` in Power BI.
3. **Connect Source**: Map the model to `Cleaned_Luxury_Housing_Bangalore.csv`.
4. **Deploy**: Update visuals to reflect the latest market trends.

---
