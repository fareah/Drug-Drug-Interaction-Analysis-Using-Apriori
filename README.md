# Drug-Drug-Interaction-Analysis-Using-Apriori
# Drug-Drug Interaction Signal Detection Using Association Rule Mining

## Overview

Drug–Drug Interactions (DDIs) are a major cause of adverse drug reactions and can lead to severe clinical outcomes. This project focuses on detecting potential DDI signals from adverse event data using Association Rule Mining techniques.

The study was conducted in two phases:

1. Detection of DDI signals associated with Stevens–Johnson Syndrome (SJS) using the Apriori algorithm.
2. Extension of the analysis using FP-Growth, Combination Risk Ratio (CRR) validation, and evaluation on additional adverse events such as Diarrhea.

---

## Objectives

* Identify potential Drug–Drug Interaction signals.
* Detect drug combinations associated with Stevens–Johnson Syndrome (SJS).
* Extend analysis to additional adverse events such as Diarrhea.
* Compare association rule mining approaches.
* Validate identified interaction signals using CRR-based evaluation.

---

## Dataset

The project uses pharmacovigilance adverse event data consisting of:

* Drug Information Table
* Patient Demographic Information
* Medical History Information
* Adverse Event/Reactions Information

These datasets are merged and transformed into transaction-based records suitable for association rule mining.

---

## Methodology

### Phase 1: Apriori-Based DDI Detection

* Data preprocessing and cleaning
* Case-level transaction creation
* Identification of SJS cases
* Frequent itemset generation using Apriori
* Association rule generation
* Evaluation using:

  * Support
  * Confidence
  * Lift
  * Conviction

### Phase 2: Advanced Signal Validation

* FP-Growth based frequent pattern mining
* Combination Risk Ratio (CRR) calculation
* Detection of high-risk drug combinations
* Precision, Recall, and F1-score evaluation
* Analysis of additional adverse events (Diarrhea)

---

## Workflow

FAERS / Adverse Event Data

↓

Data Cleaning & Integration

↓

Transaction Creation

↓

Apriori / FP-Growth

↓

Association Rule Generation

↓

CRR-Based Validation

↓

DDI Signal Detection

---

## Results

### Stevens–Johnson Syndrome (SJS)

* Successfully identified high-risk drug combinations associated with SJS.
* Generated association rules using Apriori and FP-Growth.
* Evaluated predictive performance using Precision, Recall, and F1-score.

### Diarrhea Analysis

* Extended the framework to identify DDI signals associated with Diarrhea.
* Validated discovered interaction patterns using CRR-based methods.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Mlxtend
* Matplotlib
* NetworkX
* Jupyter Notebook

---

## Repository Structure

Drug-Drug-Interaction-Analysis-Using-Apriori/

├── notebooks/

│   ├── 01_SJS_DDI_Detection_Using_Apriori.ipynb

│   └── 02_Advanced_DDI_Analysis_FP_Growth_CRR.ipynb

├── data/

├── results/

├── README.md

└── requirements.txt

---

## Future Work

* Statistical significance testing of DDI signals
* Integration of machine learning-based prediction models
* Analysis of additional adverse events
* Validation using external pharmacovigilance databases

---

## Author

Fareah Rahman

B.Tech Computer Science and Engineering

Research Interests: Artificial Intelligence, Data Science, Pharmacovigilance, Drug Safety Analytics

