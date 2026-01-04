# Clinic Inventory Statistical Audit – DT Business Analyst Assignment

## Introduction
This project is part of the DT Business Analyst Assignment, designed to simulate real-world work done inside small and busy clinics.
The focus of this task is to analyze clinic medicine inventory data and design a simple, practical, and statistical audit system that helps detect errors without increasing the doctor’s workload.

Clinics often manage inventory manually without barcodes, which leads to frequent entry mistakes.
This project focuses on error-pattern detection, not perfect reconciliation.

---

## Task 1: Clinic Inventory Statistical Audit

### Objective
To design a daily statistical micro-audit system that identifies inventory mismatches and sales-entry errors using Excel.

### Files Included
- clinic_inventory_sample.xlsx  
  Contains sample clinic inventory data including opening balance, purchases, sales, and current stock.

- inventory_audit_template.xlsx  
  An Excel-based audit template that automatically checks stock consistency and flags errors.

---

### How the Audit Works
1. Expected Stock Calculation  
   Expected Stock = Opening Balance + Purchases − Sales

2. Mismatch Detection
   - If current stock does not match expected stock, it is flagged as Mismatch
   - This helps quickly identify possible manual entry errors

3. Randomized Daily Checks
   - A random check column selects a small percentage of medicines daily
   - This improves staff discipline and reduces repeated mistakes

4. Focus on High-Risk Areas
   - Medicines with frequent mismatches can be identified easily
   - Staff attention is directed where errors are most likely

---

### Why This Approach is Practical
- Designed for small clinics with manual systems
- Does not require extra software or barcode scanners
- Easy to use by clinic staff
- Saves doctor time by highlighting only problematic entries

---

### Business Impact
- Reduces inventory errors
- Prevents revenue leakage
- Improves SOP compliance
- Builds accountability among staff

---

## Tools Used
- Microsoft Excel
- Excel formulas (IF, arithmetic calculations)
- Randomized checks for audit sampling

---

## Conclusion
This project demonstrates how simple statistical thinking and Excel-based systems can solve real operational problems in clinics without increasing complexity or workload.
