# QVI Chip Category: Strategic Analysis & Presentation 🚀

## Project Overview
This project represents the culmination of a comprehensive retail analytics engagement for the Category Manager of Chips. The work progressed through data exploration, customer segmentation, and experimental trial analysis, concluding with a strategic presentation designed to inform the client's half-year plan.

This repository showcases the full analytical journey: from raw data processing in **R** to advanced visualization in **Power BI** and strategic storytelling via **Google Slides**.

## Repository Structure
```text
.
├── Task1/
│   ├── chip_analysis.R                 # R script for customer segmentation
│   ├── customer_segment_analysis.csv   # Output: Key metrics by segment
│   └── README.md
│
├── Task2/
│   ├── trial_analysis.R                # R script for trial store analysis
│   ├── trial_summary.csv               # Output: Trial vs. Control performance
│   └── README.md
│
└── Task3/
    ├── QVI_data.csv                    # Data source for dashboard
    ├── (Power BI .pbix file)           # Interactive dashboard
    ├── Strategic Recommendations for Chip Category Performance.pdf   # Final client-facing report
    └── README.md
```
*Note: Large raw data files (`QVI_transaction_data.xlsx`, `QVI_data.csv`) are excluded from this repository due to size limits.*

## Analytical Journey & Key Findings

### Phase 1: Customer Segmentation (R)
*   **Objective:** Identify and understand the purchasing behaviors of key customer segments.
*   **Methodology:** Data was cleaned and feature-engineered in R using `data.table` and `dplyr`. Key metrics (sales, customer count, frequency) were aggregated by lifestage and premium status.
*   **Key Finding:** Sales are driven by three main segments: **Older Families (Budget)**, **Young Singles/Couples (Mainstream)**, and **Retirees (Mainstream)**. An opportunity was identified to increase basket size for the Young Singles/Couples segment.

### Phase 2: Trial Store Analysis (R)
*   **Objective:** Evaluate the sales impact of a new in-store layout.
*   **Methodology:** Developed a control store selection algorithm based on pre-trial performance similarity. Compared trial stores (77, 86, 88) against matched controls during the trial period (Feb-Apr 2019).
*   **Key Finding:** The trial was a resounding success.
    *   **Store 77:** +33.62% lift
    *   **Store 86:** +5.69% lift
    *   **Store 88:** +12.29% lift

### Phase 3: Strategic Presentation (Power BI & Google Slides)
*   **Objective:** Translate technical findings into a compelling narrative for stakeholders.
*   **Methodology:** Used **Power BI** to build interactive dashboards, solving complex data type challenges. Structured the final presentation using the **Pyramid Principle** to lead with recommendations.
*   **Outcome:** Provided a clear roadmap for category growth, combining the trial layout success with targeted segment strategies.

## Final Recommendation
Based on the analysis, the client should **proceed with a full rollout of the new store layout** and implement targeted promotional strategies for key customer segments to maximize category revenue.

## Tools & Technologies
*   **R:** Data cleaning, statistical analysis, and control store modeling.
*   **Power BI:** Interactive dashboards and professional visualizations.
*   **DAX:** Custom measures for specific reporting requirements.
*   **Google Slides:** Strategic communication and presentation design.

## Author
**Siyamthanda Amahle Buthelezi**
