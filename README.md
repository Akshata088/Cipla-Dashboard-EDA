# Cipla Stock Analysis

This project analyzes **Cipla's stock data** using PySpark and Matplotlib to extract meaningful insights about the stock's performance and trends.

## Project Overview

The primary objective of this analysis is to process, analyze, and visualize Cipla stock data to uncover patterns and insights that can aid in decision-making.

### Tools and Technologies
- **PySpark**: For big data processing and analysis.
- **Matplotlib**: For creating visualizations to better understand the data.
- **Pandas**: To handle tabular data operations (if applicable).

---

## Key Steps in the Analysis

1. **Data Ingestion**:
   - Read the stock data from a CSV file using PySpark's `read` functionality.
   - Schema inference for column types.

2. **Data Cleaning and Preparation**:
   - Convert string columns to appropriate date and numeric types.
   - Handle missing or inconsistent data.

3. **Data Analysis**:
   - Analyze key metrics like opening and closing prices, daily highs and lows.
   - Calculate trends such as moving averages or lagged differences using PySpark's window functions.

4. **Visualizations**:
   - Plot stock trends over time using Matplotlib to visualize:
     - Price changes.
     - Volume trends.
     - Other patterns of interest.

  ## Dashboard Analysis
![image](https://github.com/user-attachments/assets/1ad588b4-b423-4543-9608-338e611d11bf)


