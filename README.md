# Synthetic Sales Data Analysis Project

This project demonstrates business analytics and data analysis using a synthetic sales dataset. It is designed to be a complete, out‑of‑the‑box example that you can clone, run locally and extend. The repository includes a generated dataset, an exploratory and predictive analysis notebook, and a list of required Python dependencies.

## Project Structure

| File/Folder                | Description                                         |
|---------------------------|-----------------------------------------------------|
| `synthetic_sales_data.csv`| Synthetic dataset of 1,000 customer orders with demographic, product and transaction details |
| `sales_analysis_notebook.ipynb` | Jupyter notebook performing exploratory data analysis (EDA), visualizations, and a predictive model to classify whether an order will be returned |
| `requirements.txt`        | List of Python packages needed to run the notebook |
| `README.md`               | This file, providing project details and usage instructions |

## Dataset Overview

The **synthetic_sales_data.csv** file simulates 1,000 customer orders with the following columns:

- `Order ID`: Unique identifier for each order.
- `Order Date`: Date of the order.
- `Customer Age`: Age of the customer.
- `Gender`: Gender of the customer (`Male` or `Female`).
- `Country`: Country where the order was placed (USA, Canada, UK, Germany, France or Australia).
- `Product Category`: Category of the purchased product (Electronics, Apparel, Home, Sports, Toys or Beauty).
- `Quantity`: Number of items purchased.
- `Unit Price`: Price per item.
- `Total Price`: Calculated as `Quantity` × `Unit Price`.
- `Payment Method`: Payment method used (Credit Card, Debit Card, PayPal, Bank Transfer or Cash).
- `Customer Satisfaction`: A satisfaction score ranging from 1 (lowest) to 5 (highest).
- `Returned`: Target variable indicating whether the order was returned (1) or not (0).

The dataset is entirely synthetic and was generated programmatically for demonstration purposes. There is no personally identifiable information.

## Notebook Summary

The **sales_analysis_notebook.ipynb** notebook takes you through the following steps:

1. **Importing Libraries & Loading Data** – Imports necessary Python libraries, loads the dataset and displays the first few rows.
2. **Exploratory Data Analysis (EDA)** – Computes summary statistics, visualizes the distribution of numeric features and examines correlations between variables.
3. **Visualizations** – Generates histograms and a correlation heatmap to identify patterns and relationships.
4. **Predictive Modeling** – Builds a machine learning pipeline using one‑hot encoding for categorical variables and a random forest classifier to predict whether an order will be returned. The model’s performance is evaluated using accuracy and a classification report.
5. **Conclusion** – Summarizes findings and discusses potential improvements.

This notebook showcases common tasks performed by business analysts, program managers and data analysts, including data exploration, visualization and predictive analytics.

## Getting Started

Follow these steps to run the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/your-username/synthetic-sales-analysis.git
   cd synthetic-sales-analysis
   ```

2. **Create a virtual environment (optional but recommended)**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook**

   ```bash
   jupyter notebook sales_analysis_notebook.ipynb
   ```

   or use VSCode or another IDE to open the notebook.

5. **Explore and extend**

   Feel free to modify the notebook, experiment with different visualizations, and try other machine learning algorithms. You can also generate additional synthetic data or apply the workflow to real datasets.

## Contributing

This repository is intended as a showcase project. If you find bugs or have suggestions for improvements, feel free to fork the repository and submit a pull request.
