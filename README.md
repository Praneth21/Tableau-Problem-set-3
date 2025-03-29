# 📊 Tableau Dashboards – Visual Analytics Problem Set #3 

This project is based on exercises from *Storytelling with Data: Let's Practice* and includes both visual sketching and Tableau dashboard development. It demonstrates advanced dashboard formatting, calculated fields, and interactive parameter use.

---

## 📂 Files Included

| File | Description |
|------|-------------|
| `Problem_Set_3_Dashboard.twbx` | Tableau workbook with all 4 dashboards |
| `sketches.png` *(optional)* | Hand-drawn visual ideas |
| `dashboard_screenshots/` | Screenshots of final dashboards (optional) |

---

## 🟨 Problem 1 – Sketches to Tableau

📘 **Based on Exercise 2.9 in Storytelling with Data**

- Created at least 6 hand-drawn sketches to visualize time-to-close by product and sales channel
- Recreated 4 of those sketches in Tableau:
  - Dot plot for product performance
  - Deviation-from-average bar
  - Product ranking visual
  - Simplified executive summary chart

🎯 **Purpose:** Develop multiple visual design approaches and compare their effectiveness in communication.

---

## 🟦 Problem 2 – Dashboard Rebuild (Figure 2.8b)

📘 **Goal:** Recreate a side-by-side dual-chart dashboard showing deal time performance

🛠️ **Techniques Used:**
- Calculated field for average (gray box logic)
- Dual chart layout using floating containers
- Product vs Channel cross-tab
- Clean formatting, annotations, and color coding

🎯 **Purpose:** Practice dashboard layering and calculated logic for storytelling

---

## 🟩 Problem 3 – Dealership Performance (Figure 5.2c Rebuild)

📘 **Goal:** Visualize dealership sales by region, quarter, and ranking

🛠️ **Techniques Used:**
- Data preparation for regional analysis
- Calculated field for **Regional Average**
- RANK-based coloring for Q3 2019 (blue/orange)
- Labeling + top-aligned axis for Q3

🎯 **Purpose:** Provide insight into dealership variation and segment standout performers visually

---

## 🟥 Problem 4 – Donation Analysis with Parameters

📘 **Goal:** Use parameter controls and calculated fields to allow users to explore donation data

🛠️ **Techniques Used:**
- Parameter: `Min Gift Level`
- Parameter: `Major Donation Cut-off`
- Calculated Fields:
  - `Large Donor Filter` using `NULL()` logic
  - `Highlight Major Donors` for color emphasis
  - `Dynamic Title` using parameter values
- Log scale axis with reference line

🎯 **Purpose:** Deliver flexible insight into donation behavior and major gift trends

---

## 🧠 Skills Demonstrated

- Tableau Calculated Fields & Table Calculations
- Dashboard Layout Design
- Parameter & Filter Integration
- Interactive Titles and Axis Formatting
- Chart Sketching → Visualization Translation

---

## 🔗 References

- [Storytelling with Data: Let’s Practice – Chapter 2](https://www.storytellingwithdata.com/)
- [Tableau Public Visual Inspiration](https://public.tableau.com/en-us/gallery)

---

## 🚀 How to Use

1. Download the `.twbx` file
2. Open in Tableau Desktop or Tableau Public
3. Explore the four dashboards using filters and tooltips

---

## 📌 License

This project is for academic and portfolio use as part of the Visual Analytics course at DePaul University.

