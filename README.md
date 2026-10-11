# Data-Transformation-and-Modelling-PBI
A Power BI project demonstrating data transformation, data cleansing, and star-schema modeling for e-commerce sales analysis
## Objective
To transform, cleanse, and model e-commerce sales data in Power BI, enabling accurate analysis of sales, profitability, customer trends, and target performance through an optimized data model
## Datasets Used
The project utilizes the following datasets:
- List of Orders
- Order Details
- Sales Target
##Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
## Data Preparation and Transformation
- Imported all source datasets into Power BI.
- Restricted the List of Orders table to the first 500 records.
- Updated data types for Order Date, Amount, and Target fields.
- Standardized Customer Name values using Proper Case formatting.
- Created a Location column by combining City and State.
- Added a Profit Margin calculated column.
- Created a Profit Status conditional column.
- Merged List of Orders and Order Details to create an Orders Data table.
- Reviewed and handled missing values and duplicate records.
- Applied sorting and filtering techniques for analysis.
- Created aggregated tables for order counts, order summaries, and monthly sales targets.
## Data Modeling
A relational model was implemented using a star schema approach
### Fact Table
Order Details
### Dimension Tables
- List of Orders
- Dim Product
- Order Count
### Supporting Tables
- Order Summary
- Sales Target
## Key Learning Outcomes
- Data cleansing and transformation using Power Query
- Data type management and data quality improvement
- Table merging and aggregation techniques
- Dimension table creation
- Relationship management in Power BI
- Star schema design principles
- Business-oriented data modeling
