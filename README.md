# 📱 Web Scraping Smartphone Data – Price & Specs Analysis

A portfolio project to showcase practical skills in **web scraping**, **data analysis**, **data manipulation**, and **data visualization**. This project involved collecting smartphone specifications and pricing data directly from a Malaysian tech website using Python automation, cleaning and transforming it for analysis, and building visual insights from it. A machine learning model was also proposed to predict smartphone prices.

---

## 🚀 Project Summary

- Scraped smartphone data (model, specs, pricing, etc.) using **Cloudscraper**, bypassing Cloudflare protections.
- Cleaned and transformed inconsistent specification formats (e.g., storage, RAM, battery).
- Resolved data quality issues manually for the remaining 7% of entries.
- Visualized insights across brands, RAM/storage distribution, and pricing trends.
- Prepared data for predictive modeling (e.g., RAM x Storage vs Price).
- Proposed future improvement ideas including smarter HTML tag parsing and ML-based prediction.

---

## 🧠 Skills & Tech Stack

| Category | Tools Used |
|---------|------------|
| Web Scraping | `cloudscraper`, `requests`, `BeautifulSoup` |
| Data Manipulation | `pandas`, `numpy`, `regex` |
| Data Visualization | `matplotlib`, `seaborn` |
| Automation Handling | `cloudscraper` to bypass anti-bot measures |
| Machine Learning (Planned & Completed) | `scikit-learn`, `train_test_split`, `Random Forest and Linear Regression` |

> 📌 Note: For 93% of smartphones, data was scraped and parsed automatically. The remaining entries were resolved via manual overrides due to structural deviations (e.g., multiple `<th>` rows, different formatting, etc.).

---

## 🛠 Challenges & Solutions

| Challenge | Solution |
|----------|----------|
| Cloudflare blocking requests | Used `cloudscraper` instead of `requests` or `selenium` |
| Inconsistent spec formatting | Applied regex to extract numeric values from varied RAM/storage/battery fields |
| Incomplete entries | Created a manual override dictionary for missing values |
| Variants with multiple models | Handled model-variant associations during parsing |
| Structural HTML irregularities | Proposed future improvement: detect and parse `<th>`-based spec tables more effectively |
| No year data | Proposed future improvement: grab year data and extract other specs nicely for more accurate model prediction |

---

## No plans. Will go ahead with better projects

- Build and train a **Linear Regression** model on cleaned data to predict smartphone prices.
  
--
