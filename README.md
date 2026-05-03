# Pattern Discovery in Online Retail Transactions

## Course
CS 4412 — Data Mining  
Kennesaw State University

## Overview
This project explores large-scale online retail transaction data to discover meaningful purchasing patterns using data mining techniques. The focus is on exploratory pattern discovery using association rule mining, specifically the Apriori algorithm.

The goal is to identify relationships between products that are frequently purchased together and interpret these patterns in a real-world retail context.

---

## Dataset
**Online Retail II Dataset**  
Source: https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset  

The dataset contains over one million transaction records from a UK-based online retail company between 2009 and 2011. Each record represents a product purchased within a transaction.

### Preprocessing Decisions
- Removed missing and invalid transactions  
- Filtered to United Kingdom transactions  
- Selected top 200 most frequent items  
- Limited to 8000 invoices for computational efficiency  

---

## Methods

### Exploratory Data Analysis (EDA)
- Top purchased items analysis  
- Transaction size distribution  
- Country distribution  

### Association Rule Mining
- Apriori algorithm implementation  
- Frequent itemset generation  
- Rule generation using lift metric  

### Parameters
- Minimum support: 0.02  
- Lift threshold: ≥ 1.0  

---

## Results

The analysis revealed strong associations between complementary products:

- Cabinet-related items frequently purchased together  
- Teacup and saucer combinations  
- Decorative and themed retail products  

These findings demonstrate that customers tend to purchase related items together.

---

## Interpretation

The discovered patterns can be applied to:

- Recommendation systems  
- Product bundling strategies  
- Store layout optimization  

---

## Critical Assessment

### Limitations
- Dataset limited to UK transactions  
- Reduced dataset (top 200 items) may exclude rare patterns  
- Association rules represent correlation, not causation  

### Ethical Considerations
- Data must be anonymized  
- Customer privacy must be protected  
- Insights should be used responsibly  

---

## Tools Used
- Python  
- Pandas  
- mlxtend  
- Matplotlib  
- Google Colab  

---

## Repository Structure
/data → dataset or dataset link  
/notebooks → analysis notebook  
/outputs → generated charts and rules  
/docs → reports (M3 + Final M4 PDF)  
README.md → project overview  
