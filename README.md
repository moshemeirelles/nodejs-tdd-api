# Books API
[![Build Status](https://travis-ci.org/moshemeirelles/nodejs-tdd-api.svg?branch=master)](https://travis-ci.org/mshmeirelles/nodejs-tdd-api)
[![Coverage Status](https://coveralls.io/repos/github/mshmeirelles/nodejs-tdd-api/badge.svg?branch=master)](https://coveralls.io/github/mshmeirelles/nodejs-tdd-api?branch=master)
[![Code Climate](https://codeclimate.com/github/mshmeirelles/nodejs-tdd-api/badges/gpa.svg)](https://codeclimate.com/github/mshmeirelles/nodejs-tdd-api)

This is an application that returns a list of books, created to apply the best practices of TDD using Node JS, like unit tests, integration tests and contract tests. Libs used: Express, Mocha, Chai and Supertest; implemented using ES6 + Babel and Authorization with Jwt.

## How to develop

1. Clone repository.
2. Install dependencies.
3. Run lint and tests.

```console
git clone git@github.com:moshemeirelles/nodejs-tdd-api.git books-api
cd books-api
npm install
npm test
```

## Authentication

Just POST your email and password to `/token` and you receive your token to access api endpoints.
