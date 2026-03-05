# Avocado-Toast-Supply-Chain-Analysis
In this project, I conducted a supply chain analysis of the key ingredients used in avocado toast using data from the Open Food Facts database. The objective was to investigate where the primary ingredients are sourced and identify the most common country of origin for each ingredient.


### Project Overview

Avocado toast has become one of the most popular breakfast meals worldwide, especially in the United Kingdom. While the dish appears simple, its ingredients often travel across multiple countries before reaching the consumer.

In this project, I conducted a supply chain analysis of the key ingredients used in avocado toast using data from the Open Food Facts database. The objective was to investigate where the primary ingredients are sourced and identify the most common country of origin for each ingredient.

This project demonstrates how data manipulation and exploratory analysis can reveal the global supply chains behind everyday food products.

### Business Problem

Food supply chains are increasingly globalized, making it difficult to understand where ingredients originate. Businesses, researchers, and consumers may want to know:

Where food ingredients are most commonly sourced

How global supply chains contribute to everyday meals

Which countries dominate the production of key food products

This analysis focuses on the three essential ingredients of avocado toast:

Avocados

Olive oil

Sourdough bread

The goal is to determine the most common country of origin for each ingredient in products sold in the U.K.


### Dataset

The dataset comes from the Open Food Facts, an open database containing detailed information about food products from around the world.

Relevant Features Used

To streamline the analysis, the dataset was subset to include the following variables:

['code', 'lc', 'product_name_en', 'quantity', 'serving_size', 'packaging_tags', 'brands', 'brands_tags', 'categories_tags', 'labels_tags', 'countries', 'countries_tags', 'origins', 'origins_tags']

These fields provide information about product identity, category, brand, and country of origin.


### Methodology
1. Data Loading

Imported the dataset using Pandas.

Loaded relevant category files for avocado, olive oil, and sourdough products.

2. Data Filtering

Filtered the dataset to isolate products belonging to each ingredient category:

Avocado products

Olive oil products

Sourdough products

3. Data Cleaning

Standardized country names

Removed special characters such as hyphens

Ensured country names contain only letters and spaces

4. Feature Selection

Subset the dataset to retain only columns relevant for supply chain analysis.

5. Origin Analysis

Extracted origin information from the origins column

Calculated the most frequent country of origin for each ingredient.

### Results

The analysis identified the most common source country for each ingredient:

Ingredient	Most Common Country of Origin
Avocados	top_avocado_origin
Olive Oil	top_olive_oil_origin
Sourdough	top_sourdough_origin

These values were stored in the following variables:

top_avocado_origin
top_olive_oil_origin
top_sourdough_origin

### Tools & Technologies

Python

Pandas

NumPy

Jupyter Notebook


### Key Skills Demonstrated

Data cleaning and preprocessing

Dataset subsetting and filtering

Text data standardization

Exploratory data analysis

Frequency analysis

Python data manipulation with Pandas


### Project Structure
avocado-toast-supply-chain-analysis
│
├── data/
│   ├── open_food_facts.csv
│   └── relevant_categories.txt
│
├── notebooks/
│   └── avocado_supply_chain_analysis.ipynb
│
├── src/
│   └── data_processing.py
│
└── README.md
Project Impact

This analysis highlights how even a simple meal like avocado toast relies on a global network of agricultural producers and food suppliers. Understanding these supply chains can help:

Improve transparency in food sourcing

Support sustainable sourcing decisions

Provide insights into global food production trends

