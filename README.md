# -data-analyst-internship-task5
# Titanic Dataset - Exploratory Data Analysis

## 📌 Project Overview
This repository contains a Jupyter Notebook performing **Exploratory Data Analysis (EDA)** on the Titanic dataset.  
It includes statistical summaries, visualizations, and key findings that highlight factors affecting passenger survival.

## 📂 Repository Contents
- `task5.ipynb` – Main EDA notebook
- `eda_summary_report.pdf` – PDF report of findings
- `README.md` – Project documentation

## 📊 Dataset
- **Source:** Seaborn's built-in Titanic dataset (`sns.load_dataset('titanic')`)
- Features: Age, gender, class, fare, embarked location, survival, etc.

## 🔍 Key Steps in Analysis
1. Data loading & inspection
2. Handling missing values
3. Univariate, bivariate, multivariate analysis
4. Visualizations (histograms, boxplots, heatmaps, pairplots)
5. Summary of insights

## 📈 Summary of Findings
- ~62% passengers did not survive
- Females had higher survival rate
- Higher-class passengers more likely to survive
- Fare positively correlated with survival and class
- Most passengers aged between 20–40 years

## 🛠 Requirements
Make sure you have Python 3.x installed with:
  pip install pandas numpy matplotlib seaborn



## 🚀 How to Run
1. Clone this repository:
git clone https://github.com/anshuiitb/-data-analyst-internship-task5.git
cd <-data-analyst-internship-task5>

2. Open the notebook in Jupyter/Colab/VS Code:
jupyter notebook task5.ipynb

3. Run all cells to reproduce results.
4. Open `eda_summary_report.pdf` for a formatted report.

## 🙌 Acknowledgements
- [Seaborn Library](https://seaborn.pydata.org/) for providing Titanic dataset.
