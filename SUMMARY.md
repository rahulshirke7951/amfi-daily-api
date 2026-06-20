# 📌 Project Summary

## MF Data Pipeline

A lightweight and automated pipeline to collect, process, and manage mutual fund (MF) data for analysis and downstream usage.

---

## 🔑 Key Highlights

- Automates MF data ingestion
- Cleans and transforms raw financial data
- Stores structured datasets for analysis
- Supports scheduled execution (cron / CI)
- Includes maintenance utilities (e.g., release cleanup)

---

## ⚙️ Core Workflow

1. Fetch data from source APIs or datasets
2. Clean and normalize the data
3. Store processed data in structured format
4. Run on schedule for continuous updates

---

## 📂 Important Directories

- `src/` → Core pipeline logic
- `scripts/` → Utility and automation scripts
- `data/` → Raw and processed datasets
- `config/` → Configuration files

---

## 🧹 Maintenance

Includes scripts to:
- Delete old GitHub releases
- Keep latest N releases
- Perform dry-run checks before deletion

---

## 🎯 Purpose

To provide a scalable and maintainable system for tracking and analyzing mutual fund data efficiently.

---

## 🚀 Future Scope

- Real-time data ingestion
- Monitoring & alerting
- Dashboard integration
- Advanced analytics

---

> This file is intended as a quick reference for understanding the project at a glance.
