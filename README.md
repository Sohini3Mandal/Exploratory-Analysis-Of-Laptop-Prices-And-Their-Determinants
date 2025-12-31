## 📊 Exploratory Analysis of Laptop Prices and Their Determinants

This project presents a **comprehensive exploratory data analysis (EDA)** of a laptop pricing dataset to understand **price distribution, feature behavior, and the key hardware and categorical factors influencing laptop prices**.

The analysis systematically examines **data imbalance, feature standardization, and pricing stratification** across manufacturers, categories, and hardware configurations. Emphasis is placed on identifying which features meaningfully drive price variation and which contribute little explanatory value, providing a strong analytical foundation for future regression or machine learning models.

---

## 📂 Dataset

- **Name:** Laptop Pricing  
- **Source:** https://www.kaggle.com/datasets/huzdaria/laptop-pricing
- **Observations:** 238 (229 after data cleaning)  
- **Features:** Hardware specifications, manufacturer, category, operating system, and price  

---

## 🔍 Analysis Highlights

* Identified **strong market imbalance** across brands, categories, and configurations
* Found **price to be right-skewed**, driven by a small number of premium laptops
* Performance-related features (**RAM, CPU frequency, GPU type**) show the strongest association with price
* Physical attributes (**weight, screen size**) exhibit weak or negligible direct influence on price
* Revealed **standardized hardware tiers** leading to clustered, non-continuous patterns in the data

---

## 🛠️ Python Tools Used

* **NumPy** – numerical computation
* **Pandas** – data cleaning, preprocessing, and manipulation
* **Matplotlib** – core visualizations
* **Seaborn** – statistical plots (countplots, boxplots, heatmaps, pairplots)
* **Scikit-learn** – feature scaling (StandardScaler)
* **ydata-profiling** – automated exploratory data analysis (HTML report)

---

## 📁 Repository Structure

```
📁 Exploratory-Analysis-Of-Laptop-Prices-And-Their-Determinants
│
├── EDA_ProfileReport_on_LaptopPricingData.html
├── Exploratory Analysis Of Laptop Prices And Their Determinants (Notebook).ipynb
├── Exploratory Analysis Of Laptop Prices And Their Determinants (Report).pdf
├── Laptop.csv
└── README.md
```

---

## 🎯 Conclusion

This exploratory analysis shows that laptop pricing is shaped by discrete performance tiers and market positioning rather than continuous variation in individual features. The findings underscore the importance of rigorous EDA, bias awareness, and correct feature interpretation prior to any predictive or inferential statistical analysis.

---
