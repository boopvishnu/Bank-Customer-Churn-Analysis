# Bank Customer Churn Analysis - Step 2: Python (EDA)

This folder contains the programmatic analysis phase of the dataset, focusing on data cleaning, handling custom segments, and plotting accurate visual insights using Python libraries.

## 🛠️ Tech Stack & Libraries
- **Pandas:** For data ingestion, cleaning, and structural analysis.
- **NumPy:** For logical partitioning and arrays.
- **Matplotlib & Seaborn:** For plotting structured distribution and trend lines.

## 📋 Data Operations Performed
- **Zero-Balance Filtering:** Isolated 3,617 customers with an exact 0 balance to analyze inactive account distributions without skewing the core bell curve.
- **Age Binning:** Structured the continuous age data into categorical buckets (`18-30`, `31-45`, `46-60`, `60+`) using `pd.cut()`.
- **Handling Float Precision:** Formatted data labels inside plotting loops to prevent long floating-point decimals and clean up layout visibility.

## 📊 Core Visualization Showcase
Below is the clean trend line generated during the analysis, optimized with custom axis limits (`plt.ylim`), tight bounding boxes (`bbox_inches='tight'`), and high resolution (300 DPI):

![Churn Rate By Tenure](Churn%20Rate%20By%20Tenure.png)

## 💡 Top Data Insights
1. **Complaints:** Customers who filed a complaint showed a massive 99.5% correlation with churn.
2. **Geography:** Germany displayed a highly elevated churn rate (32.4%) relative to other European clusters.
3. **Age Target:** The 51-60 demographic segment holds the highest risk factor with a 56.21% peak churn rate.
