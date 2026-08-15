# 📊 Project 01 — Excel Data Cleaning & CRM Data Quality

## 📌 Project Overview

This project simulates a real-world freelance Excel data cleaning task for a customer CRM dataset.

The objective was to transform a messy customer dataset into a cleaner, standardized, and review-ready dataset before CRM import.

The project focuses on:

- Data cleaning and standardization
- Duplicate detection
- Data quality checks
- Issue logging
- Change tracking
- Client-ready documentation

> **Note:** This is a training simulation inspired by real freelance Excel data-cleaning requirements. It is not paid client work.

---

## 🎯 Business Scenario

A client provided a messy customer list that needed to be cleaned and prepared before importing the data into a CRM system.

The dataset contained inconsistent customer names, email formats, phone numbers, city names, status values, date formats, and duplicate records.

The goal was to improve data quality while preserving valid customer records.

---

## 🛠️ Tools Used

- Microsoft Excel
- Excel Formulas
- Data Cleaning & Standardization
- Duplicate Detection
- Data Validation
- Documentation & Issue Logging

---

## 🔍 Data Cleaning Process

### 1. Customer Name Standardization

Customer names were standardized by:

- Removing unnecessary spaces
- Applying consistent capitalization
- Creating a clean customer-name field

### 2. Email Standardization

Email values were cleaned and standardized into a consistent format.

Invalid-looking email values were identified for quality review.

### 3. Phone Number Standardization

Phone numbers were standardized into a consistent format to improve CRM compatibility.

### 4. City Standardization

City names were standardized to maintain consistent location values.

### 5. Status Standardization

Customer status values were standardized into consistent categories such as:

- Active
- Inactive
- Pending

### 6. Date Standardization

Signup dates were standardized into:

`DD/MM/YYYY`

### 7. Duplicate Detection

Duplicate customer records were identified using key customer information.

Duplicate records were flagged for review instead of being automatically deleted.

### 8. Issue Logging

Identified data-quality issues were documented in a dedicated `ISSUE_LOG` sheet.

### 9. Change Tracking

Major cleaning actions were documented in the `Change_Log` sheet.

---

## 📈 Cleaning Results

| Metric | Result |
|---|---:|
| Total Records | 51 |
| Unique Records | 49 |
| Duplicate Records | 2 |
| Issues Logged | 2 |

### Recommended Action

Review and remove duplicate records after manual verification.

---

## 📁 Workbook Structure

The final Excel workbook contains:

| Sheet | Purpose |
|---|---|
| `Raw_Data` | Original customer dataset |
| `CLEANED_DATA` | Standardized and cleaned dataset |
| `ISSUE_LOG` | Identified data-quality issues |
| `Change_Log` | Major cleaning actions and corrections |
| `Client_Brief` | Project requirements and cleaning summary |

---

## 📸 Project Screenshots

### Client Brief — Requirements

![Client Brief Part 1](screenshots/Screenshot%202026-08-15%20213004.png)

### Client Brief — Cleaning Results

![Client Brief Part 2](screenshots/Screenshot%202026-08-15%20212627.png)

### Cleaned Data — Part 1

![Cleaned Data Part 1](screenshots/Screenshot%202026-08-15%20204815.png)

### Cleaned Data — Part 2

![Cleaned Data Part 2](screenshots/Screenshot%202026-08-15%20204837.png)

### Cleaned Data — Part 3

![Cleaned Data Part 3](screenshots/Screenshot%202026-08-15%20204855.png)

### Issue Log

![Issue Log](screenshots/Screenshot%202026-08-15%20211340.png)

### Change Log

![Change Log](screenshots/Screenshot%202026-08-15%20211907.png)

---

## 💼 Skills Demonstrated

This project demonstrates practical skills in:

- Excel data cleaning
- Data standardization
- Duplicate detection
- Data quality assurance
- Data validation
- Issue documentation
- Change tracking
- CRM data preparation
- Client requirement interpretation
- Professional documentation

---

## 📦 Deliverable

The final deliverable is an Excel workbook containing the cleaned dataset, quality checks, issue log, change log, and client brief.

**Final workbook:**

`Project_01_Excel_Data_Cleaning_FINAL.xlsx`

---

## 👤 Portfolio

Created as part of a practical data analytics and automation portfolio.

This project represents the first step in a broader learning roadmap covering:

**Excel Data Cleaning → Kaggle → Data Analyst → n8n → AI Automation**

---

## 📌 Project Status

**Completed ✅**
