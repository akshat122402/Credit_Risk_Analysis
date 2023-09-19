# Credit Risk Analysis

This repository contains Python code for analyzing credit risk using a loan dataset. The analysis explores various aspects of the dataset, including loan status, loan amounts, interest rates, loan grades, home ownership, and more.


## Introduction

This project aims to provide insights and visualizations based on a loan dataset. It covers data preprocessing, exploratory data analysis, and visualization of key factors that may impact loan defaults. The analysis helps in understanding the relationships between various attributes and the loan status and to better understand the credit risk, i.e., the probability of a person defaulting their loan installments.

## Dataset

The dataset used for this analysis is named "LoanStats_2019Q1.csv." It contains loan-related information, such as loan amount, interest rate, loan grade, home ownership, loan status, etc. dated in the first quarter, i.e., January to March, of 2019. The dataset is provided in a CSV format and contains 115675 rows. The original dataset contained 144 columns, but I did intital preprocessing in MS Excel and removed 42 rows which were innecessary for analysis.
You can download the dataset used in this project as a ZIP file.
[Download Dataset ZIP](LoanStats_2019Q1.zip)

## Requirements

To run the code in this repository, you need the following Python libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn
```
## Analysis

The analysis includes the following components:

- Data preprocessing: Handling missing data, cleaning columns, and converting data types.
- Descriptive statistics: Generating basic statistics and data type summaries.
- Exploratory data analysis: Visualizing loan status, loan amounts, interest rates, loan grades, home ownership, and more.
- Correlation analysis: Examining the correlation between numeric attributes.
- Loan status analysis: Investigating loan status categories and their counts.
- Relationship analysis: Exploring the relationships between loan grades, subgrades, home ownership, and loan status.
- Time series analysis: Analyzing loan issuance trends over time and their impact on loan defaults.
- Credit history analysis: Investigating the impact of credit utilization and credit history length on loan defaults.
- Payment and recovery analysis: Calculating total amounts paid by borrowers and exploring recovery efforts.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to contribute to this project by opening issues, suggesting improvements, or submitting pull requests. If you have any questions or feedback, please don't hesitate to reach out.

**Happy coding!**
