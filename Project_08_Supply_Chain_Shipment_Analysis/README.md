# Supply Chain Insights: Analyzing Shipment Data for Pricing Trends and Anomalies

## Project Overview
This project analyzes a shipment dataset to uncover insights into pricing trends and patterns within the supply chain. The program identifies outliers or anomalies in the data and generates a summary report highlighting the findings.

## Key Features
1. **Data Loading**: Loads the shipment dataset for analysis.
2. **Data Summary**: Provides a concise summary of the dataset.
3. **Outlier Detection**: Identifies outliers using box plots.
4. **Descriptive Statistics**: Generates summary statistics for the dataset.
5. **Summary Report**: Creates a detailed report on pricing trends and patterns.

## Libraries Used
- `pandas`
- `seaborn`
- `matplotlib`

## Code Explanation
- **Data Loading**: Loads the shipment dataset and displays the first few rows.
- **Data Summary**: Prints a concise summary and generates descriptive statistics.
- **Outlier Detection**: Uses box plots to identify anomalies in numerical columns.
- **Summary Report**: Creates a report that provides insights into pricing trends and patterns.

## Code Structure
1. Load and explore the dataset.
2. Summarize the dataset with descriptive statistics.
3. Check for missing values.
4. Visualize numerical columns using box plots.
5. Generate a summary report.
   
## Prerequisites
- Python 3.8+
- Pandas, Seaborn, Matplotlib

## Explanation
This project involves analyzing a shipment dataset to provide insights into pricing trends and patterns within the supply chain. The dataset includes information about shipment IDs, project codes, countries, shipment modes, item quantities, values, and various costs.

The first step is loading the dataset into a Pandas DataFrame and displaying the first few rows. A concise summary of the dataset is printed, showing data types, non-null counts, and memory usage. Descriptive statistics are generated to provide summary statistics for numerical columns.

Next, the program checks for missing values in each column and visualizes numerical columns using box plots to identify any outliers or anomalies. The summary report provides insights into the basic information about the dataset, summary statistics, and missing values.

The analysis reveals that 'Line Item Value' has the maximum number of outliers, indicating potential anomalies in the pricing data. This information can be used for further investigation to ensure data quality and accuracy.

## Insights
1. **Outlier Detection**: Identified 'Line Item Value' as having the maximum number of outliers, which may require further investigation.
2. **Data Completeness**: Found missing values in columns like 'Shipment Mode', 'Dosage', and 'Line Item Insurance (USD)', which need to be addressed for accurate analysis.
3. **Descriptive Statistics**: Provided a comprehensive summary of the dataset, helping understand the distribution and central tendencies of key attributes.

## Future Enhancements
- **Predictive Analytics**: Develop models to predict shipment costs and delivery times based on historical data.
- **Interactive Dashboards**: Create interactive visualizations and dashboards for real-time monitoring of supply chain metrics.
- **Anomaly Detection**: Implement advanced anomaly detection techniques to automatically flag suspicious data points.

