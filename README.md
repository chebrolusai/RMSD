<h1 align="center">RMSD</h1>

#### About

The proposed Retail Management System Database (RMSD) addresses the complex needs of retail operations by providing a structured and centralized data management solution. The RMSD will streamline processes, reduce errors, and offer actionable insights into all levels of the retail operation, from point-of-sale transactions to inventory restocking and employee information.

#### Built using

<img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=black">

#### ER diagram

<img width="1438" alt="Screenshot 2024-04-12 at 12 24 45 PM" src="https://github.com/shivabhargavbhuvanam/RMSD/assets/145069226/f81d6ebe-2af4-4acd-9829-f34bc20096ce">

#### Roles

- Store Owner
- Manager
- Inventory Clerk
- Sales Representative
- Accountant

#### Project Structure

- Data Model ( Normalised )
- Tables and Views
- Stored Procedures
- Functions
- Triggers
- Reports

#### Project Features

- The Model/Schema setup ( admin + store owner script) when run in order can be executed any number times without any ORA Errors
- Multiple Roles focussing on security and principle of least priviledge
- Well defined Exception handling with clear and concise error messages
- Input based reports to give quarterly analysis of the store
- Unit testing of functions and procedures with both positive and negative test cases

#### Note

In this system, the <b> STORE_OWNER </b> is the <b> Application Admin </b> created by the DB Admin.

#### Usage

<b> Invoke the scripts in this order </b>

1. Run the script admin_script.sql first, under Scripts/Admin ( db admin )
2. Run the script store_owner_script.sql, under Scripts/Store_owner ( application admin )
