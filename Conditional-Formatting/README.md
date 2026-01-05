### Customer Order Analysis - Conditional Formatting (Excel Mini Task)

#### Objective:
The objective of this mini task is to apply Excel Conditional Formatting techniques to highlight important business conditions and data quality issues within a customer order dataset. This improves data readability and supports faster analytical insights.


#### Dataset Overview:
The dataset contains customer order information with the following relevant attributes:

1. Order Date
2. First Name
3. Last Name
4. Full Name
5. Age
6. Gender
7. Address
8. Order Total
9. Ordered Date
10. Returned 
11. Email


#### Business Problems Addressed:
This analysis focuses on answering the following questions:

1. Which orders occurred within the most recent month?
2. Are there any duplicate order entries in the dataset?
3. Which customers placed high-value orders?
4. Which orders were returned?


#### Conditional Formatting Rules Applied:

1. Orders Occurring in the Last Month
A date-based conditional formatting rule was applied to identify orders that occurred within the last month.
Formatting applied: Yellow fill
Purpose: To quickly identify recent customer activity

2. Duplicate Order Entries
Duplicate values were identified using Excel’s built-in duplicate formatting rule.
Formatting applied: Red fill
Purpose: To detect duplicate records that could impact reporting accuracy

3. High-Value Orders (Formula-Based Rule)
A formula-based conditional formatting rule was applied to identify high-value orders.
Highest order value in the dataset: 16000
Mid-value threshold considered: 8000
Closest practical value identified: 7200

Formula used:
=$H2 >= $H$11

Formatting applied: Green fill
Purpose: To highlight customers with significant purchase values

4. Returned Orders
A text-based conditional formatting rule was applied to identify returned orders.
Condition: Returned equals "Yes"
Formatting applied: Red fill
Purpose: To quickly identify returned orders for further analysis


#### Key Insights:

1. The application of conditional formatting enables:
2. Clear visibility of recent transactions
3. Easy identification of duplicate records
4. Quick recognition of high-value customers
5. Immediate detection of returned orders


#### Tools Used:

1. Microsoft Excel
2. Conditional Formatting
3. Formula-based rules


#### Outcome:
This mini task demonstrates practical Excel skills including:

1. Applying multiple conditional formatting rules
2. Using formula-driven logic for business analysis
3. Enhancing data clarity and interpretability
