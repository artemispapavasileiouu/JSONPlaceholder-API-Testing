# JSONPlaceholder API Testing with Postman

## Project Overview

This project demonstrates basic REST API testing using Postman and the JSONPlaceholder test API.

The goal is to validate HTTP responses, status codes, response data, data types, and filtering behavior through automated Post-response tests written in JavaScript.

## Tools & Technologies

- **Postman** — API requests and test execution
- **JavaScript** — automated API assertions
- **REST API** — HTTP methods and response validation
- **JSON** — request and response data
- **JSONPlaceholder** — public test API

## Test Scenarios

| Request | Method | Validation |
|---|---|---|
| Get Single Post | GET | Status code, JSON response, post ID, title, body, user ID |
| Get All Posts | GET | Status code, array structure, 100 posts, required fields, unique IDs |
| Create Post | POST | Status code 201, generated ID, submitted data |
| Get Posts by User | GET | Status code, array structure, user ID filtering, titles |
| Delete Post | DELETE | Status code and response structure |

## Test Results

All implemented Post-response tests passed during execution in Postman.

- GET Single Post: 5 tests
- GET All Posts: 5 tests
- POST Create Post: 5 tests
- GET Posts by User: 4 tests
- DELETE Post: 2 tests

**Total: 21 passing assertions across 5 requests.**

## How to Run the Tests

1. Download or clone this repository.
2. Open Postman.
3. Select **Import**.
4. Import `JSONPlaceholder_API_Testing.postman_collection.json`.
5. Open the imported collection.
6. Run the requests individually using **Send**, or execute the collection using **Run**.
7. Review the test results in Postman.

## API Base URL

`https://jsonplaceholder.typicode.com`

## Notes and Limitations

JSONPlaceholder is a mock API for testing and learning purposes. POST and DELETE operations are simulated and do not permanently modify the underlying data.

The reported test results reflect the execution performed during this project and may vary if the API behavior changes.

## Skills Demonstrated

- REST API testing
- HTTP methods: GET, POST, DELETE
- HTTP status code validation
- JSON response validation
- Automated assertions in JavaScript
- Query parameter testing
- API test organization in Postman
