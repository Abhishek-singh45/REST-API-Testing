# REST API Testing – Sample Web Application

## Project Overview

This project demonstrates manual REST API testing of a sample web application using Postman. The APIs were tested for functionality, validation, CRUD operations, authentication, response status codes, and negative scenarios.

## Tools & Technologies

* Postman
* REST API
* Jira
* MySQL
* GitHub

## API Modules Tested

* Authentication
* Users
* Products
* Orders

## Testing Performed

* GET, POST, PUT, DELETE
* Positive Testing
* Negative Testing
* Functional Testing
* Validation Testing
* CRUD Testing
* Authentication Testing
* Response Status Code Validation
* JSON Response Validation
* SQL Validation

## Test Cases

A total of **35 practical API test cases** were documented.

| Module         | Test Cases |
| -------------- | ---------: |
| Authentication |         11 |
| Users          |          8 |
| Products       |          8 |
| Orders         |          8 |
| **Total**      |     **35** |

## Defects Identified

During testing, **6 genuine API defects** were identified and documented.

| Bug ID | Module   | Defect                                                           |
| ------ | -------- | ---------------------------------------------------------------- |
| RAT-1  | Orders   | Created order could not be retrieved using returned Order ID     |
| RAT-2  | Users    | Deleted user remained accessible                                 |
| RAT-3  | Users    | Created user could not be retrieved using returned User ID       |
| RAT-4  | Products | Created product could not be retrieved using returned Product ID |
| RAT-5  | Products | Updated product changes were not persisted                       |
| RAT-6  | Products | Deleted product remained accessible                              |

## Project Files

* `API-Test-Cases.xlsx` – API test cases
* `REST_API_Testing_Jira_Bug_Reports.pdf` – Jira bug reports
* `New Collection.postman_collection.json` – Postman API collection

## Key Skills Demonstrated

* REST API Manual Testing
* Postman
* HTTP Methods
* HTTP Status Codes
* JSON Validation
* Positive & Negative Testing
* CRUD Testing
* Authentication Testing
* Jira Defect Reporting
* SQL/MySQL Validation
* Test Case Design

## Project Type

**Manual QA / API Testing Project**

