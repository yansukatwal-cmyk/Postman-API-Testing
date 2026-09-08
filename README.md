# Postman API Testing

A beginner-friendly API testing project using **Postman** and the public **JSONPlaceholder REST API**.

I created this project to practice API testing, writing test scripts, checking responses, and testing different HTTP methods.

## What I Tested

The test cases cover:

* Get all users
* Get a single user
* Get an invalid user
* Create a user
* Update a user
* Delete a user
* Create a user with missing data
* Get users using query parameters
* Get posts by user ID
* Get comments by post ID

## Test Results

* **Total test cases:** 10
* **Passed:** 10
* **Failed:** 0
* **Pass rate:** 100%

## HTTP Methods Used

* GET
* POST
* PUT
* DELETE

## Testing Performed

The Postman tests include:

* Status code validation
* Response body validation
* JSON data validation
* Query parameter testing
* Positive testing
* Negative testing
* Basic response-time validation

## Files

```text
Postman-API-Testing
│
├── JSONPlaceholder_API_Testing.postman_collection.json
├── API_Test_Cases.xlsx
└── README.md
```

### Postman Collection

The `.json` file contains the API requests and Postman test scripts used during testing.

### API Test Cases

The Excel file contains the documented test cases, expected results, actual results, and test status.

## Tools Used

* Postman
* JavaScript
* JSONPlaceholder API
* Git & GitHub

## About JSONPlaceholder

JSONPlaceholder is a free fake REST API used for testing and learning. Since it is a mock API, actions such as creating, updating, and deleting data are simulated and are not permanently stored.

## Purpose

The goal of this project was to get practical experience with API testing using Postman and understand how QA testers validate API requests and responses.
