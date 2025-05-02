# 🧪 Digital Marketing Campaign Analysis & Customer Segmentation

This project analyzes the effectiveness of different marketing campaigns and segments customers based on behavioral and demographic data. The dataset is from [Kaggle](https://www.kaggle.com/datasets/zafarali27/digital-marketing-campaign/data).

The goal is to uncover which campaign types are most effective, and ultimately build customer segments that inform targeted marketing strategies.

---

## 📓 Project Structure

### Notebook 1: `A-B_Testing_Awareness_and_Conversion.ipynb`
Compares **Awareness** and **Conversion** campaigns using A/B testing principles.

- 📊 Distribution plots (histogram & KDE)
- 📈 Summary statistics (`.describe()`)
- 🧪 Normality check (Shapiro-Wilk Test)
- 🟰 Homogeneity of variance (Levene’s Test)
- 📉 Hypothesis testing (t-test or Mann-Whitney)

### Notebook 2: `CampaignType_ANOVA_Comparison.ipynb` *(Coming Soon)*
Tests for significant differences in `ConversionRate` across **all four** campaign types using:

- ANOVA / Welch ANOVA
- Kruskal-Wallis (non-parametric alternative)
- Post-hoc tests (Tukey’s HSD)

### Notebook 3: `Customer_Segmentation.ipynb` *(Coming Soon)*
Clusters customers based on features like Age, Income, LoyaltyPoints, and behavior.

- K-Means or hierarchical clustering
- PCA (optional)
- Visualization and interpretation

### Power BI Report *(Coming Soon)*
An interactive dashboard summarizing campaign performance and customer segments.

---

## 🧰 Tools & Libraries

- Python: `pandas`, `numpy`, `scipy`, `seaborn`, `matplotlib`, `statsmodels`
- Jupyter Notebooks
- Power BI

---

## 🧠 What I Learned

- Applied A/B testing with real marketing data
- Performed proper statistical validation (normality, variance checks)
- Transitioned from A/B testing to multi-group comparison
- Built a foundation for actionable marketing insights
- Learned to structure multi-notebook data projects for future scaling

---

## 🚧 Future Work

- 📈 Campaign comparison across all four campaign types
- 📊 Customer segmentation analysis
- 📊 Final Power BI dashboard
