# JSONPlaceholder API Tests

A Postman collection testing the [JSONPlaceholder](https://jsonplaceholder.typicode.com/) REST API.

## What's tested
- GET /posts, /users, /comments
- POST /posts (create)
- PUT/PATCH /posts (update)
- DELETE /posts
- Edge cases (e.g. filter with no matches → 404)

## Test Results
- 9 requests | 42 tests | 100% passing

## How to run
npx newman run JSONPlaceholder-API-Test.postman_collection.json
