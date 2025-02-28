# Data Science Assignment

## Overview
This project involves data analysis and visualization using Python. The dataset is analyzed for customer churn trends based on various features such as customer service calls, voice mail plans, international plans, and other relevant attributes.

## Features
- **Exploratory Data Analysis (EDA)**
  - Distribution of Customer Service Calls
  - Churn Distribution by Voice Mail Plan
  - Churn Distribution by International Plan
  - Number of Customer Service Calls by Churned Customers (State-wise & Area Code-wise)
  - Churn-wise Charge Distribution
  - Correlation Heatmap of Dataset
  - Scatter Plots and Pair Plots for Charge & Minutes

- **Data Visualization**
  - Histograms, Bar Charts, Scatter Plots, and Heatmaps using `matplotlib` and `seaborn`
  - Percentage-based comparison of churned vs non-churned customers

## Installation
To run the project, ensure you have Python installed along with the required libraries. Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn
```

## Usage
Run the Jupyter Notebook or Python script to execute the data analysis:

```bash
jupyter notebook
```

or

```bash
python analysis.py
```

## Dataset
The dataset contains customer data, including the following features:
- **Customer Service Calls** - Number of times a customer contacted support
- **Churn** - Whether the customer left the service (1 = Yes, 0 = No)
- **VM_Plan** - Subscription to a Voice Mail Plan
- **Intl_Plan** - Subscription to an International Plan
- **State & Area Code** - Geographical details
- **Day, Evening, and Night Charges & Minutes** - Usage details

## Visualizations
This project generates various insights using:
- Histograms for data distribution
- Bar charts for categorical comparisons
- Heatmaps to analyze feature correlation
- Scatter plots for charge and minute usage trends

## GitHub Setup
If you face issues pushing to GitHub, try the following:

```bash
git pull origin main --rebase
git push origin main
```

## Contributing
If you wish to contribute, feel free to fork the repository and create a pull request.

## License
This project is for educational purposes only.

---

**Author:** Tanishq Tyagi  
**GitHub:** [tanishq-t](https://github.com/tanishq-t)

