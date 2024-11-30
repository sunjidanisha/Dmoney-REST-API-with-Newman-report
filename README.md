# DMoney API Testing Project with Newman Report

## Table of Contents
- [Overview](#overview)
- [Test Scenarios](#test-scenarios)
- [API Details](#api-details)
- [How to Execute the Project](#how-to-execute-the-project)
- [Postman Documentation](#postman-documentation)
- [Technologies Used](#technologies-used)
- [Test Cases](#test-cases-writing)
- [Bug Report](#bug-report)
- [Newman Report](#newman-report)
  

---

## Overview
The DMoney project serves as a simulation platform for financial transactions, allowing users to transfer virtual funds. It is designed for testing and learning purposes.

---

## Test Scenarios
1. **Set up an Admin account with an Agent, two Customers, and a Merchant.**  
   - **Admin Login:**  
     - **Email:** `admin@roadtocareer.net`  
     - **Password:** `1234`

2. **Transfer funds from the SYSTEM account to the Agent.**  
   - **Account Type:** SYSTEM  
   - **Transaction Range:** 10 TK to 10,000 TK  

3. **Agent transfers money to a Customer.**  
   - **Source Account:** Agent  
   - **Destination Account:** Customer  

4. **Verify the Agent’s account balance.**

5. **Send money between two Customers.**  
   - **Source Account:** Customer  
   - **Destination Account:** Customer  

6. **Withdraw funds from a Customer’s account to the Agent’s account (valid range: 10 TK to 10,000 TK).**  
   - **Source Account:** Customer  
   - **Destination Account:** Agent  

7. **Check the Customer’s account balance and verify transactions using the transaction ID.**

8. **Make a payment from a Customer to the Merchant.**  
   - **Source Account:** Customer  
   - **Destination Account:** Merchant  

9. **Second Customer reviews both balance and transaction details.**

10. **Merchant verifies their account balance.**

# API Endpoint Details

- **User API Endpoints**: [https://dmoney.roadtocareer.net/api-docs/user](https://dmoney.roadtocareer.net/api-docs/user)
- **Transaction API Endpoints**: [https://dmoney.roadtocareer.net/api-docs/transaction](https://dmoney.roadtocareer.net/api-docs/transaction)
- **Secret Key**: `X-AUTH-SECRET-KEY: ROADTOSDET`

## How to Run the Project

1. Clone this project:
   ```bash
   git clone https://github.com/sunjidanisha/Dmoney-REST-API-with-Newman-report
   
2. Open the project in any code editor or command shell.
3. Install the required dependencies
4. Run the Newman collection

## Technology Used

1. **Postman**: Download and install Postman if you haven't already.  
   - [Download Postman](https://www.postman.com/downloads/)

2. **Newman**: Used to run Postman collections from the command line.


## Test Case Writing

The detailed test cases for the DMoney API project are documented in a Google Spreadsheet. You can access the test cases via the link below:

- [Test Case Documentation](https://docs.google.com/spreadsheets/d/1FJTX9dt9_kpmztrkpIhsyNAztk3a6d14-J3_z3k-j3M/edit?gid=782524371#gid=782524371)


## Bug Reporting

The identified bugs during the testing phase of the DMoney API project are documented in a Google Spreadsheet. You can access the bug report via the link below:

- [Bug Report Documentation](https://docs.google.com/spreadsheets/d/1YnOSWtBFijrBQ2kypZwESQKJKyADX1nW_kon_EWq82M/edit?usp=sharing)

## Newman report
![image](https://github.com/user-attachments/assets/d5cd511f-513f-472f-9100-445bd01d7362)
![image](https://github.com/user-attachments/assets/7ce4d0f9-c074-499b-879d-2a10e159bb8a)

## Total request
![image](https://github.com/user-attachments/assets/8ca6f14a-8f8d-4b2b-a128-18ba0e014b6d)
![image](https://github.com/user-attachments/assets/26f02029-4920-4fb1-8d39-6888876ad901)






