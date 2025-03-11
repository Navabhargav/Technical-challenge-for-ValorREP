# ValorREP Technical Challenge - International Trade Data Analysis

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/) [![Pandas](https://img.shields.io/badge/Pandas-1.5-green)](https://pandas.pydata.org/) [![Matplotlib](https://img.shields.io/badge/Matplotlib-3.7-blue)](https://matplotlib.org/)

---

## 📌 Project Overview

This project analyzes international trade data provided by ValorREP to extract key insights and trends. The dataset includes information on imports and exports across various countries, commodities (represented by HS codes), and years. The goal was to answer specific questions related to trade patterns and visualize the findings.

💡 **Key Objectives:**

✔ Calculate total import/export values for each country.
✔ Identify the most frequent commodity section for each country.
✔ Analyze import/export changes for the US between 2021 and 2022.
✔ Visualize import and export trends on a country level, particularly focusing on the top 10 countries for 2022.

---

## 📊 Dataset & Methodology

### Dataset:

The dataset consists of structured records with details on:

* `country_name`: Name of the country involved in the trade.
* `year`: Year of the trade record.
* `comm_code`: HS code representing the traded commodity.
* `flow`: Direction of trade (Import or Export).
* `trade_usd`: Value of the trade in USD.
* A separate mapping table was used to connect `comm_code` to `section_name`.

### Data Preprocessing & Analysis:

1.  **Data Loading and Merging:** Loaded trade data and mapping table into pandas DataFrames and merged them based on `comm_code`.
2.  **Data Aggregation:** Aggregated trade values to calculate total imports and exports by country and year.
3.  **Frequent Sections:** Identified the most frequent commodity section for each country using mode calculation.
4.  **US Trade Analysis:** Filtered data for the US and calculated percentage changes in imports and exports between 2021 and 2022.
5.  **Visualization:** Utilized matplotlib and seaborn to create visualizations of import and export trends, focusing on the top 10 countries for 2022 to provide a clearer visual representation.

---
## 📈 Key Insights & Findings

* **Top Importing/Exporting Countries:** China and Mexico are among the top countries with significant import and export volumes. Canada also demonstrates strong trade figures.
* **Most Frequent Sections:** "Chemical Products" is a frequently observed commodity section across many countries.
* **US Trade Changes:** The US experienced a decrease in both imports (-16.39%) and exports (-10.57%) from 2021 to 2022.
* **Visualizations:** The visualizations in the Jupyter Notebook show the distribution of import and export values, highlighting the top 10 countries for 2022 for better clarity.

---

## 🚀 Business Impact

* **Market Understanding:** Provides insights into global trade dynamics and key players.
* **Trend Identification:** Helps identify shifts in trade patterns and potential opportunities.
* **Data-Driven Decisions:** Supports informed decision-making for businesses involved in international trade.

---

## 🖥️ Technologies Used

| Category        | Technologies     |
|-----------------|------------------|
| Languages       | Python           |
| Data Processing | Pandas, NumPy    |
| Data Visualization | Matplotlib, Seaborn |

---

## ⚙️ Installation

1.  Clone the repository: `git clone [repository URL]`
2.  Navigate to the project directory: `cd [repository name]`
3.  Create a virtual environment (recommended): `python -m venv venv`
4.  Activate the virtual environment:
    * On Windows: `venv\Scripts\activate`
    * On macOS/Linux: `source venv/bin/activate`
5.  Install dependencies: `pip install -r requirements.txt`
6.  Open and run the Jupyter Notebook: `jupyter notebook notebooks/trade_analysis.ipynb`

---

## 🤝 Contributors

👤 Nava Bhargav Gedda
📩 [navabhargavg@gmail.com](mailto:navabhargavg@gmail.com)
🔗 [LinkedIn](https://linkedin.com/in/nava-bhargav-gedda-4a4a30151) | 🌐 [GitHub](https://github.com/Navabhargav)

---

## ⭐ Like this Project?

If you found this project useful, give it a star ⭐ on GitHub and share it with others! 🚀
