## NBA All-Star Retention & Exit Analysis (2016–2026)

**Dataset Used: https://www.kaggle.com/datasets/ismailperacha/nba-all-star-dependency-dataset-20162026 (Own)**

Data-driven analysis of how NBA teams manage All-Star talent following peak playoff success.

This project examines retention windows, championship effects, acquisition type impact, and dominant exit mechanisms to understand how modern front offices handle star players.


## Research Questions

How long do teams retain All-Stars after peak playoff success?

Do championship teams retain stars longer?

Does acquisition method (Draft, Trade, Free Agency) affect retention?

How do All-Star stints most commonly end?

Is the modern NBA trade-dominant?


## Key Findings

**1. Contender Windows Are Short**

* Median retention after peak: **2 years**

* 62% of All-Stars leave within 2 seasons

* Only 14% remain after 5 years


**2. Champion Retention Premium**

* Champions retain stars **3.33 years**

* Non-champions retain stars **2.08 years**

* Suggestive evidence (p ≈ 0.06)


**3. Drafted Stars Stay Slightly Longer**

* Draft: 2.87 years
* Free Agency: 2.00 years
* Trade: 1.94 years
* Not statistically significant (p ≈ 0.12)


**4. Trade Dominates Exit Pathways**

* 70% of stints end via trade
* Only 22% end via free agency

**5. Even Homegrown Stars are Traded**
* 80% of drafted All-Stars exit via trade


Modern NBA roster management is overwhelmingly transactional and asset-focused.


## Visualizations

Retention Distribution

Survival Curve

Championship Comparison

Exit Mechanisms

Exit by Acquisition Type


## Methodology

* Dataset: All NBA All-Star team stints (2016–2026 window)

* Sample: 74 completed stints

* Statistical Tests:

    * Two-sample t-test (Championship effect)

    * ANOVA (Acquisition type effect)

* Survival-style cumulative retention modeling

## Project Structure

nba-allstar-retention-analysis/
├── notebook/
├── images/
└── README.md


## Dataset
Available on Kaggle:
Link to NBA All-Star Dependency Dataset



