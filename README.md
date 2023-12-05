# Cypress - Test Automation University

We are creating a Cypress Project by learning from Test Automation University. There is a lot to explore and learn. This  will also contains the requirement and how to get started with the project in a linux system.

## 1. Checking the node.js
First of all we need to check if node.js is installed in our system or not. For that we will write

` node -v `

If node.js is not installe then install it by 

`sudo apt install nodejs `

Then continue and install npm as well:

` sudo apt install npm `

After that we will run these commands:

`  npm init -y `

` npm install cypress `

## 2. Opening a cypress Test 

Cypress has a nice UI that opens up for the automation for that run this in bash terminal:

`npx cypress open`

## 3: Configuration of Cypress Project

We can add multiple configuration in Cypress.config file. My default setting is given below :

~~~
const { defineConfig } = require("cypress");

module.exports = defineConfig({
  pageLoadTimeout: 60000,
  retries: 2,
  screenshotOnFail: true,
  screenshotsFolder: 'cypress/screenshots',
  projectId: 'fqqcti',
  e2e: {
    setupNodeEvents(on, config) {
      // implement node event listeners here
    },
  },
});

~~~

## 4: How to get Elements?

This is a drive linnk that contains the data.

=> https://www.mediafire.com/view/mpotwdc3d5h50ul/Screenshot_from_2023-12-04_19-14-52.png/file
