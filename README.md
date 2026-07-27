# 🏃 Aerofit Customer Purchase Behavior Analysis
Python • Pandas • NumPy • Matplotlib • Seaborn

This project analyzes customer purchasing behavior for Aerofit's treadmill products using Exploratory Data Analysis (EDA), customer profiling, and statistical analysis. The objective is to identify the characteristics of customers purchasing different treadmill models and provide data-driven business recommendations to improve product positioning and marketing strategies.

---

## 📌 Project Overview

Aerofit is a leading fitness equipment company offering three treadmill models:

- **KP281** – Entry-level model
- **KP481** – Mid-range model
- **KP781** – Premium model

The primary objective of this project is to understand how customer demographics, income, fitness level, usage patterns, and other factors influence the purchase of different treadmill models. The insights derived from this analysis can support targeted marketing campaigns, customer segmentation, and product positioning.

---

## 🎯 Business Problem

Aerofit is a leading fitness equipment company that offers three treadmill models targeting different customer segments. The company wants to understand the characteristics of customers purchasing each model.

The key business questions addressed in this analysis are:

- Who are the typical customers for each treadmill model?
- How do age, income, education, fitness, usage, and miles differ across products?
- Which customer segments are more likely to purchase premium treadmill models?
- What business strategies can Aerofit adopt to improve product positioning and marketing effectiveness?

---

## 📂 Dataset Information

The dataset contains customer purchase records for Aerofit's treadmill products.

| Feature | Description |
|----------|-------------|
| Product | Treadmill model purchased (KP281, KP481, KP781) |
| Age | Customer age (years) |
| Gender | Male or Female |
| Education | Years of education |
| MaritalStatus | Single or Partnered |
| Usage | Average treadmill usage per week |
| Fitness | Self-rated fitness level (1–5) |
| Income | Annual income |
| Miles | Expected miles walked/run per week |

**Dataset Size**

- **Rows:** 180
- **Columns:** 9

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Google Colab**
- **Jupyter Notebook**
- **Git**
- **GitHub**

---

## 🔄 Project Workflow

The analysis was performed using the following workflow:

1. Data Loading
2. Data Cleaning and Preparation
3. Exploratory Data Analysis (EDA)
4. Univariate and Bivariate Analysis
5. Correlation Analysis
6. Customer Profiling
7. Probability Analysis
8. Business Insights
9. Business Recommendations

---

## 📈 Key Visualizations

### 1. Product Purchase Distribution

![Product Purchase Distribution](Images/01_product_distribution.png)

**Key Insights**

- KP281 is the most purchased treadmill model.
- KP481 is the second most popular model.
- KP781 is a premium product catering to a niche customer segment.

---

### 2. Income Distribution Across Products

![Income Distribution](Images/02_product_vs_income.png)

**Key Insights**

- KP781 customers belong to significantly higher income groups.
- Income is one of the strongest factors influencing product selection.

---

### 3. Fitness Distribution Across Products

![Fitness Distribution](Images/03_product_vs_fitness.png)

**Key Insights**

- KP781 customers report the highest fitness levels.
- Entry-level models are purchased by customers with moderate fitness.

---

### 4. Weekly Usage Across Products

![Usage Distribution](Images/04_product_vs_usage.png)

**Key Insights**

- Premium customers use treadmills more frequently.
- Usage increases with product category.

---

### 5. Product Purchase by Gender

![Gender Distribution](Images/05_product_vs_gender.png)

**Key Insights**

- KP781 has a higher proportion of male customers.
- KP281 shows a more balanced gender distribution.

---

### 6. Correlation Heatmap

![Correlation Heatmap](Images/06_correlation_heatmap.png)

**Key Insights**

- Usage, Fitness and Miles are strongly correlated.
- Income also shows positive relationships with several customer attributes.

---

### 7. Pair Plot of Numerical Features

![Pair Plot](Images/07_pairplot.png)

**Key Insights**

- Demonstrates relationships among all numerical variables.
- Useful for identifying trends, clusters and correlations.

---

### 8. Customer Profile Summary

![Customer Profile Summary](Images/08_customer_profile_summary.png)

**Key Insights**

- KP781 customers have the highest income, fitness, usage and miles.
- KP281 attracts entry-level customers.
- KP481 serves as a mid-range product.

---

## 💡 Key Business Insights

- KP281 is the highest-selling treadmill model.
- KP781 customers are typically high-income and highly active individuals.
- Income, fitness level and treadmill usage strongly influence premium product purchases.
- Customer demographics vary significantly across the three treadmill models.
- Aerofit can improve customer targeting by focusing on product-specific customer segments.

---

## 📋 Business Recommendations

- Target premium customers with personalized marketing campaigns for KP781.
- Position KP281 as an affordable entry-level treadmill.
- Promote KP481 as a value-for-money option for intermediate fitness enthusiasts.
- Design marketing campaigns based on customer income and fitness profiles.
- Improve product recommendations using customer segmentation insights.

---

## 📁 Repository Structure

```text
Aerofit-Business-Case/
│
├── Aerofit_Business_Case.ipynb
├── README.md
├── requirements.txt
├── Data/
│   └── aerofit_treadmill.csv
└── Images/
    ├── 01_product_distribution.png
    ├── 02_product_vs_income.png
    ├── 03_product_vs_fitness.png
    ├── 04_product_vs_usage.png
    ├── 05_product_vs_gender.png
    ├── 06_correlation_heatmap.png
    ├── 07_pairplot.png
    └── 08_customer_profile_summary.png
```

---

## ▶️ How to Run the Project

1. Clone this repository.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open `Aerofit_Business_Case.ipynb` using Jupyter Notebook or Google Colab.
4. Run all cells sequentially to reproduce the analysis.

---

## 👩‍💻 Author

**Sowmya Chethi**

Aspiring Data Analyst | Python | SQL | Statistics | Data Visualization

GitHub Portfolio Project – Aerofit Customer Purchase Behavior Analysis