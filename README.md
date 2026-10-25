# 🏥 Government Hospital Capacity Gap Dashboard

An interactive Excel dashboard analysing the gap in government hospital capacity (beds, doctors and ambulances) across Indian states.

## 📌 Problem Statement

Government hospitals in many states struggle to match patient demand with available resources. This project looks at where capacity falls short by comparing admissions and OPD load against the beds, doctors and ambulances available.

## 📂 Dataset

- **Reference source:** National Health Profile (NHP) 2023, Government of India
- **Data used:** A 10,000-row simulated scenario dataset with 11 columns (including `Ambulances_Available`), designed around the state-level structure of NHP 2023
- **Note:** NHP 2023 provides only state-level figures, so a simulated dataset was built to enable deeper analysis. The data is for portfolio and learning purposes and does not represent actual hospital records.

## 🛠️ Tools Used

- Microsoft Excel
- Power Query (data loading and transformation)
- PivotTables and PivotCharts
- Slicers
- Calculated columns

## 🔄 Process

1. Loaded the dataset into Excel through **Power Query** (Close & Load)
2. Created calculated columns:
   - `Admissions_per_Bed`
   - `OPD_per_Doctor`
   - `Year`
3. Built **PivotTables** for state-wise capacity analysis
4. Created **charts** to visualise the gaps
5. Added **slicers** for interactive filtering
6. Combined everything in a **Dashboard** sheet

## 📊 Key Metrics

- Admissions per Bed
- OPD per Doctor
- Ambulance availability by state

## 💡 Key Insights

- [Insight 1: e.g. which states have the highest admissions per bed]
- [Insight 2: e.g. which states have the highest OPD load per doctor]
- [Insight 3: e.g. ambulance availability gap]

## 🖼️ Dashboard Preview

![Dashboard Screenshot](<img width="1387" height="599" alt="image" src="https://github.com/user-attachments/assets/7d5cb386-f709-4625-8fcb-f00b734d2c08" />
)

## 📁 Repository Structure

```
├── README.md
├── data/
│   └── hospital_capacity_data.csv
├── hospital_capacity_dashboard.xlsx
└── screenshots/
    └── dashboard.png
```

## 👤 Author

**Shybin Sinan KV**
Aspiring Data Analyst | Kerala, India
LinkedIn: www.linkedin.com/in/shybin-sinan-bb72ab351
