# Bank Customer Churn Analysis (Python - Step 2)

Welcome to the Python phase of my data analytics challenge. After building the dashboard in Excel, I did the exact same analysis in Python using Pandas for data handling, and Matplotlib and Seaborn for plotting.

---

###  Visualization Preview
<img width="1664" height="1343" alt="Image" src="https://github.com/user-attachments/assets/138f3e94-657e-4dd7-a53e-048e533ae594" />

---

###  Code Structure
To keep the analysis clean, the Jupyter Notebook is structured into:
* **Dependencies:** Loading Pandas, NumPy, Matplotlib, and Seaborn.
* **Data Profiling:** Reading the customer dataset and verifying column types.
* **Data Processing:** Grouping continuous customer data into custom categories.
* **Chart Programming:** Writing code to create, label, and save formatted plots.

---

###  Data Process & Fixes
* **Float Precision:** Fixed long 12-13 digit floating decimals by formatting the data labels inside the plotting loops.
* **Zero Balance Isolation:** Separated 3,617 customers with a 0 balance to plot a clean normal distribution curve for active accounts.
* **High-Res Export:** Saved charts using `dpi=300` and `bbox_inches='tight'` so text labels remain clear and do not get cut off.

---

###  Key Insights Discovered
* **Complaints:** Customers who filed a complaint showed a massive 99.5% correlation with leaving the bank.
* **Geography:** Germany showed a much higher churn rate (32.4%) compared to France and Spain.
* **Age Demographics:** Churn peaks heavily among customers aged 51 to 60, reaching a 56.21% churn rate.

---

###  Files in this Folder
* `Bank_Customer_Churn_Analysis.ipynb` - Complete Jupyter Notebook with code.
* `Churn Rate By Tenure.png` - Finalized high-res line chart exported from the script.

---

###  What's Next?
Phase 2 (Python) is complete. I am now moving on to Phase 3, where I will upload the same dataset into a BI tool to build an interactive dashboard next week!
---
