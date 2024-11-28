# **DMoney Rest API with Newman Report -  Testing Project**

## **Content**
- [Introduction](#introduction)
- [Test Cases Scenario](#test-cases-scenario)
- [API Endpoint Details](#api-endpoint-details)
- [How to run the project](#How-to-run-the-project)
  
  
## Introduction

The DMoney project is a demonstration platform designed to simulate financial transactions where users can transfer virtual or demo money.

## Test cases scenario

1. Admin creates an Agent, 2 random Customers, and a Merchant.  
   - **Admin email**: `admin@roadtocareer.net`  **Password**: `1234`
2. Deposit some money from the SYSTEM account to the Agent.  
   - **System account**: `SYSTEM`  **Range**: 10 TK to 10,000 TK
3. Agent deposits money to one of the Customers.
   - **Hint**: fromAc: `Agent`, toAc: `Customer`     
4. Check the Agent's balance.
5. Then, send money from one Customer to another Customer.
   - **Hint**: fromAc: `Customer`, toAc: `Customer`  
6. Withdraw any amount from a Customer to the Agent (range 10 TK to 10,000 TK).
   - **Hint**: fromAc: `Customer`, toAc: `Agent`  
7. Check the Customer's balance and transaction statement by trnxId.
8. Make a payment from the second Customer to the Merchant.
   - **Hint**: fromAc: `Customer`, toAc: `Merchant`  
9. The second Customer checks both balance and transaction statement. 
10. The Merchant checks his balance.

## API Endpoint Details

- **User API Endpoints**: [_https://dmoney.roadtocareer.net/api-docs/user_](https://dmoney.roadtocareer.net/api-docs/user)

- **Transaction API Endpoints**: [_https://dmoney.roadtocareer.net/api-docs/transaction_](https://dmoney.roadtocareer.net/api-docs/transaction)
- **Partner Key**: X-AUTH-SECRET-KEY: `ROADTOSDET`

## How to run the project

- clone this project
    ```console
    <p align="center">
      https://github.com/rashadkhan97/DMoney-REST-API-with-Newman-Report.git
    </p>
    ```
- Open with any code editor / Command Shell
- Give the following command ```npm i``` and ```node .\report.js```


