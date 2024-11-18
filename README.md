
# GitHub Actions CI/CD

- Deployed app: [Quizz App](https://github-actions-ci-cd-3rd7.onrender.com)


![Static Badge](https://img.shields.io/badge/license-MIT-blue?style=flat)

## Table of Contents
- [CI/CD with GitHub Actions](#ci/cd-with-github-actions)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [How to Contribute](#how-to-contribute)
- [Questions](#questions)
- [Authors and Acknowledgment](#authors-and-acknowledgment)
- [License](#license)

## CI/CD with GitHub Actions
This project utilizes GitHub Actions to implement a CI/CD workflow with the following features:

1. **Branching Strategy**: The repository has a `main` branch, a `develop` branch, and uses `feature` branches for development.
2. **Pull Request Workflow**: When a Pull Request is submitted to the `develop` branch, a GitHub Action is triggered to execute Cypress component tests.
3. **Automatic Deployment**: When a Pull Request is submitted and merged to the `main` branch, a GitHub Action is triggered to automatically deploy the application to Render.

All Cypress component tests must pass before the application is deployed to production.

## Installation
1. Clone the repository
2. Run `npm install` to install required packages
3. Ensure MongoDB is installed and running on your system
4. Configure your MongoDB connection in the project

## Usage
1. Run `npm start` to start the server
2. Use an API testing tool like Insomnia or Postman to interact with the endpoints

## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose ODM
- Cypress
- GitHub Actions
- Render
- JavaScript
- Git

## How to Contribute
To contribute:
1. Fork the repository
2. Create a new feature branch
3. Make your changes
4. Ensure Cypress component tests pass
5. Submit a pull request to the `develop` branch

## Questions
You can reach me for questions at:
- GitHub Profile: [marioxabel](https://github.com/marioxabel)

## Authors and Acknowledgment
- Author: [Mario](https://github.com/marioxabel)
- This was a challenge for the [Tecnológico de Monterrey Coding Boot Camp](https://bootcamp.tec.mx/coding/)

## License
Distributed under the MIT License. [Click to see the full MIT license](https://choosealicense.com/licenses/MIT/).