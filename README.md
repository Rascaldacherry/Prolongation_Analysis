# Prolongation_Analysis
The head of the customer support department wants to get information about how well the employees of his department (account managers) are coping with one of their main tasks - prolongation of contracts with clients. From the analyst, he wants to receive a report on employee extensions for 2023.

# Description
The company uses two prolongation coefficients:
- For projects extended in the first month, the ratio of the shipment amount of projects extended in the first month after completion to the shipment amount of the last month of implementation of all projects completed last month.
- For projects extended in the second month, the ratio of the shipment amount of projects extended in the second month to the shipment amount of the last month of projects not extended in the first month.

# Data
There are two sets of data available:

`extensions.csv`:
1. id – id of project
2. id month – the last month of the project implementation
3. AM – full name of the responsible account manager (data is primary in relation to financial_data)

`financial_data.csv`:
1. id – the project ID
2. The reason for the duplicate is the reason why rows with the same id occur multiple times.
3. Columns with the name of the month – the amount of project shipments in a given month
4. Account – Full name of the responsible account manager
