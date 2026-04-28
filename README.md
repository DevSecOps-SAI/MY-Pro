# Exploratory Data Analysis (EDA) in Banking Using Python

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.x](https://img.shields.io/badge/python-3.x-blue.svg)](https://www.python.org/)

The purpose of this project is to master **Exploratory Data Analysis (EDA)** in the banking sector using the **Pandas** framework. This project performs "bank scoring" by analyzing client characteristics to predict behavior, specifically the likelihood of a client making a term deposit.

---

##  Project Goals
* **Data Exploration:** Analyze banking datasets using the Pandas framework.
* **Statistical Analysis:** Build complex pivot tables to extract business insights.
* **Data Visualization:** Create meaningful plots to identify trends and marketing opportunities.

##  Technology Stack
* **Pandas:** Data manipulation and analysis.
* **NumPy:** Numerical computing.
* **Matplotlib:** Static, animated, and interactive visualizations.

##  Dataset Overview
The analysis uses a subset of the [UCI Bank Marketing Data Set](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing). 
* **bank-additional.csv:** The core dataset for analysis.
* **bank-additional-names.txt:** Detailed descriptions of all client and marketing features.

---

##  Key Business Questions Answered
The project provides programmatic answers to the following:
1.  **Conversion Rate:** What is the share of clients attracted in our source data?
2.  **Customer Profiles:** What are the mean values of numerical features among attracted clients?
3.  **Communication Depth:** What is the average call duration for successfully attracted clients?
4.  **Demographics:** What is the average age among attracted and unmarried clients?
5.  **Labor Analysis:** What is the average age and call duration across different employment types?

##  Getting Started

### Prerequisites
Ensure you have Python installed, then install the required libraries:
```bash
pip install pandas numpy matplotlib
