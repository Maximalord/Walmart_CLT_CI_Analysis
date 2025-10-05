 # Walmart CLT & Confidence Interval Analysis 📊

This repository contains a complete exploratory data analysis (EDA) and statistical analysis of Walmart customer purchasing behavior during Black Friday.  
The analysis uses the Central Limit Theorem (CLT) and Confidence Intervals (CI) to compare spending habits across gender, marital status, and age groups.

---

## 📝 Project Overview

**Business Problem:**  
Walmart wants to understand whether spending habits differ between male and female customers and how factors like marital status and age influence purchases.  
The analysis aims to provide actionable insights for better decision-making during high-demand periods like Black Friday.

**Key Goals:**
- Perform EDA to understand spending patterns.
- Compare purchase amounts between genders.
- Compute confidence intervals using CLT for average spending.
- Explore spending patterns by marital status and age groups.
- Provide actionable recommendations to Walmart.

---

## 📂 Repository Structure

```

Walmart_CLT_CI_Analysis/
│
├── notebooks/                   # Jupyter notebooks
│   └── Walmart_CLT_CI_Analysis.ipynb
│
├── data/                        # Dataset files
│   └── Walmart_data.csv
│
├── plots/                       # Generated plots
│
 ├── README.md                    # Project documentation
 
````

---

## 📊 Methodology

1. **Data Import & Cleaning**
   - Loaded dataset and checked structure.
   - Handled missing values and detected outliers.
   - Converted categorical variables for analysis.

2. **Exploratory Data Analysis**
   - Univariate & bivariate analysis of purchase amounts.
   - Gender-based spending analysis.
   - Analysis based on marital status and age groups.

3. **Statistical Analysis**
   - Applied Central Limit Theorem to compute confidence intervals.
   - Compared spending habits between groups.
   - Observed overlapping/non-overlapping intervals for actionable insights.

4. **Insights & Recommendations**
   - Summarized actionable business recommendations based on findings.

---

## 📈 Requirements

Install the required Python packages:

```bash
pip install -r requirements.txt
````

The `requirements.txt` contains:

* pandas
* numpy
* matplotlib
* seaborn
* jupyter

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/Maximalord/Walmart_CLT_CI_Analysis.git
cd Walmart_CLT_CI_Analysis
```

2. Open and run the notebook:

```bash
jupyter notebook notebooks/Walmart_CLT_CI_Analysis.ipynb
```

---

## 📌 Insights

* Women spend slightly more than men on average during Black Friday.
* Confidence intervals show overlap but reveal subtle differences in spending habits.
* Married customers spend more than unmarried ones.
* Age significantly affects spending patterns.

---

## 💡 Recommendations for Walmart

* **Targeted Campaigns:** Create personalized offers for high-spending groups like women and married customers.
* **Age-Based Promotions:** Tailor promotions for specific age groups with higher average spending.
* **Dynamic Pricing:** Adjust prices during peak seasons based on customer segment spending behavior.

---

## 🙏 Acknowledgments

Special thanks to **Scaler** and **[@Hina Sharma](https://www.linkedin.com/in/hinasharma19/)** for guidance and mentorship throughout this project.

---

## 📜 License

This project is licensed under the MIT License — see the LICENSE file for details.

```


Do you want me to do that?
```
