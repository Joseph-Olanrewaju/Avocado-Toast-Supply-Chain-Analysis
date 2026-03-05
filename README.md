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
