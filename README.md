# 🌍 Global Airbnb Performance & Market Share Analytics

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Relational%20Model-green?style=for-the-badge)](#data-architecture)

An interactive, multi-page Power BI business intelligence dashboard analyzing **280,000+ listings** and customer reviews across 10 global metropolitan markets. 

This project explores listing lifecycle trends, city-level market concentrations, granular rating drivers, and host trust signals to uncover actionable insights for marketplace optimization.

---

## 📊 Dashboard Preview

| Page 1: Performance & Lifecycle Overview |
| :---: |
| <img width="1277" height="975" alt="Screenshot 2026-10-26 105910" src="https://github.com/user-attachments/assets/1541a70f-509b-4298-87c8-af07aceb7285" />
 |

| Page 2: Ratings & Market Share Matrix |
| :---: |
| <img width="1277" height="976" alt="Screenshot 2026-10-26 105924" src="https://github.com/user-attachments/assets/00ae206d-995b-4528-be05-dcd01d777599" />
 |

| Page 3: Review Frequency & Trust Signals |
| :---: |
| <img width="1277" height="976" alt="Screenshot 2026-10-26 105941" src="https://github.com/user-attachments/assets/22a35091-5596-4002-b6a5-be336416b5d6" />
 |

---

## 🎯 Key Business Questions Answered

1. **Lifecycle Trends:** How has listing inventory evolved across room categories from market launch through industry disruptions?
2. **Market Concentration:** Which geographic hubs represent the core inventory volume, and what is their cumulative market share?
3. **Rating Performance:** How do secondary review dimensions (Cleanliness, Accuracy, Communication, Value for Money) correlate with overall customer satisfaction?
4. **Host Verification:** Does host profile completeness and identity verification act as a measurable driver of customer trust and review activity?

---

## 🧠 Key Insights & Findings

* **Market Concentration (Pareto Principle):** The top 3 metropolitan markets—**Paris, New York City, and Sydney**—account for **~48%** of the entire global listing volume.
* **Pricing Dynamics:** Entire homes/apartments command the largest inventory share, while hotel rooms maintain premium pricing spikes across European city centers.
* **The Trust Factor:** Over **66%** of active hosts maintain verified identity status. Verified listings demonstrate significantly higher booking confidence and review volume.
* **Category Score Gaps:** Across all 10 cities, **Cleanliness** and **Value for Money** consistently emerge as the primary drivers pulling down overall satisfaction scores.

---

## 🛠️ Data Architecture & Modeling

* **Data Source:** Maven Analytics Airbnb Open Dataset (Listings & Reviews).
* **Scale:** 280,000+ rows normalized into Fact and Dimension tables.
* **Data Model:** Normalized 1-to-Many Relational Model connecting `Listings` (Dimension/Parent) and `Reviews` (Fact/Transactional) tables on `listing_id`.

---

## 🚀 Key Features Built in Power BI

* **State-Driven UI (Bookmarks & Buttons):** Custom toggle controls switching dynamically between high-level visual charts and detailed multi-metric scorecards.
* **Conditional Heatmaps:** Dynamic color gradients applied to matrix scorecards for rapid identification of low-scoring dimensions.
* **Pareto Dual-Axis Visuals:** Tracking cumulative market percentage alongside categorical volume distribution.
* **Native Cross-Filtering:** Interactive click-to-filter capability across all chart visuals and KPI cards.

---

## 📂 Repository Contents

* `/screenshots`: High-resolution captures of the 3-page interactive report.
* `*.pbit`: Complete Power BI report template file with data model, visuals, and DAX measures.
