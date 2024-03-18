# GoRestAPI

## Introduction
This README provides guidelines and examples for testing the GoRest API using various endpoints. The GoRest API provides endpoints for managing users, posts, comments, and more.

## API Base URL
The base URL for the GoRest API is: `https://gorest.co.in/public/v2

## Authentication
Some endpoints may require authentication. To obtain an access token for authentication, you can sign up on the GoRest website and obtain an API token.

## Testing Endpoints
-Users (/users)
-Posts (/posts)
-Comments (/comments)

## Setup and Testing Guidelines
- Download the collections and environment to Postman app
- Ensure that you have a valid access token for endpoints that require authentication (PUT, POST, PATCH, DELETE).
- Put your token on the Token variable on QA environment.
- Run the collection by clicking three dots at the root folder and select Run collection option
- It could be run each test folder separately by clicking three dots on the wanted folder and select Run folder option.
- Verify the response status codes for each request to ensure proper handling of requests.
- Another way to get the tests is by workspace for Postman on https://www.postman.com/galactic-crater-982733/workspace/gorest-api-testing

## Feedback and Issues
If you encounter any issues or have feedback regarding the GoRest API, you can reach out to the GoRest team through their website or support channels.

## Disclaimer
This README is for testing purposes only and should not be considered as exhaustive documentation. Always refer to the official documentation for comprehensive information about the GoRest API.
