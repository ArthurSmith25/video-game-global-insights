# 🎮 Ice Online Store: Global Video Game Sales & User Score Analysis

**Market Intelligence & Platform Performance Evaluation**

**Stack:** Python (`Pandas`, `NumPy`, `SciPy`, `Plotly`, `Seaborn`) — data sourced via historical video game sales and user/critic ratings.

---

## 📋 Table of Contents

* **Project Overview & Executive Summary**
* **Phase 01: Data Sanitization & Ingestion Integrity**
* **Phase 02: Historical Lifecycles, Modern Dynamics & Regional Profiling**
* **Phase 03: Profitability Diagnostics & Critic Impact**
* **Phase 04: Regional Behavioral Divergence**
* **Phase 05: Hypothesis Testing & Inferential Analysis**
* **Executive Summary & Strategy Wrap-Up**

---

## 🎯 Project Overview

Ice Online Store, a global video game retailer, is auditing historical sales data and user/critic ratings to optimize its upcoming holiday inventory and marketing campaigns. Before allocating ad spend across platforms and genres, this analysis answers three critical business questions: **which platforms and genres drive the highest revenue**, **do user and critic reviews differ significantly across major platforms**, and **do regional preferences (NA vs. EU vs. JP) show statistically distinct purchasing behaviors** — validated rigorously through statistical hypothesis testing rather than guesswork.

---

## 🎯 Strategic Objectives

1. **Data Sanitization & Preparation** — clean column schemas, handle missing values in critical scoring fields, and normalize release years for reliable trend analysis.
2. **Sales & Platform Dynamics** — quantify historical sales trends across platforms and identify key lifecycle patterns for video game hardware and software.
3. **Regional Behavioral Profiling** — segment top platforms, genres, and ESRB ratings across North America, Europe, and Japan to capture regional market nuances.
4. **Rigorous Hypothesis Testing** — evaluate statistical differences in user ratings between platforms and genres using appropriate tests (e.g., Mann-Whitney U or t-tests).

---

## 🛠️ Technical Stack

* **Data Processing & Inference** — `Pandas`, `NumPy`, and `SciPy` (`stats.mannwhitneyu`, `stats.ttest_ind`) for statistical validation.
* **Visualization** — `Plotly Express` for interactive charts and `Seaborn`/`Matplotlib` for significance heatmaps.

---

## ⚙️ Phase 1: Data Sanitization & Schema Normalization

This foundational stage ingests and structurally audits the raw game dataset. The goal is to enforce rigorous data hygiene, normalize column headers, handle missing values in scores and ratings, and prepare a reliable analysis window.

**Execution Protocol:**
* **Schema Sanitization** — lowercase column names, parse data types correctly, and address missing values in critical sales and rating attributes.
* **Type Conversion** — convert sales figures to float and years to datetime/integer format.
* **Defensive Filtering** — isolate relevant modern gaming eras to forecast upcoming promotional strategies accurately.

🎯 **Technical Goal:** Ingest raw CSV data, standardize feature schemas, handle missing values, and apply defensive filtering while tracking precise record attrition.

🧳 **Business Goal:** Incomplete sales records or legacy console data from decades ago can distort modern inventory forecasts. Sanitizing the dataset upfront ensures that every downstream business insight rests on a pristine, reliable sample.

---

## 📈 Phase 2: Exploratory Data Analysis & Sales Dynamics

This section evaluates core gaming market trends. The goal is to reconstruct platform lifecycles, quantify sales across genres, and pinpoint top revenue drivers that impact overall business performance.

**Execution Protocol:**
* **Platform Lifecycle & Obsolescence Analysis** — aggregate total sales by platform and release year from historical data to establish the statistical justification for the modern analytical window.
* **Current Market Share & Dynamics** — evaluate active platforms to determine leadership, hardware longevity, and volume distribution without information loss.
* **Genre Profiling & User Engagement** — rank genres by global sales and average user ratings to determine customer preferences and profitability.

---

## 🌍 Phase 3: Regional User Profiling (NA, EU, JP)

This stage breaks down consumer behavior across North America, Europe, and Japan to uncover distinct geographic patterns in purchasing preferences.

**Execution Protocol:**
* **Platform Market Shares by Region** — identify the dominant console or PC ecosystems in each major geographic market.
* **Genre Preferences** — analyze how genre popularity shifts drastically between Western markets and Japan (e.g., Action/Shooter dominance vs. RPG preferences).
* **ESRB Ratings Impact** — evaluate how content ratings influence sales figures in different regulatory and cultural environments.

---

## 🧪 Phase 4: Hypothesis Testing & Inferential Analysis

This analytical block moves past descriptive metrics to test specific statistical assertions about user behavior and platform ratings.

**Execution Protocol:**
* **Hypothesis Formulation** — define null and alternative hypotheses regarding user ratings across platforms (e.g., Xbox One vs. PC) and genres (e.g., Action vs. Sports).
* **Statistical Validation** — apply normality checks, variance evaluations, and non-parametric tests (`SciPy`) to assess significance levels ($\alpha = 0.05$).
* **Business Interpretation** — translate statistical p-values into actionable commercial guidelines for marketing and product curation.

---

## 🚀 Phase 5: Conclusions & Strategic Recommendations

The final section synthesizes technical findings into a concrete business roadmap for Ice Online Store's upcoming fiscal quarters.

**Execution Protocol:**
* **Inventory Allocation** — prioritize platform stock based on active lifecycle trends rather than historical volume.
* **Targeted Regional Campaigns** — tailor promotional bundles to align with specific regional genre affinities.
* **Review System Integration** — leverage critic and user score dynamics to curate high-converting game recommendations on the platform frontend.