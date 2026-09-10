# 🛒 SQL Retail & HR Analytics Portfolio

A production-grade SQL portfolio project showcasing advanced data analysis, database management, and business intelligence reporting for retail operations and human resources systems.

---

## 💼 Overview

Designed to demonstrate technical proficiency in complex SQL querying, table joins, data aggregations, date-time functions, and conditional data processing. This project addresses key business intelligence needs, including high-value customer segmentation, revenue projections, organisational hierarchy mapping, and cohort ranking.

---

## 🛠️ Technical Stack & Skills Demonstrated

* **Advanced Joins & Relationships:** Multi-table inner/left joins and self-joins for organisational hierarchy analysis.
* **String & Date-Time Functions:** Pattern matching (`LEFT`, `IN`), chronological filtering, `DATEDIFF()`, `DATE_ADD()`, and format transformations.
* **Conditional & Case Logic:** Multi-tier categorisation (`CASE WHEN`) and handling null values (`COALESCE`).
* **Pagination & Ranking:** Leaderboard extractions and range segmentation using `LIMIT` and `OFFSET`.
* **Subqueries & Aggregations:** Comparative analysis using scalar subqueries against aggregate benchmarks.

---

## 📊 Core Business Problems Solved & Technical Implementation

* **High-Value Customer Reward Identification:** Filtered and sorted top-performing orders joined with customer entities.
* **Pattern-Based Marketing Targeting:** Extracted targeted audience subsets using string manipulation functions without redundant `OR` statements.
* **Risk & Operations Monitoring:** Flagged pending high-value liabilities and tracked customer registration milestones using date difference calculations.
* **Financial Forecasting:** Projected gross revenues, calculated 18% GST metrics, and mapped expected collection windows using interval additions.
* ** Organisational Hierarchy Mapping:** Resolved internal self-referential relationships in the employee database to report management structures.
* **Customer Loyalty Segmentation:** Dynamically classified buyers into spending tiers (`Premium`, `Gold`, `Silver`) and engagement statuses using conditional statements.

---

## 📂 Repository Structure

```text
├── database/
│   └── schema_setup.sql      # Schema definitions for Customers, Orders, and Employees
├── scripts/
│   └── sql_solutions.sql     # Complete script containing all 12 analytical solutions
└── README.md                 # Comprehensive project documentation
