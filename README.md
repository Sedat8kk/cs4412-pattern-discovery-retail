# Pattern Discovery in Online Retail Transactions

## Project Description
This project explores large-scale online retail transaction data to discover meaningful purchasing patterns using data mining techniques. The focus is on exploratory pattern discovery rather than prediction, including frequent product combinations, natural customer segments, and anomalous transactions.

## Dataset
**Online Retail II Dataset**  
Source: https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset  

The dataset contains over one million transaction records from a UK-based online retail company operating between 2009 and 2011. Each record represents an individual item purchased within a transaction and includes invoice details, product information, quantities, prices, customer identifiers, and country data.
## M3 Progress — Pattern Discovery

### Completed Work

This milestone includes:

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- UK transaction filtering
- Transaction basket construction
- Apriori algorithm implementation
- FP-Growth algorithm implementation
- Association rule mining
- Pattern interpretation and comparison

### Key Findings

- Certain decorative retail items frequently appear together
- Seasonal gift-related product groupings identified
- High-confidence product combinations discovered
- FP-Growth produced more rules faster than Apriori

### Tools Used

- Python
- Pandas
- mlxtend
- Matplotlib
- Google Colab


## Repository Structure

cs4412-pattern-discovery-retail/
│
├── data/
├── notebooks/
├── outputs/
├── docs/
└── README.md

### M3 Deliverables

- M3 Analysis Report (docs folder)
- Implementation Notebook (notebooks folder)
- Output Rules (outputs folder)

---
## Author
Sedat Sekizkardes
CS 4412 — Data Mining  
Kennesaw State University
