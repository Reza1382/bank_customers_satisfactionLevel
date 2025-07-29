# 🏦 Bank Customer Satisfaction Analysis

A comprehensive data analysis project examining customer satisfaction patterns in banking using Python and statistical methods.

## 📊 Project Overview

This project analyzes a synthetic but realistic dataset of 300 bank customers to understand factors affecting customer satisfaction and churn behavior. The dataset includes various customer attributes such as age, gender, income, credit card ownership, number of products used, satisfaction levels, and churn status.

To simulate real-world data challenges, the dataset intentionally contains **missing values** in key numerical columns including age, income, and satisfaction levels.

## 🎯 Project Objectives

1. **Data Preprocessing**: Learn essential data cleaning techniques including handling missing values, data types, and value distributions
2. **Descriptive and Visual Analysis**: Gain insights into relationships between customer features and behaviors
3. **Statistical Analysis and Clustering**: Examine factors influencing customer satisfaction and loyalty

## 📋 Dataset Features

| Column | Description |
|--------|-------------|
| `CustomerID` | Unique customer identifier |
| `Age` | Customer age |
| `Gender` | Customer gender |
| `Income` | Monthly income (thousands of dollars) |
| `HasCreditCard` | Whether customer has a credit card |
| `NumOfProducts` | Number of banking products used |
| `SatisfactionLevel` | Customer satisfaction rating (1-5 scale) |
| `Churned` | Whether customer has left the bank (True/False) |

## 🔧 Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization
- **SciPy** - Statistical analysis and hypothesis testing

## 📈 Key Analysis Components

### 1. Data Preprocessing
- Handling missing values using mean imputation for numerical columns
- Removing rows with missing satisfaction levels
- Converting boolean values to binary format for analysis

### 2. Exploratory Data Analysis
- Customer satisfaction distribution analysis
- Gender-based satisfaction comparison
- Correlation analysis between income, age, and satisfaction
- Churn analysis by demographics and product usage

### 3. Statistical Testing

#### T-Test Analysis
**Research Question**: Does having a credit card correlate with customer satisfaction levels?

**Results**:
- t-statistic = 1.23
- p-value = 0.22 (> 0.05)
- **Conclusion**: No significant difference in satisfaction levels between customers with and without credit cards at 95% confidence level

#### ANOVA Analysis
**Research Question**: Do satisfaction levels differ based on the number of products purchased?

**Results**:
- F-statistic = 0.71
- p-value = 0.55 (> 0.05)
- **Conclusion**: No significant difference in satisfaction levels across different product usage groups

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scipy
```

### Running the Analysis
1. Clone this repository
2. Ensure you have the `bank_customers.csv` dataset in the same directory
3. Run the Python script:
```bash
python bank_customers.py
```

## 📊 Key Findings

1. **Credit Card Impact**: No statistically significant relationship between credit card ownership and customer satisfaction
2. **Product Usage**: Number of banking products used does not significantly impact satisfaction levels
3. **Demographics**: Age and gender show minimal correlation with satisfaction and churn behavior
4. **Income Correlation**: No meaningful correlation between customer income and satisfaction levels

## 🔍 Custom Visualization Function

The project includes a custom `plotting()` function that creates standardized visualizations:
- Supports bar plots, line plots, and scatter plots
- Consistent styling and formatting
- Flexible parameter configuration

## 📝 Future Enhancements

- Machine learning models for churn prediction
- Time-series analysis of customer behavior
- Advanced clustering techniques
- Interactive dashboard development

## 🤝 Contributing

Feel free to fork this project and submit pull requests for any improvements or additional analysis techniques.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or suggestions regarding this analysis, please open an issue in this repository.

---

*This project demonstrates fundamental data science techniques including data preprocessing, exploratory data analysis, statistical hypothesis testing, and data visualization in the context of banking customer analytics.*
