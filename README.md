```markdown
# M1-INF4 — Python Workshop for Data Analysis
## Session 5 — Data Integration Case Study : Campus Tech[cite: 1]

### 👥 Group Members & Group Number
* **Members:**
  * Sofya Erokhova
  * Maria Teresa Martins Soares
  * Pierre Habart
  * Meriem Benseidi

---

### 📋 Project Overview
This synthesis project is part of the Python data analysis workshop (`Atelier-Python`)
It involves integrating and analyzing three heterogeneous data sources (sales, stores, and products) for a fictional retailer named **Campus Tech**. 

The main objective is to critically assess the manager's claim that *"the store with the highest total sales is our best-performing store and we should copy its approach everywhere"*. The study relies on rigorous data cleaning methods, duplicate removal, relational joins, and graphical visualizations using Pandas and Matplotlib.

---

### 🗂️ Repository Structure
The project is organized with the following directory structure:
```text
Atelier-Python/
├── data/
│   ├── case_products.csv
│   ├── case_sales.csv
│   ├── case_stores.csv
│   ├── homelessness.csv
│   ├── sales_subset.csv
│   ├── support_sites.csv
│   └── support_tickets.csv
│   └── temperatures.csv
├── notebooks/
│   ├── 01-Python-NumPy-S1-refresher.ipynb
│   ├── 02-Pandas-Manipulation-S2.ipynb
│   ├── 03-Data-Cleaning-S3.ipynb
│   ├── 04-EDA-Visualization-S4.ipynb
│   ├── 05-Data-Integration-Case-Study.ipynb
│   └── case_study_outputs/
│       ├── category_summary.csv
│       ├── store_summary.csv
│       ├── reconciliation.csv
│       ├── sales_review.csv
│       ├── integration_review.csv
│       ├── figure1_total_revenue_by_store.png
│       ├── figure2_revenue_distribution.png
│       └── figure3_daily_revenue.png
├── requirements.txt
└── README.md

```

---

### ⚙️ Execution Instructions

To run the project and reproduce the complete analysis:

1. **Prerequisites:** Ensure you have Python installed (recommended: version 3.10 or higher). Install the necessary dependencies if needed:
```bash
pip install -r requirements.txt

```


2. **Clone the Repository and Navigate:**
```bash
git clone <REPOSITORY_URL>
cd Atelier-Python

```


3. **Launch the Case Study Notebook:**
* Open Jupyter Notebook or JupyterLab:
```bash
jupyter notebook

```


* Navigate to the `notebooks/` folder and open **`05-Data-Integration-Case-Study.ipynb`**.


* Run all cells sequentially from top to bottom (*Kernel > Restart & Run All*).



---

### 📊 Results and Deliverables

The cleaned summary tables and the three requested labeled figures are automatically generated and saved in the `notebooks/case_study_outputs/` subdirectory:

* **Exported Tables:** `store_summary.csv`, `category_summary.csv`, `reconciliation.csv`, `sales_review.csv`, `integration_review.csv`.


* **Figures:**
1. `figure1_total_revenue_by_store.png` (Total revenue and order counts by store)


2. `figure2_revenue_distribution.png` (Distribution of order revenue - Boxplot)


3. `figure3_daily_revenue.png` (Daily store revenue trend over time)





---

### ✍️ Individual Contributions

In accordance with the workshop guidelines, all group members have reviewed and validated the overall analysis. Every member is fully capable of explaining the data units, cleaning choices, join controls, and study conclusions.

* **Sofya Erokhova :**
* Section 1 of notebook 5.




* **Maria Teresa Martins Soares :**
* Sections 2 and 6.




* **Pierre Habart :**
* Sections 4 and 7.




* **Meriem Benseidi :**
* Sections 3 and 5





```

```