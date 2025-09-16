# api-testing-automation
A collection of automated API tests for a public REST API, using Postman, JavaScript, and Newman for CI integration.
## Overview
This repository contains a comprehensive collection of automated tests for RESTful APIs. The tests are written using **Postman** and executed via **Newman** (the Postman CLI), allowing for seamless integration into Continuous Integration/Continuous Deployment (CI/CD) pipelines. The project demonstrates skills in API testing, automation, and quality assurance.

## Features
- **Functional Testing:** Validation of status codes, response bodies, headers, and response times.
- **Data-Driven Testing:** Tests parameterized with external JSON/CSV files for scalable test scenarios.
- **Environment Management:** Uses Postman Environments for variables like base URLs and authentication tokens.
- **CI/CD Integration:** Includes a GitHub Actions workflow to run the test suite automatically on every push or pull request.
- **Detailed Reporting:** Generates HTML and JUnit reports for easy result interpretation and historical tracking.

## Tech Stack
- **Postman:** For designing and organizing API requests and test scripts.
- **Newman:** Command-line collection runner for Postman.
- **JavaScript:** For writing Postman test scripts (pm.* API).
- **GitHub Actions:** For CI/CD automation.

## Project Structure
api-testing-automation/
├── collections/ # Postman collection exports (.json)

├── environments/ # Postman environment exports (.json)

├── data/ # Data files for data-driven testing (.json, .csv)

├── scripts/ # Optional helper scripts (e.g., pre-processing data)

├── reports/ # Generated test reports (gitignored)

│ └── html-report/ # Newman HTML output

└── .github/workflows/ # CI/CD pipeline configuration

└── newman-tests.yml # GitHub Actions workflow file

text

## Getting Started

### Prerequisites
- **Node.js** (to install Newman via npm)
- **Postman** (optional, for GUI-based editing of collections)
