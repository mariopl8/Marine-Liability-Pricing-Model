# Marine Liability Pricing & Portfolio Diagnostics Model

## Overview
This repository contains a comprehensive actuarial pricing model and exploratory portfolio analysis for **Oceanic Shipping Co.**, developed as part of the **AIG Actuarial Analyst Job Simulation**. The objective is to evaluate historical claims data (2018–2023), isolate catastrophic events, and determine a mathematically sound **Final Commercial Premium** for the upcoming 2024 policy period.

## Repository Structure
* **`OceanicShipping_PricingModel_MarioPerez.xlsx`**: The complete multi-tab workbook containing raw data, exploratory data analysis (EDA), dynamic dashboards, actuarial pure premium calculations, sensitivity testing, and executive reporting.

## Key Modeling Components
1. **Data Cleaning & Attritional Filtering:** Separated high-frequency attritional claims (99 claims) from extreme catastrophic outliers (1 large loss event) using conditional logic and inflation-adjusted capped net incurred figures.
2. **Exploratory Data Analysis (EDA):** Developed dynamic pivot tables, charts, and metrics to track loss frequency, severity drivers, claim types (e.g., Environmental Pollution, Technical Failure), and geographic risk concentrations across global maritime regions.
3. **Pure Premium & Large Loss Loading:**
   * Calculated historical loss cost per unit of gross tonnage.
   * Isolated a major catastrophic event of **$5,253,947.42** and amortized it over an assumed **20-year return period** to derive a stable Large Loss Loading ($\$262,697.37$ annually).
4. **Commercial Pricing:** Applied a **30% expense loading** and a **10% target profit margin** to establish a recommended Final Premium of **$13,019,673.45** for an expected exposure of 40,000,000 gross tonnage.
5. **Sensitivity Analysis:** Stress-tested the underwriting portfolio by modeling a **6% inflationary shock in claim severity**, resulting in a revised Final Premium of **$13,778,314.42**.

## Tools & Technologies Used
* **Microsoft Excel:** Advanced formula architecture (`COUNTIFS`, dynamic multi-condition logic), Pivot Tables, Slicers, UI/UX dashboard design, and structured financial modeling.
* **Actuarial Science & Insurance Underwriting:** Risk assessment, loss frequency/severity modeling, expense/profit loading structures, and facultative reinsurance pricing principles.
