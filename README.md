# ZMM Customer ALV Report

This is an ABAP program that fetches customer data from the KNA1 table and displays it in an ALV grid format. The report allows filtering by customer number and presents details such as customer number, name, city, and country.

## Features:
- **Customer Details:** Retrieves customer information from the KNA1 table (including customer number, name, city, country).
- **ALV Grid Display:** Uses the `REUSE_ALV_GRID_DISPLAY` function to display the results in an ALV grid.
- **Customer Filtering:** The user can filter the results by entering a customer number in the selection screen.

## Prerequisites:
- **SAP System:** This report is intended for use in an SAP system with access to the KNA1 table.
- **Authorization:** Ensure that you have the necessary authorizations to run the report and access customer data.

## How to Use:
1. Run the report in the SAP GUI.
2. Enter a customer number in the selection screen (optional). If no customer number is entered, all customers will be displayed.
3. The report will fetch customer details from the KNA1 table and display them in an ALV grid.

## Installation Instructions:
1. Copy the ABAP code into your SAP system.
2. Create a new report program (e.g., `ZMM_CUSTOMER_ALV`) and paste the code.
3. Activate the program.
4. Execute the program and view the results.

## Contributions:
- Feel free to fork the repository, make changes, and create a pull request.
- Bug reports and suggestions for improvements are welcome.

