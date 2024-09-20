# Home Sales Data Analysis with SparkSQL

<img src="https://images.unsplash.com/photo-1560520031-3a4dc4e9de0c?q=80&w=1973&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Housing Market Analysis" width="25%">

*Photo by [Tierra Mallorca](https://unsplash.com/@tierramallorca) on [Unsplash](https://unsplash.com/photos/JXI2Ap8dTNc)*


This project utilizes Apache Spark's SQL capabilities to analyze home sales data and determine key metrics. The analysis includes creating temporary views, partitioning data, caching and uncaching tables, and verifying the uncaching process. The primary objective is to answer specific business questions related to home sales trends and prices.

## Overview

The real estate market is a significant economic indicator, and understanding trends within this market can provide valuable insights for investors, homeowners, and policymakers. This project focuses on analyzing home sales data to extract meaningful patterns and trends using Apache SparkSQL.

## Dataset

The dataset contains detailed information about home sales, including:

- **Price**: The selling price of the home.
- **Bedrooms**: Number of bedrooms.
- **Bathrooms**: Number of bathrooms.
- **Square Footage**: Total living area.
- **Year Built**: The year the home was constructed.
- **Floors**: Number of floors.
- **View Rating**: A rating indicating the quality of the view from the home.

## Analysis Objectives

The project aims to answer the following key questions:

1. **Average Price for Four-Bedroom Houses Each Year**

   What is the average price for a four-bedroom house sold for each year?
2. **Average Price of Homes Built Each Year with Specific Features**

   What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms?
3. **Average Price for Specific Home Criteria**

   What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?
4. **Average Price per View Rating with High Value**

   What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000?

## Technologies Used

- **Apache Spark SQL**
- **Python 3.x**
- **Jupyter Notebook**
- **Google Colab**

## Results

The analysis will produce the following results:

1. **Average Price for Four-Bedroom Houses Each Year**

   - A table showing the average selling price of four-bedroom houses for each year.
2. **Average Price of Homes Built Each Year with Specific Features**

   - A table displaying the average price of homes built each year that have three bedrooms and three bathrooms.
3. **Average Price for Specific Home Criteria**

   - A table showing the average price of homes that meet the following criteria:
     - Three bedrooms
     - Three bathrooms
     - Two floors
     - Living area greater than or equal to 2,000 square feet
4. **Average Price per View Rating with High Value**

   - A table listing the average home price per "view" rating where the average price is greater than or equal to $350,000.

To see the analysis, please open the [Home Sales Jupyter Notebook](Home_Sales.ipynb)

## Contact

- **Author**: Carlos Ruiz
- **Email**: Carlos.Ruiz@AIDecisions.com
- **GitHub**: [AIDecisions](https://github.com/AIDecisions)

Feel free to reach out for any questions or suggestions.
