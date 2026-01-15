# Data Visualization Project: The Pressure Game
### Tactical Identity & Efficiency in Serie A Football

---

## 📌 Description

This project was developed as part of the **Data Visualization course** within the **MSc in Data Science program** at **University of Milano-Bicocca**. It focuses on a statistical analysis of the **Serie A (2024/25 season)**, utilizing advanced football metrics from **Understat**.

The analysis moves beyond traditional league tables to quantify **Tactical Identity** and **Efficiency**. By applying data visualization techniques and machine learning, the project identifies distinct playing styles, measures the gap between expected and actual performance, and visualizes the structural trade-offs between offensive volume and defensive solidity.

---

## 📊 Key Analysis Areas

### 1. Tactical Profiling (PCA & Clustering)
Using **Principal Component Analysis (PCA)**, the project reduces complex tactical metrics (xG, xGA, PPDA, Deep Completions) into two primary dimensions. This allows for the unsupervised classification of teams into four distinct archetypes:
*   *Elite Volume Generators*
*   *Pragmatic Controllers*
*   *Passive Defenders*
*   *Strugglers*

### 2. Efficiency & Reality Checks
A deep dive into the disparity between performance and results:
*   **Performance Matrix:** Visualizing the trade-off between offensive production and defensive vulnerability.
*   **Reality vs. Expectation:** Measuring overperformance and underperformance by comparing Actual Points against Expected Points (xPTS).

### 3. Case Study: The AC Milan Pivot
A temporal analysis of AC Milan’s tactical shift from the 24/25 to the 25/26 season. Radar charts and percentage-change analysis visualize how the team sacrificed offensive volume to achieve structural solidity and higher efficiency.

---

## ⚙️ Technical Workflow

The project follows a reproducible data pipeline:

1.  **Data Ingestion:** Parsing raw exports from Understat.
2.  **Preprocessing:** Normalization of metrics to "Per 90 Minutes" values to ensure fair comparison.
3.  **Feature Engineering:** Calculation of custom KPIs such as the *Efficiency Gap* and *Territorial Dominance Index*.
4.  **Visualization:** Generation of high-fidelity, static charts using a custom-built style theme inspired by data journalism (e.g., *The Economist*).

---

## 💻 Tech Stack

*   **Python 3.x**
*   **Data Processing:** Pandas, NumPy
*   **Machine Learning:** Scikit-learn (StandardScaler, PCA, K-Means)
*   **Visualization:** Matplotlib, Seaborn
*   **Data Source:** Understat

