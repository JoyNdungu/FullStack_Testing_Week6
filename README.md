# FullStack_Testing_Week6

This project is a MERN (MongoDB, Express, React, Node.js) application that focuses on implementing reliable testing strategies and debugging techniques to ensure application stability and performance.

The application includes authentication pages (Register, Login, Home) and demonstrates industry-standard testing practices, including unit tests, integration tests, and end-to-end (E2E) tests.

#  Project Overview

This project contains:

A React + Vite frontend

A Node.js + Express backend

User authentication flow

Automated testing for improved reliability

Debugging techniques implemented throughout the development process

# Testing Strategy
1. End-to-End Tests (Cypress)

End-to-end testing simulates the real user experience.
Located in:
```bash
client/cypress/e2e/auth.cy.js
```

Covers:

Register page form interactions

Login form flows

URL redirects

Verifying successful navigation

Run Cypress:
```bash
cd client
npx cypress open
```
2. Unit Tests

Unit tests ensure small, isolated parts of the code behave correctly.

Includes:

Utility functions

Express middleware testing

React components tested in isolation

Run:
```bash
npm test
```
3. Integration Tests

Integration tests verify that multiple parts of the system work together.

Includes:

API endpoints (using Supertest)

Authentication API flow

Database interactions using a test database

# 📸 Screenshots Included

A folder named /screenshots contains:

cypress-tests.png → Cypress interface showing passing E2E tests

coverage-terminal.png → Screenshot of console coverage output from npm test

# 🐞 Debugging Techniques Implemented

Debugging approaches used throughout the project include:

Console logging in backend routes and middleware

Cypress debugging tools (logs, snapshots, command trace)

Browser DevTools for frontend state inspection

Handling async errors in Express using proper try/catch

Validation of API responses during integration tests

React error boundaries for catching UI issues

These techniques help identify and fix issues quickly across both the client and server.

# Running the Application
Frontend
```bash
cd client
npm install
npm run dev
```

Backend
```bash
cd server
npm install
npm run dev
```
Running All Tests
```bash
npm test
```

✔ Project Summary

Fully tested MERN application

Includes unit, integration, and E2E tests

Uses Cypress, Jest, and Supertest

Testing strategy well-documented

Debugging practices implemented across the app

🎉 Thank you for checking out this project!


