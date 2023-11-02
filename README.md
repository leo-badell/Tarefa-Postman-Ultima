Project 1: Third Testing Collection

This Postman collection, named "Third Testing Collection," is designed for testing API endpoints related to the JSONPlaceholder API. It includes a set of API requests, each with associated test scripts to validate the API responses.

Info:

Collection ID: c717c03b-d895-4e54-901f-46fe1db24b52
Collection Schema: Collection v2.1.0
Exporter ID: 23679802
API Endpoints and Tests:

GET Users: API endpoint: https://jsonplaceholder.typicode.com/users/
Test: Response time is less than 200ms
GET Users by Name: API endpoint: https://jsonplaceholder.typicode.com/users/?name=Ervin Howell
Test: Response time is less than 200ms
GET Users by Phone: API endpoint: https://jsonplaceholder.typicode.com/users/?phone=(254)954-1289
Test: Status code is 200
GET Users by Website: API endpoint: https://jsonplaceholder.typicode.com/users/?website=ambrose.net
Test: Status code is 200
Dynamic URL: API endpoint: {{url}}/users/
This request uses a dynamic URL, and the value of {{url}} should be provided during execution.
This collection is primarily focused on testing the response times and status codes of different API endpoints related to user data.

Project 2: Globals

This Postman environment, named "Globals," defines global variables that can be used across collections and requests within Postman. These global variables are used to manage different base URLs for API requests and endpoints.

ID: e75b5fc6-8b0c-434b-8ef1-a0aa4f67f6a3

Global Variables:

int: Base URL for a shop API: https://api.predic8.de/shop/
url: Base URL for JSONPlaceholder API: https://jsonplaceholder.typicode.com/users/
Postman Export Details:

Exported at: 2022-10-10T00:24:21.988Z
Exported using Postman version: 10.0.20
These global variables are meant to simplify the management of base URLs for different APIs and can be accessed across various collections and requests within Postman.
