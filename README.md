# Exploratory Data Analysis (EDA) on Festival & Seasonal Sales Data

This repository contains detailed Exploratory Data Analysis (EDA) projects focused on analyzing **Festival and Seasonal Sales Data**, including Christmas Shopping Trends and End-of-Season Sale (EOSS) analysis. The projects leverage Python libraries such as **NumPy**, **Pandas**, **Matplotlib**, and **Seaborn** to extract actionable insights from retail sales data.

---

## Project Overview

These EDA projects aim to provide insights into:

- **Peak buying periods** during festive seasons
- **Best-selling product categories**
- **Pricing and discount trends** and their impact on revenue
- **Customer demographics** (age groups, gender, location)
- **Comparative analysis** of sales across different events (Christmas, EOSS, Baseline)

---

## Files in this repository

| Filename                         | Description                                             |
|---------------------------------|---------------------------------------------------------|
| `Seasonal_Sales_EDA.ipynb`       | Jupyter notebook containing step-by-step EDA analysis  |
| `seasonal_sales.csv`              | Sample dataset (replace with your own if needed)       |
| `README.md`                      | This readme file                                        |

---

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook or JupyterLab (optional if using Google Colab)
- Required Python packages:
pip install numpy pandas matplotlib seaborn
Alternatively, you can run the notebook in Google Colab without any setup.

**Running the Notebook**
Clone this repository:

git clone https://github.com/yourusername/festival-seasonal-sales-eda.git
cd festival-seasonal-sales-eda

Open the Jupyter Notebook:
jupyter notebook Seasonal_Sales_EDA.ipynb
Execute the notebook cells step-by-step to perform the analysis.
Or simply upload the notebook and dataset to Google Colab and run it there.
Analysis Steps

The notebook contains the following main sections:
Introduction: Overview of project goals and libraries used.
Data Loading: Loading the sales dataset and inspecting it.
Data Preprocessing: Cleaning data, handling missing values, and creating calculated fields such as Revenue and Age_Group.

Exploratory Data Analysis (EDA):
Sales by product category
Impact of discounts on revenue
Customer demographics (age groups, gender, city)
Revenue comparison across different sales events (Christmas, EOSS, Baseline)

Advanced Insights:
Top products by revenue
Detailed event-wise sales analysis

Conclusion: Summary of findings and recommendations.

Dataset
The sample dataset seasonal_sales.csv contains synthetic or real retail sales data with the following key columns:
Date: Date of transaction
Event: Sale event name (e.g., Christmas, EOSS, Baseline)
Category: Product category (e.g., Electronics, Clothing)
Product_ID: Unique product identifier
Quantity: Number of units sold
Price: Unit price of product
Discount: Discount percentage applied
Customer_Age: Age of the customer
Customer_Gender: Gender of the customer
City: Customer location

**Contribution**
Feel free to fork this repository, enhance the analysis, or add your own datasets and projects.
If you find any issues or have suggestions, please open an issue or submit a pull request.

**License**
This project is open-source and available under the MIT License.

**Contact**
For questions or feedback, please contact:
Your Name – your.email@example.com
GitHub: https://github.com/yourusername

