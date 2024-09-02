# Insurance Claims Analysis Dashboard for Prism Insurance Pvt. Ltd.

## Project Overview

The insurance industry deals with vast amounts of data, and understanding this data is crucial for improving business operations. This dashboard is designed to give a comprehensive view of the claims data, showcasing key metrics such as premium amounts, coverage amounts, claim statuses, policy types, and customer activity. The dashboard also incorporates role-level security (RLS) to ensure that users can only view data relevant to their roles.

## Key Features
- Interactive Dashboard: Users can filter the data by policy number, claim number, and customer ID to view specific information.

- **Premium Amount and Coverage Amount:** Displays the total premium collected and the total coverage amount, providing a snapshot of the financial scale of the business.

- **Claim Amount:** Shows the total claim amount, helping assess the financial liabilities.

- **Number of Claims by Claim Status:** Visualizes the distribution of claims across different statuses (Rejected, Settled, Pending), offering insights into the processing efficiency and challenges.

- **Premium Amount by Policy Type:** Breaks down premium contributions by different policy types (Travel, Health, Auto, Life, Home), helping identify the most profitable segments.

- **Claim Amount by Age Group:** Analyzes the claim amounts based on different age groups, aiding in understanding the demographic trends in claims.

- **Count of Active/Inactive Customers:** Illustrates the proportion of active versus inactive customers, providing insights into customer engagement and retention.

- **Policy Type Summary Table:** A tabular summary of the pending and rejected claims by policy type, enabling a quick overview of the claims landscape.

## Recommendations

- **Streamline Claims Processing:** Address the high number of pending and rejected claims to improve settlement times and customer satisfaction.

- **Focus on High-Premium Policies:** Invest in marketing Travel and Health policies, as they contribute the most to premium revenue.

- **Boost Customer Retention:** Target inactive customers with personalized offers to increase renewals and lifetime value.

- **Cater to Adult Demographic:** Develop specialized products for the Adult age group, which has the highest claim amounts.

- **Leverage Predictive Analytics:** Use data to forecast claims and adjust premium rates proactively.

## Technical Stack 

- **Power BI:** Used for creating the interactive dashboard and visualizing the claims data.
- **MSSQL Server:** Utilized for storing and querying the claims data.
- **SQL:** Used for data manipulation and to write complex queries for data retrieval and analysis.
- **DAX (Data Analysis Expressions):** Used within Power BI to create calculated columns, measures, and custom tables.
- **Role-Level Security (RLS):** Implemented in Power BI to restrict data access based on user roles.

