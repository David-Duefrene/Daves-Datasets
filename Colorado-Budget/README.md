# Colorado Budget
Contains all income and expenses for the Colorado state government.

## Data Structure
Each set is broken up by year.

Data lists are either cabinets, departments, fund categories and funds
`
grand_totals: contains all totals of individual lists
    total_amount: total amount Colorado has spent/earned for the year
    cabinet: year total of all cabinets
    department: year total of all departments
    fund_categories: year total of all fund categories
    funds: year total of all funds
cabinet: contains all cabinets budgets separated by month
department: contains all departments budgets separated by month
fund_categories: contains all fund categories budgets separated by month
funds: contains all funds budgets separated by month
`
