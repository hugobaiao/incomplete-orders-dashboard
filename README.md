# Introduction

Welcome to the **Incomplete Orders Dashboard** project! This dashboard is designed to streamline the monitoring and sharing of incomplete orders within our work environment. 

## Overview

Every month, we undertake the task of tracking orders that have passed their expected delivery or completion dates but remain unresolved. This process involves gathering weekly files from a global database to ensure comprehensive monitoring. Given the involvement of multiple stakeholders, I've created this dashboard in PowerBI. The dashboard provides a real-time view of our progress, making it easier to share updates and collaborate effectively.
Please note that all data displayed in this dashboard is fictitious and used solely for demonstration purposes. This ensures privacy and confidentiality while providing a clear representation of the dashboard's functionality.

## Key Metrics

The dashboard focuses on several important metrics:
- **Current Week Orders**: The total number of incomplete orders for the current week.
- **Pending Action Orders**: Orders that require immediate action.
- **Pending Response Orders**: Orders awaiting responses.
- **Orders by Owner**: Breakdown of orders by the responsible department.
- **Orders by Issue**: Categorization of orders based on specific issues, whether pending responses, escalated to other departments, or if the issue has been resolved.

## Automation

To ensure accuracy and efficiency, the dashboard is automatically updated using an Excel file received weekly. Additionally, Python scripts are employed to compare and analyze the data week over week, enhancing the reliability of the information presented. 

## Workflow Overview

The main workflow for maintaining the **Incomplete Orders Dashboard** consists of several key steps:

1. **Getting the Raw Data**:
   - Extract data from the global database (QlikSense).

2. **Cleaning the Data**:
   - Thoroughly clean the data and copy all custom columns from previous files.

3. **Comparing Files**:
   - Use Python scripts with the help of Jupyter Notebook to compare the new and previous files.

4. **Uploading and Connecting**:
   - Upload the new file and connect it to the Power BI dashboard.
   - The dashboard is automatically updated whenever there's a change to the Excel file.

This streamlined process ensures that the dashboard remains accurate and up-to-date, providing real-time insights into incomplete orders.

![Dashboard Image](https://github.com/hugobaiao/incomplete-orders-dashboard/blob/main/incomplete_orders.png)
