# Project Overview

This project analyzes the performance of three different implementations (variants) of an in-app currency feature within a live video streaming service. The analysis focuses on daily revenue, user behavior, and retention rates to determine the best variant to roll out.

# Final Recommendation

Variant 2 is recommended for roll-out due to its highest revenue per user and strong performance in the high purchase frequency segment. However, it is advised to incorporate insights from Variant 3, which shows significantly higher retention rates, to improve overall retention.

# Key Components

Data Preparation
Descriptive Statistics and Visualization
Statistical Testing
Retention Rate Analysis
Implementation Plan

# Prerequisites

Install Python 3.9.6 (if not already installed)

### Follow instructions at: https://www.python.org/downloads/release/python-390/

# Install required packages
pip install pandas matplotlib seaborn scipy lifelines scikit-posthocs
Ensure you have the following packages installed:

- pandas
- matplotlib
- seaborn
- scipy
- lifelines
- scikit-posthocs

You can install these packages using pip:

``` pip install pandas matplotlib seaborn scipy lifelines scikit-posthocs```


# How to Run the Code

1. Clone the Repository
2. Prepare the Dataset:

- Ensure your dataset (abc_test_data.csv) is in the same directory as the script or update the file path in the script accordingly.

3. Run the Analysis:

- python main.py

# Findings

✅ Variant 2 is the most effective in terms of total purchased amounts. 
 
✅ There is no significant difference in the single purchase values.

✅ Variant 2 is the most effective in terms of the number of purchases.

✅ Variant 3 shows significantly higher retention rates.

# Conclusion

This README provides a comprehensive guide to running the analysis code, interpreting the results, and implementing the recommendations based on the findings. By following the steps and using the provided code, you can replicate the analysis and make data-driven decisions for feature roll-out.
