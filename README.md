# Ski Shop Analysis README

## Overview

The Ski Project is a comprehensive analysis and data processing tool designed for ski resort operations. It utilizes Python to aggregate, analyze, and visualize data related to ski equipment rentals, customer demographics, and transaction histories. The project aims to provide actionable insights for ski resort management to optimize their operations, improve customer satisfaction, and increase profitability.

## Data Source

The dataset used in this project was obtained from the Maven Analytics Ski Project. This rich dataset provides extensive details on ski equipment rentals, including transaction histories, customer demographics, and other relevant operational data, making it an invaluable resource for our analysis.

## Features

- **Data Aggregation**: Implements custom functions to aggregate data based on various categories such as date, customer ID, and location.
- **Analysis**: Provides detailed analysis of rental transactions, including total revenue per location and customer spending patterns.

## Installation

To set up the Ski Project, follow these steps:

1. Ensure you have Python installed on your system.
2. Clone the repository to your local machine.

## Usage

The project includes several key functions for data processing:

- `sum([len(order) for order in order_dict.values()])`: Calculates the total number of items rented.
- `aggregator(category_index, field_to_sum_index, dictionary)`: A versatile function to aggregate data based on specified indices from the order dictionary.

Example usage:

```python
location_sums = aggregator(5, 2, order_dict)
print(location_sums)
```

This will output the total revenue per location, such as:

```plaintext
{'Sun Valley': 1268.84, 'Stowe': 3582.82, 'Mammoth': 3879.81}
```


## Contact

For any inquiries or contributions, please open an issue in the GitHub repository.

