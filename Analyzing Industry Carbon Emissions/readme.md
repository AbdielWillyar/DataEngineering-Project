## Introduction

In today's world, addressing climate change is a critical global challenge. One significant contributor to greenhouse gas emissions is the manufacturing and transportation of products. According to "The Carbon Catalogue," these emissions account for more than 75% of global emissions.

This project focuses on analyzing product carbon footprints (PCFs), which represent the greenhouse gas emissions associated with a given product, measured in CO2 equivalent. The data used for this analysis is publicly available on nature.com and is stored in a PostgreSQL database.

## Data Overview

The project's data is stored in a PostgreSQL database with a single table named `product_emissions`. The table contains information about PCFs, including the year, product name, company, country, industry group, weight in kilograms, carbon footprint in CO2 equivalent, and percentages of emissions at various production stages (upstream, operations, downstream).

Here is a brief description of the columns in the `product_emissions` table:

- `id`: Unique identifier
- `year`: Year of the data
- `product_name`: Name of the product
- `company`: Company responsible for the product
- `country`: Country of origin
- `industry_group`: Industry group to which the product belongs
- `weight_kg`: Weight of the product in kilograms
- `carbon_footprint_pcf`: Carbon footprint of the product in CO2 equivalent
- `upstream_percent_total_pcf`: Percentage of emissions in the upstream stage
- `operations_percent_total_pcf`: Percentage of emissions in the operations stage
- `downstream_percent_total_pcf`: Percentage of emissions in the downstream stage
