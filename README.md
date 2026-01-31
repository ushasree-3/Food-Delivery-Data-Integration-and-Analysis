# Food Delivery Data Integration and Analysis

## Overview
The goal is to combine transactional, user, and restaurant master data into a single unified dataset and perform analytical queries to answer business questions.

The final merged dataset serves as the single source of truth for all analyses and questions in this hackathon.

---

## Datasets
The analysis is based on three independent data sources:

- **orders.csv** – Transaction-level order data
- **users.json** – User master data
- **restaurants.sql** – Restaurant master data containing cuisine and rating information

---

## Data Processing
The following steps were performed:

- Loaded CSV and JSON data using Pandas
- Executed SQL scripts to extract restaurant information
- Merged datasets using LEFT JOINs to retain all transaction records
- Created a consolidated dataset for analysis

---

## Analysis
The unified dataset was used to study:

- User membership patterns
- City-wise and cuisine-wise order trends
- Revenue distribution
- Restaurant rating impact on orders

All insights are derived solely from the final merged dataset.

---

## Tools & Technologies
- Python
- Pandas
- SQLite
- Google Colab

---

## Repository Structure
```text
.
├── Food_Delivery_Analysis.ipynb    # Main analysis notebook
├── final_food_delivery_dataset.csv # The unified "Source of Truth"
├── orders.csv                      # Raw transaction data
├── users.json                      # Raw user metadata
├── restaurants.sql                 # SQL schema and restaurant data
└── README.md                       # Project documentation
