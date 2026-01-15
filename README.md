# Data Visualization Project: The Pressure Game
### Beyond Expected Goals: the hidden side of Serie A

---

## 📌 Description

This project was developed as part of the **Data Visualization course** within the **MSc in Data Science program** at **University of Milano-Bicocca**. It presents a comprehensive statistical and tactical analysis of the **Italian Serie A (2024/25 season)**, utilizing advanced football metrics from **Understat**.

The analysis moves beyond traditional league tables to explore the **structural drivers** of team performance, quantifying the relationship between **Expected Metrics** (xG, xPTS), **Tactical Identity** (pressing intensity, territorial control), and **Actual Results** (goals, points).

The project challenges conventional narratives by proving that **volume alone is vanity**: creating chances without converting them leads to underperformance. Through machine learning (PCA, K-Means clustering) and custom visualizations, the analysis identifies **four tactical archetypes** and presents a detailed case study of **AC Milan's structural transformation** from a high-risk approach (24/25) to a safety-first, efficient model (25/26).

---

## 🎯 Project Objectives

1.  **Map Tactical Identity:** Classify Serie A teams into distinct playing styles based on offensive output and defensive approach using **PCA** and **Clustering**.
2.  **Quantify Efficiency:** Measure the disparity between Expected Performance (xG, xPTS) and Actual Results to identify overperformers.
3.  **Identify Structural Patterns:** Reveal hidden correlations between pressing intensity (PPDA), territorial dominance, and goal creation.
4.  **Case Study Analysis:** Visualize AC Milan's tactical pivot across two seasons, highlighting the trade-offs between volume and solidity.

---

## 🔬 Methodologies Used

The following analytical and visualization techniques were employed:

-   **Data Processing:** Extraction of metrics from Understat and normalization to "Per 90 Minutes" values for fair comparison.
-   **Dimensionality Reduction (PCA):** Reducing 4 tactical variables (xG, DC, xGA, PPDA) into 2 interpretable dimensions (Offensive Output vs Defensive Approach).
-   **Unsupervised Clustering (K-Means):** Segmentation of teams into 4 tactical clusters (e.g., *Elite Volume Generators*, *Pragmatic Controllers*, *Passive Defenders*).
-   **Comparative Visual Analytics:** Use of scatter plots, heatmaps, and territorial control maps to visualize multi-dimensional performance.
-   **Temporal Analysis:** Season-over-season comparison using radar charts and percentage change bar plots.

---

## 🛠️ Technologies Used

-   **Programming Language:** Python 3.11+
-   **Data Manipulation:** Pandas, NumPy.
-   **Machine Learning:** Scikit-learn (StandardScaler, PCA, K-Means).
-   **Visualization:** Matplotlib, Seaborn (Static, publication-quality charts with custom journalistic styling).
-   **Logo Integration:** Custom `LogoManager` class for dynamic team logo placement.
-   **Data Source:** [Understat.com](https://understat.com/) (Advanced football statistics).
