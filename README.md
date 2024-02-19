# Banking-Process-Automation-with-UiPath
This project automates the process of transferring funds between bank accounts using Robotic Process Automation (RPA) technology with UiPath.

# Project Overview
Objective: The primary objective of this project is to streamline and automate the bank transfer process, eliminating manual intervention and reducing the risk of errors.

Workflow Description: The workflow consists of sequential steps to assign source and destination accounts, specify the transfer amount, log the start of the process, open the banking application, check the availability of the application, login to the banking account, navigate to the transfer funds page, fill transfer details including source account, destination account, and transfer amount, confirm the transfer, and log the success of the process.

# Implementation Details
Assignments: Assign source account, destination account, and transfer amount variables with appropriate values.

Logging: Log the start of the bank transfer process and retry attempts to open the banking application.

Application Interaction: Open the banking application, login to the banking account, navigate to the transfer funds page, fill transfer details, and confirm the transfer.

Error Handling: Use a loop to check the availability of the banking application and retry opening if not available.
