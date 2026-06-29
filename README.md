# Green-Supply-Chain-Data-Analysis

A beginner-friendly **Data Analytics** project built in a single Jupyter notebook.
It analyzes 1,000 supply chain records to find out which product categories
perform best and worst on sustainability, and why.

No machine learning. No complicated code. Just clean, well-commented,
step-by-step analysis — the kind of project that's great for learning the
basics or for a first portfolio piece.

## 📊 What This Project Does

1. **Load** a real dataset with `pandas`
2. **Check** it for missing values and duplicates
3. **Clean** the column names and fix any negative numbers
4. **Calculate** 2 simple KPIs from existing columns
5. **Group** the data by category and compare averages
6. **Visualize** the patterns with 3 charts
7. **Summarize** the findings in plain English

## 🖼️ Preview

**Average Sustainability Score by Product Type**
![Sustainability score by product type](images/chart_1.png)

**Cost vs. Sustainability Score**
![Cost vs sustainability score](images/chart_2.png)

**Average Renewable Energy % by Product Type**
![Renewable energy percent by product type](images/chart_3.png)

## 🛠️ Tech Stack

- **Python 3**
- **pandas** — loading and analyzing the data
- **matplotlib** + **seaborn** — charts

That's it — no database, no extra services, no install headaches.

## 📁 Repository Structure

```
green-supply-chain-beginner/
├── Green_Supply_Chain_Beginner_Project.ipynb   # the main notebook
├── data/
│   └── green_supply_chain_dataset_1000.csv     # source dataset
├── images/                                      # chart previews for this README
├── requirements.txt
└── README.md
```

## 📦 Dataset

1,000 records across 5 product categories: **Electronics, Apparel, Automotive,
Pharmaceutical, Food**. Each record has cost, CO2 emissions, energy use, waste
generated, renewable energy %, transport distance, delivery time, and a
sustainability score (0–100).

## 🔍 Key Findings

- **Food** has the highest average sustainability score; **Apparel** has the lowest.
- Cost alone doesn't predict sustainability — there's no clear pattern between
  how much something costs and how sustainable it is.
- Categories with higher renewable energy usage tend to score better overall.

## 💡 What I Learned

This project follows a pattern used in almost every data analytics project:

**load → check → clean → calculate → visualize → summarize**

Once comfortable with this pattern, it's easy to apply it to any new dataset.

## Conclusion

This project ran a complete BI analytics pipeline — cleaning, KPI engineering, SQL diagnostics, and SciPy statistical testing — on 1,000 supply chain records. The analysis found that renewable energy adoption, not cost or product category, is the strongest driver of sustainability outcomes (r≈0.70), while category differences alone aren't statistically significant. Results were delivered as both an interactive Excel dashboard and an auto-generated Word report, demonstrating end-to-end analytics from raw data to stakeholder-ready output.
