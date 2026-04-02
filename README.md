![API Tests](https://github.com/Farhod75/moody-api-postman-suite/actions/workflows/api-tests.yml/badge.svg)
# Moody Credit API Test Suite

Portfolio API test suite built by Farhod Elbekov.
Simulates credit account workflows using reqres.in mock API.

## Coverage
- 11 requests across 6 phases
- 38 assertions
- Auth token chaining
- Negative testing
- Performance SLA check

## Tech Stack
Postman · Newman · GitHub Actions CI

## Run locally
npm install -g newman
newman run collections/Moody-Credit-API-Suite.postman_collection.json \
  --environment environments/DEV-Moody-API.postman_environment.json