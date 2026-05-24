## 🏥 Project 1 — Hospital Patient Analytics System
**Field:** Life Science / Healthcare  
**File:** `hospital_analytics.py`

### What It Does
- Manages patients, doctors, diagnoses, medications and prescriptions
- Runs 8 real-world analytics queries hospitals actually use
- Exports a multi-sheet Excel report automatically

### Tables
| Table | Purpose |
|-------|---------|
| doctors | Doctor info, specialization |
| patients | Patient records, admission/discharge |
| diagnoses | Disease, severity per patient |
| medications | Drug catalogue |
| prescriptions | Which patient gets which drug |

### SQL Concepts Demonstrated
- INNER JOIN / LEFT JOIN across 4 tables
- GROUP BY + COUNT + AVG + SUM
- CASE WHEN for conditional columns
- WHERE IS NULL / IS NOT NULL
- Subqueries inside SELECT
- Date arithmetic with julianday()

### How to Run
```bash
python hospital_analytics.py
```
**Output:** `hospital_analytics_report.xlsx` (8 sheets)
