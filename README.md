# Internet Prices Analysis 

This project examines internet prices in different countries, comparing them with other economic indicators such as wages, GDP per capita, and internet usage rates. The analysis provides insights into the factors influencing internet prices and discusses trends across various income levels.

## Table of Contents

1. [Datasets Used](#datasets-used)
2. [Techniques Employed](#techniques-employed)
3. [Key Findings](#key-findings)
4. [Challenges Encountered](#challenges-encountered)
5. [Data Visualization](#data-visualization)
6. [Additional Notes](#additional-notes)

### **Datasets Used**

The following datasets were used in this analysis:

- Internet Prices: Sourced from Numbeo.com and Kaggle.com.
- Internet Usage Rates: Sourced from World Bank data.
- GDP per Capita: Data from World Bank.
- Wages: Sourced from Kaggle.com, originally from World Bank and Numbeo.com.

### **Techniques Employed**

- Data merging with Pandas.
- Data visualization with Matplotlib and Plotly Express.
- Data conversion (from Excel to CSV, regular expression to float).
- Web scraping for Numbeo.com data.
- Statistical analysis with Pandas.

### **Key Findings**

- Internet Prices vs. Wages: There are significant disparities in internet prices relative to wages across different countries. Some high-income countries, like the United States and Australia, have similar internet prices but different wage levels.
- Internet Prices vs. GDP Per Capita: The ratio between internet prices and GDP per capita varies significantly across countries. Discrepancies were noted in the classification of some countries by the World Bank.
- Internet Prices vs. Internet Usage Rates: The data suggests that high internet usage might correlate with lower internet prices, but more research is needed.

### **Challenges Encountered**

- The original datasets had inconsistencies in data format, requiring additional conversion steps.
- Some datasets lacked complete information for certain countries or time periods, leading to the use of older data for analysis.

### **Data Visualization**

Visualizations were created to represent various analyses:

- Internet Prices vs. Wages: Bar charts depicting the ratio between internet prices and wages for different countries.
- Internet Usage Rates: Choropleth maps showing global internet usage rates.
- GDP per Capita vs. Internet Prices: Horizontal bar charts visualizing the ratio between internet prices and GDP per capita.

### **Additional Notes**

- The analysis emphasized 10 selected countries, representing a range of income levels and geographical regions.
- The project scope does not include in-depth analysis of every country or factors like government regulations and infrastructure.

*Author: https://github.com/randomoi*