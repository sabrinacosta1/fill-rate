# Advanced Analysis of Fill Rate with Python

This project showcases an end-to-end process of analyzing sales data, order availability, and compliance with delivery timelines using **Python**. With a strong focus on **data manipulation** and **analysis**, this repository is an excellent example of leveraging Python's **Pandas** and **NumPy** libraries for insights into sales performance and operational efficiency.

## Features

- **Data Extraction**: Import multiple Excel files and process large datasets with ease.
- **Data Filtering**: Filter sales and order data based on specific business rules (e.g., document types, delivery timelines).
- **Performance Metrics**:
  - Calculate and evaluate compliance with predefined delivery standards.
  - Generate delivery performance reports segmented by order type.
- **Custom Logic Implementation**: 
  - Map order types (e.g., `Express`, `Weekly`) and assess compliance based on specific thresholds.
  - Identify pending orders and compute projected delivery dates.
- **Global and Type-Specific Performance Metrics**:
  - Compute delivery success rates for each order type (Express, Weekly, Stock, Programmed).
  - Global compliance rate calculation.
- **Scalable Design**: Easily adaptable for additional datasets, rules, or report requirements.

## Project Structure

- **`Faturamento` Analysis**: Focused on completed orders and compliance with specified delivery timelines.
- **`Separação` Analysis**: Evaluates orders pending fulfillment and tracks readiness for delivery.
- **`Análise Disponibilidade`**: Identifies order availability, calculates projected delivery dates, and checks compliance with deadlines.
- **Performance Metrics**: Delivery compliance rates for each order type and a global summary.

## Technologies Used

- **Python**: Primary programming language for data analysis.
- **Pandas**: Advanced data manipulation and transformation.
- **NumPy**: Efficient numerical operations.
- **Excel Integration**: Seamlessly import and export data to/from Excel files.
