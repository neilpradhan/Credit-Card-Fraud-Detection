# Credit Card Fraud Detection Dataset 

## Overview
This repository contains a dataset of transactions made by European cardholders in September 2013, focusing on the detection of fraudulent activities. It's an essential resource for developing machine learning models to identify and prevent credit card fraud.

## Dataset Description

### Key Characteristics:
- **Total Transactions:** 284,807 (including 492 frauds).
- **Class Imbalance:** Extreme imbalance with frauds constituting only 0.172% of transactions.
- **Features:**
  - V1-V28: Principal components obtained from PCA.
  - Time: Seconds elapsed between each transaction and the first transaction.
  - Amount: Transaction amount.
  - Class: Fraud (1) or non-fraud (0).

### Recommendations for Analysis:
- **Performance Metric:** Area Under the Precision-Recall Curve (AUPRC) recommended due to class imbalance.
- **Accuracy Metric:** Traditional confusion matrix accuracy is not suitable for this unbalanced classification.

## Updates & Resources

### Simulator for Transaction Data (Released on 03/05/2021)
- As part of the "Machine Learning for Credit Card Fraud Detection" handbook, a transaction data simulator is available. Check out the [Simulated Dataset](https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html).

## Acknowledgements
This dataset is the result of a research collaboration between Worldline and the Machine Learning Group ([MLG](http://mlg.ulb.ac.be)) of ULB (Université Libre de Bruxelles). More information on related topics and projects can be found at [ResearchGate - Fraud Detection](https://www.researchgate.net/project/Fraud-detection-5) and the DefeatFraud project page.

## Citations
For academic or research use, please cite the following works:
- Publications by Andrea Dal Pozzolo, Olivier Caelen, Yann-Aël Le Borgne, Gianluca Bontempi, and others, detailing methodologies and insights into credit card fraud detection.



---

This README.md provides a comprehensive overview of the dataset, suitable for a GitHub repository dedicated to credit card fraud detection research.


