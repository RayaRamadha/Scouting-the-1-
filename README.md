# ⚽ Scouting the 1%: Identifying Football's Physical Anomalies

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Latest-orange.svg)
![Pandas](https://img.shields.io/badge/Pandas-Latest-green.svg)

## 📌 Project Overview
In modern football, athleticism is a decisive competitive advantage. This project utilizes Data Science methodologies to identify players who possess an extreme combination of **Strength**, **Pace**, and **Jumping** ability—the "1%" outliers who break traditional scouting stereotypes.

By applying **Biomechanical Normalization**, I developed the **Physical Dominance Index (PDI)** to rank players based on their functional explosiveness and recovery potential.

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas (Data Wrangling), Scikit-Learn (MinMaxScaler), Matplotlib/Seaborn (Visualizations).
- **Dataset:** FC 26 Player Database (>18,000 records).

## 🧬 Methodology: The Physical Dominance Index (PDI)
To ensure a fair comparison across the entire population, the following steps were implemented:
1. **Data Cleaning:** Filtering for outfield players, U-24 prospects, and Market Value < €15M (High ROI Scouting).
2. **Normalization:** Using `MinMaxScaler` to transform raw metrics (Sprint Speed, Strength, Jumping) into a unified 0-1 scale.
3. **Index Calculation:** Computing the mean of normalized metrics to identify the top 1% outliers.

## 🚀 Key Insights
- **The Turbo-Tank:** Identified Sinclair Armstrong (Bristol City) as a premier physical poacher with a PDI of 0.8889.
- **The Aerospace Stopper:** Identified Joshua Quarshie (Southampton) as an elite recovery defender with a staggering 96 Sprint Speed at 196cm height.

## 📁 Repository Structure
- `data/`: Contains the raw and processed datasets (if licensing permits).
- `notebooks/`: Jupyter Notebook containing the Exploratory Data Analysis (EDA) and Index calculation.
- `src/`: Core Python scripts for the scouting pipeline.
- `outputs/`: Generated outlier reports and visualizations.

## 🤝 Let's Collaborate
I am **Raya Ramadha Fitroh**, a Data Science student at Telkom University. I am passionate about Sports Analytics and am currently open for **Internship Opportunities** or collaborative projects.

- **LinkedIn:** [Your LinkedIn Profile Link]
- **Email:** [Your Email Address]

---
*Developed as part of my portfolio in Sports Data Science.*
