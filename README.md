# Postman-newman-automated.tests

This repository contains a simple Todo API built using Node.js and Express. The API supports basic CRUD (Create, Read, Update, Delete) operations for managing a list of todos. The application is designed for easy understanding and can be used as a starter project or for educational purposes.

## Prerequisites

Before you begin, ensure you have met the following requirements:
- You have Node.js and npm installed on your local machine. You can download and install Node.js from [nodejs.org](https://nodejs.org/).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/postman-newman-automated.tests.git
   cd postman-newman-automated.tests

2. Install the dependencies:
   ```bash
   npm install

3. To start the Node.js application, run the following command in bash:
npm start

The server will start running on http://localhost:3000.

## Running tests

1. To run the tests locally, execute: 
   ```bash
   npm test

2. Running tests in GitHub Actions:
This repository is configured to use GitHub Actions for continuous integration. The workflow file is located at .github/workflows/main.yml and is triggered on every push to the main branch. It performs the following steps:

Checks out the repository.
Installs Node.js and project dependencies.
Starts the Node.js application.
Runs the Postman collection using Newman.
Generates an HTML report of the test results and uploads it as an artifact.

If you have any suggestions or improvements, feel free to fork the repository and create a pull request.

Contact:
kpetrauskaite57@gmail.com

Project Link: https://github.com/kpetrauskaite57/Postman-newman-automated.tests