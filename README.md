# Market Basket Analysis

This project performs **association rule mining** using three popular algorithms:

* **Apriori** (`apyori`)
* **ECLAT** (`pyECLAT`)
* **FP-Growth** (`pyfpgrowth`)

We [analyze](https://github.com/anushreebhat2001/AlgoCompare/blob/main/basket_analysis.ipynb) a retail dataset (`basket_analysis.csv`) to discover frequent itemsets and compare the algorithms based on:

* Frequent itemset counts
* Runtime performance
* Item popularity

## 📊 Highlights

* FP-Growth and ECLAT perform faster than Apriori
* Visualizations compare runtime, data size, and itemset frequency
