# BBC_Cypress_testing

This project uses Cypress to automate tests for BBC.com, making sure the website's main features are safe, reliable, and work well.

## Test Scenarios
1. **Homepage Navigation**
2. **Homepage Rendering**
3. **Article Viewing**
4. **Responsive Design**
5. **Video Playback**
6. **Language Selection**
7. **Search Functionality**
8. **Newsletter Subscription**
9. **Cyber security**

A Word document in the project files contains detailed descriptions of each test scenario, including all the steps needed to achieve the desired outcomes. These steps were originally written for manual testing and later automated with Cypress.

## Before you start
Make sure you install:
- Node.js (version 10 or higher)
- Cypress
- Npm

## Setup
1. **Clone the Repository**
    ```bash
    git clone https://github.com/RytisMiciunas/BBC_Cypress_testing.git
    ```
2. **Navigate to the Project Directory**
    ```bash
    cd your-repository/BBC_Cypress_testing
    ```
3. **Install Project Dependencies**
    ```bash
    npm install
    ```

## Running Tests
### Open Cypress app manually
```bash
npx cypress open
```
### Run all test headless mode
```bash
npx cypress run
```
### To run specific test 
```bash
npx cypress run --browser <write in which browser you want test to run > --spec 'cypress/e2e/(folder in which test is located)/(test name).js'
```

