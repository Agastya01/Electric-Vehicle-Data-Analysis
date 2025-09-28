# ⚡ Electric Vehicle Adoption Dashboard – Tableau Project

### 📚 Project Overview
This project analyzes **electric vehicle registrations** to uncover patterns in EV adoption across counties and cities. Using Tableau, the data is visualized to highlight where Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) are most prevalent, their electric ranges, and other key metrics that support infrastructure planning and policy decisions.

### 📑 Dataset Details
- **File**: `ev_registrations.csv` (your uploaded CSV)
- **Size**: 260K+ records
- **Columns** (key fields):
  - `VIN (1-10)` – Partial vehicle identifier
  - `County` / `City` / `State` / `Postal Code` – Location data
  - `Model Year`, `Make`, `Model` – Vehicle specifications
  - `Electric Vehicle Type` – Battery Electric (BEV) or Plug-in Hybrid (PHEV)
  - `Electric Range` – Rated electric-only range (miles)
  - `Base MSRP` – Vehicle base price
  - `Legislative District` – WA legislative district
  - `Electric Utility` – Provider in the area

### 🛠 Tools & Technologies
- **Tableau Desktop** (workbook: `EV_Adoption_Dashboard.twb`)
- **CSV dataset** for data source

### 🎨 Dashboard Features
- **EV Count by County & City**: Shows concentration of BEVs and PHEVs.
- **Average Electric Range per Vehicle Type**: Compare BEVs vs. PHEVs across regions.
- **Make & Model Analysis**: Most popular EVs in the state.
- **Interactive Filters**: By Model Year, Make, Electric Vehicle Type.

### 📂 Files in This Repository

| File Name | Description |
|-----------|-------------|
| `ev_registrations.csv` | Electric vehicle registration dataset |
| `EV_Adoption_Dashboard.twb` | Tableau workbook with all dashboards and visuals |

### 🚀 How to Use

1. Clone or download this repository:
   ```bash
   git clone https://github.com/your-username/EV-Adoption-Dashboard.git
   ```
2. Open `EV_Adoption_Dashboard.twb` in Tableau Desktop (or Tableau Public).
3. When prompted, link the workbook to the `ev_registrations.csv` file (if the path changed).
4. Explore the dashboard – filter by City, County, Make, and Model Year.

### 📊 Insights Delivered

- Identified **top counties and cities** with highest EV registrations.
- Compared **Battery Electric vs Plug-in Hybrid** adoption trends.
- Highlighted **popular makes & models** (Tesla Model Y, Model 3, etc.).
- Provided actionable insights for **infrastructure & policy planning**.

### 📝 Author
Created by **[Your Name]** – Data Analyst / Tableau Developer
