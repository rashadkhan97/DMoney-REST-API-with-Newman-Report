# **DMoney Rest API with Newman Report -  Testing Project**

## **Content**
- [Introduction](#introduction)
- [Test Cases Scenario](#test-cases-scenario)
- [API Endpoint Details](#api-endpoint-details)
- [How to run the project](#How-to-run-the-project)
- [Postman API Documentation](#postman-api-documentation)
- [Technology Used](#Technology-Used)
- [Test Case Writing](#test-case-writing)
- [Bug Reporting](#bug-reporting)
- [Newman Report](#newman-report)
    - [Report Summary](#report-summary)
    - [Total Requests](#total-requests)
  
  
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
      https://github.com/rashadkhan97/DMoney-REST-API-with-Newman-Report.git
    ``` 
- Open with any code editor / Command Shell
- Give the following command ```npm i``` and ```node .\report.js```

## Postman User Documentation
  
  - **https://documenter.getpostman.com/view/28551494/2sAYBXBqaE**
  

## Technology Used
- Postman: If you haven't already, [download and install Postman.](https://www.postman.com/downloads/)
- Newman

## Test Case Writing
For view purposes, one of an feature test case writing sheet screenshot is given. For better understanding click the link below - [**Test Case Writing Sheet Link**](https://docs.google.com/spreadsheets/d/1cZdk7-ELz-Vps4aKg5e9OVTR-lj1iIwB/edit?usp=sharing&ouid=113748567292900710037&rtpof=true&sd=true)


![image](https://github.com/user-attachments/assets/711ee1b3-e9f3-48ed-9e93-a7faf697df3d)


## Bug Reporting
For more clear view click on the link - [**Bug Report Sheet Link**](https://docs.google.com/spreadsheets/d/1yvT0-m4jE2ueoB4oioztYkPadFLr6Yva/edit?usp=sharing&ouid=113748567292900710037&rtpof=true&sd=true)

<p align="center">
  <img src="https://github.com/user-attachments/assets/6022fe15-79b1-4922-968b-6c87294974a0" />
</p>


## Newman Report
### Report Summary 

![image](https://github.com/user-attachments/assets/0509a5bb-f58e-4532-8256-520ac70a20bf)
![image](https://github.com/user-attachments/assets/9c7b876b-1bef-44cb-b21b-c92dcb985eef)

### Total Requests
![image](https://github.com/user-attachments/assets/c1a37253-58c9-437b-916e-ff01dff176e7)
![image](https://github.com/user-attachments/assets/c0b5fdc1-d46a-482b-a1b6-0654e1736d5b)




