# TechQuiz

This is a full-stack application that runs test cases when a Pull Request is made to the develop branch and automatically deploys to Render when the code is merged to main.

## Table of Contents

1. [Features](#features)
2. [Tech Stack](#tech-stack)
3. [Installation](#installation)
4. [Cypress Testing](#cypress-testing)
5. [Development Workflow](#development-workflow)
6. [GitHub](#github)

## Features

- Add and seed questions into a MongoDB database

- Frontend displays quiz questions and options

- Tracks correct answers

- Responsive design

## Tech Stack

- Frontend: React, TypeScript

- Backend: Node.js, Express, TypeScript

- Database: MongoDB Atlas

- CI/CD: GitHub Actions

- Testing: Cypress Component Testing

## Installation

- git clone https://github.com/TiffanyMClark/FullStack

- cd your-repo

- npm install

- npm run build

- npm start

- npm run seed

## Cypress Testing

Tests are run automatically when you push to develop. If all tests pass, you may merge to main.

## Development Workflow

1. Create feature branches off develop

2. Submit PRs to develop

3. Cypress tests run via GitHub Actions

4. After successful tests, merge to main

5. GitHub Action triggers auto-deployment to Render

## GitHub

https://github.com/TiffanyMClark/FullStack

https://fullstack1-gc8f.onrender.com/
