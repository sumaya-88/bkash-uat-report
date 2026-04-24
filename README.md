# Montgomery-Fleet-Equipment-Analysis

> **Final Project** for [IBM / Coursera] **Excel Basics for Data Analysis** course

---

## 📋 Project Overview

This project simulates the role of a **Junior Data Analyst** working in a local government office. The task involved importing, cleaning, preparing, and analyzing real-world fleet inventory data for Montgomery County using **Excel for the Web**.

The project is split into two parts:

| Part | Focus | Output |
|------|-------|--------|
| **Part 1** | Data Cleaning & Preparation | `Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx` |
| **Part 2** | Data Analysis with Pivot Tables | `Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsx` |

---

## 📂 Repository Structure

```
📁 Montgomery-Fleet-Equipment-Analysis/
│
├── 📄 README.md
├── 📊 Montgomery_Fleet_Equipment_Inventory_FA_PART_1_END.xlsx   ← Cleaned data
└── 📊 Montgomery_Fleet_Equipment_Inventory_FA_PART_2_END.xlsx   ← Analysis + Pivot Tables
```

---

## 🗂️ Dataset

- **Source:** [Montgomery County Open Data — Fleet Equipment Inventory](https://data.montgomerycountymd.gov/Government/Fleet-Equipment-Inventory/93vc-wpdr)
- **License:** Public Domain
- **Description:** A modified subset of the Montgomery County government fleet equipment inventory, containing information about equipment types and their distribution across county departments.

---

## 🧹 Part 1 — Data Cleaning & Preparation

The raw CSV data contained several quality issues that needed to be resolved before analysis could begin.

### Tasks Performed

1. **Converted CSV → XLSX** — Opened the CSV in Excel for the Web and converted it to `.xlsx` format for full editing capability.

2. **Adjusted Column Widths** — Resized all columns so data is clearly visible without truncation.

3. **Removed Empty Rows** — Used the Filter feature to identify and delete all blank rows from the dataset.

4. **Removed Duplicate Records** — Used Conditional Formatting and the Remove Duplicates feature to identify and eliminate duplicate entries.

5. **Fixed Spelling Errors** — Reviewed all text fields and corrected spelling mistakes found in the source data.

6. **Removed Extra Whitespace** — Used Find & Replace to remove all double-spaces throughout the dataset.

7. **Fixed Department Names** — Department names had been split across two columns during import. Used Flash Fill to merge them into a single clean column and removed the redundant column.

### Valid Department Names (Reference)

| | |
|---|---|
| Board of Elections | Economic Development |
| Circuit Court | Environmental Protection |
| Community Engagement Cluster | Finance |
| Community Use of Public Facilities | Fire and Rescue |
| Consumer Protection | General Services |
| Correction and Rehabilitation | Health and Human Services |
| County Executives Office | |

---

## 📊 Part 2 — Data Analysis with Pivot Tables

Using the cleaned dataset from Part 1, three pivot tables were created to uncover insights about equipment distribution across departments.

### Pivot Table 1 — Total Equipment Count by Department (Descending)

| Department | Sum of Equipment Count |
|---|---|
| Transportation | 1,221 |
| Permitting Services | 109 |
| Sheriffs Office | 85 |
| Liquor Control | 56 |
| Housing and Community Affairs | 45 |
| Recreation | 35 |
| Technology Services | 16 |
| Libraries | 6 |
| State Attorneys Office | 5 |
| Human Rights | 2 |
| Public Information Office | 1 |
| Office Of Homeland Security | 1 |
| **Grand Total** | **1,582** |

> 💡 **Insight:** The Transportation department accounts for over 77% of all fleet equipment in Montgomery County.

---

### Pivot Table 2 — Equipment Count by Department & Equipment Class

A cross-tabulation showing how each department's fleet breaks down by vehicle/equipment type — useful for understanding fleet composition per department.

---

### Pivot Table 3 — Equipment Count by Equipment Class & Department

| Equipment Class | Total Count |
|---|---|
| Transit Bus | 379 |
| Heavy Duty | 290 |
| Off Road Vehicle Equipment | 283 |
| Pick Up Trucks | 150 |
| Sedan | 130 |
| Medium Duty | 100 |
| SUV | 90 |
| Van | 65 |
| Public Safety Sedan | 47 |
| Public Safety SUV | 20 |
| CUV | 15 |
| Public Safety Van | 8 |
| Public Safety CUV | 4 |
| Public Safety Pick Up Trucks | 1 |
| **Grand Total** | **1,582** |

> 💡 **Insight:** Transit Buses, Heavy Duty vehicles, and Off-Road Equipment together make up over 60% of the total fleet — reflecting Montgomery County's focus on public transit and infrastructure.

---

## 🛠️ Tools & Skills Used

- **Microsoft Excel for the Web**
- Data Cleaning (filters, deduplication, find & replace, Flash Fill)
- Data Formatting (column widths, text standardization)
- Pivot Tables (single-field aggregation, cross-tabulation, sorting)
- Data Analysis & Insight Extraction

---

## 🎓 Course Information

**Course:** Excel Basics for Data Analysis  
**Provider:** IBM / Coursera  
**Module:** Final Assignment (Parts 1 & 2)  
**Skill Level:** Beginner → Intermediate

---

## 👤 Author

Feel free to connect on [LinkedIn](#) or explore more projects on [GitHub](#).

---

*Dataset used under Public Domain license from Montgomery County Open Data Portal.*
