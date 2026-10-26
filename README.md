# 🌍 Global Airbnb Performance & Market Share Analytics

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/dax/)
[![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-green?style=for-the-badge)](#data-architecture)

An interactive, multi-page Power BI business intelligence dashboard analyzing **280,000+ listings** and customer reviews across 10 global metropolitan markets. 

This project explores listing lifecycle trends, city-level market concentrations, granular rating drivers, and host trust signals to uncover actionable insights for marketplace optimization.

---

## 📊 Dashboard Preview

| Page 1: Performance & Lifecycle Overview | Page 2: Ratings & Market Share Matrix |
| :---: | :---: |
| ![Page 1](screenshots/page1_overview.png) | ![Page 2](screenshots/page2_ratings.png) |

| Page 3: Review Frequency & Trust Signals |
| :---: |
| ![Page 3](screenshots/page3_reviews_trust.png) |

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
* **Schema Design:** Multi-table relationship model with native cross-filtering enabled across Listing ID keys to ensure responsive cross-visual slicing.

---

## 🚀 Key Features Built in Power BI

* **State-Driven UI (Bookmarks & Buttons):** Custom toggle controls switching dynamically between high-level visual charts and detailed multi-metric scorecards.
* **Conditional Heatmaps:** Dynamic color gradients applied to matrix scorecards for rapid identification of low-scoring dimensions.
* **Pareto Dual-Axis Visuals:** Tracking cumulative market percentage alongside categorical volume distribution.
* **Native Cross-Filtering:** Interactive click-to-filter capability across all chart visuals and KPI cards.

---

## 📂 Repository Contents

* `/screenshots`: High-resolution captures of the 3-page interactive report.
* `*.pbix`: Complete Power BI report file with data model, visuals, and DAX measures.
