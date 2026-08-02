# Bank Customer Churn Analysis Dashboard (Excel - Step 1)

Hi everyone! Welcome to my repository. This is Step 1 of my personal data analytics challenge. 

As a fresher looking to break into the analytics world, I designed this challenge for myself: Take the same raw bank customer dataset, clean it, analyze it, and visualize it using 3 different tools. 

This project is built entirely inside Microsoft Excel, taking around 22 hours over 2 days of continuous iteration, data processing, and dashboard designing. 

Next up in this challenge: Python (Pandas/Matplotlib) and Power BI!

---

### Dashboard Preview

<img width="1874" height="742" alt="Image" src="https://github.com/user-attachments/assets/f6670e29-98d3-4dcc-8c35-f1b64440eaf1" />

---

### Workbook Structure & Organization
To keep the project clean, scalable, and professional, I structured my Excel workbook into 3 distinct sheets:
* Data: The core repository containing the raw, cleaned bank customer dataset.
* Tables: My operational backend workspace where all the complex Pivot Tables, data aggregations, and calculations live.
* Dashboard: The finalized, dark-themed interactive front-end containing all the visualizations, KPI cards, and dynamic slicers. 

---

### Data Workflow & Process
I followed an end-to-end analytics workflow to make sure the insights are accurate and reliable:

1. Data Sourcing & Cleaning: Imported the raw dataset containing 10,000 customer records. Checked for any missing values, duplicates, or formatting issues to ensure the data was completely clean.
2. Data Aggregation: Built robust Pivot Tables to segment the data by demographics, financial tiers, and tenure. For the credit score analysis, I utilized Average Balance instead of Sum to maintain a fair comparison between groups.
3. Dashboard Design & UI/UX: Moved all interactive slicers into a neat left-side sidebar for a sleek software-like feel. Applied a customized Dark Charcoal and Neon Lime Green theme (#A6FF00) to make the data visually striking and easy to read.

---

### Key Business Insights Discovered
Even though the bank's Overall Churn Rate is 20.4% %, digging deeper into the charts revealed some very specific high-risk areas:

* The Gender Gap: Female customers have a significantly higher churn rate (25.1%) compared to male customers (16.5%).
* Geographical Risk: German accounts are showing a much higher drop-off rate compared to customers in France and Spain.
* Activity Matrix: Inactive members are leaving at a staggering 26.9% rate (compared to 14.2% for active members), marking a major revenue loss zone for the bank.
* Tenure vs. Churn: The custom line chart helps pinpoint the exact year on a customer's journey where they are most likely to leave the bank.
* Credit Score Bands: The Avg Balance by Credit Score vertical bar chart clearly indicates which credit tiers hold the highest capital within the organization.

---

### Files in this Repository
* Bank_Customer_Churn_Dashboard.xlsx - The full dynamic Excel sheet with Pivot tables, custom slicer styles, and charts.
* Dashboard.png - A high-res view of the finalized dashboard layout.

---

### What's Next?
Now that Phase 1 (Excel) is complete, I am moving on to Phase 2, where I will perform the exact same analysis using Python (Pandas, Matplotlib, and Seaborn).

I would love to hear your feedback, suggestions, or advice on how I can improve my workflow or design. Thank you for checking out my project!
