# cypress.io Exploration
The goal of this project is to learn a bit about cypress io, and how to set a project from scratch using it

## Setup
If you are working on a real project that you would like to test, it would be a great idea to have cypress.io installed as part of that project, and the tests colocated with the source code.
To do so:
1. Navigate to the project repository
2. Run `npm install cypress`

If you are trying cypress for the sake of learning, do the following:
1. Create a new directory (e.g. cypress-exploration)
2. Navigate to that directory: `cd cypress-exploration`
3. Create a new Node.js module using: `npm init`, and follow the steps/questions that appear in the terminal
4. Run `npm install cypress`

## Start Cypress.io
To start cypress run the following command: `npx cypress open` or `./node_modules/.bin/cypress open`. This is the default command. To make it easier:
1. Add it as a script in package.js: `"cypress:open": "cypress open"`
2. To start Cypress.io run: `npm run cypress:open`

## Run Cypress.io tests
To run tests directly from command line: `npx cypress run` or `./node_modules/.bin/cypress run`. To make it easier:
1. Add it as a script in package.js: `"cy:run": "cypress run"`
2. To run the test: `npm run cy:run`

To run with a parameter add --. For example:
`npm run cy:run -- --headed` to run in a headed mode instead of the default headless mode.
