# **Churn Detective: Diagnosing Customer Turnover**

![Project Banner](data/Customer-churn.jpg)

## **Project Overview**

Customer churn is a critical metric for any business, especially in the highly competitive telecommunications industry. Understanding why customers leave and identifying the factors contributing to churn can help companies develop strategies to retain their customers, thereby improving profitability and customer satisfaction.

In this notebook, we analyze the Telco Customer Churn dataset, provided by IBM, which contains various demographic, account, and service-related attributes of customers from a specific period of time. By exploring these variables, we aim to identify patterns and key indicators of churn. Through a combination of categorical and numerical data analysis, along with correlation and feature importance studies, this analysis will provide insights that can guide targeted retention strategies and predictive modeling efforts.

## **Table of Contents**

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## **Dataset**

- **Source:** The dataset is from a telecom company, containing customer attributes such as service usage, contract type, tenure, and whether they churned.
- **Data Features:** The dataset includes features such as customer demographics, service information, account details, and churn status.

## **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/deexposito/Customer_Data_Dashboard.git
   cd Customer_Data_Dashboard


2. Install required dependencies:

```bash
pip install -r requirements.txt
```

## Usage
Open the Jupyter notebook `Customer_Data_Dashboard.ipynb` in your local environment.

Run the notebook to analyze customer churn and generate visualizations.

## Analysis
This project involves several key steps:

1. **Data Cleaning**: Addressing missing values and preparing the dataset.
2. **Exploratory Data Analysis (EDA)**: Investigating customer behavior and service usage patterns.
3. **Statistical Testing**: Applying tests like Chi-square and t-tests to explore relationships between variables.
4. **Clustering Analysis**: Using K-Means to group customers based on similar characteristics.
5. **Interactive Dashboard**: Visualizing churn insights using Dash and Plotly.

## Results
- Identified key factors driving customer churn, including contract type and service usage.
- Developed an interactive dashboard for real-time churn analysis.
- Provided actionable recommendations for improving customer retention.

## Contributing
Contributions, issues, and feature requests are welcome. Check the issues page for more details.

## License
This project is licensed under the MIT License - see the LICENSE file for details.


