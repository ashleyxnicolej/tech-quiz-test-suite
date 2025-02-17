# Tech Quiz Test Suite

This repository contains the Tech Quiz Test Suite, a project designed to test a quiz application using Cypress for end-to-end and component testing.

## Project Structure
├── component/ // Folder for component tests │ └── questions.json // Mock data for testing ├── server/ // The server application ├── .gitignore ├── cypress.config.ts // Runs the application using imports from lib/ ├── package.json ├── tsconfig.json └── README.md // App description, link to video, setup and usage instructions

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ashleyxnicolej/tech-quiz-test-suite.git
   cd tech-quiz-test-suite

2. Install Dependencies
    ```
    npm install

   
3. Rename Environment File Rename the .env.example file to .env and configure the necessary environment variables.
    ```
    mv .env.example .env
   
4. Install Cypress
    ```
    npm install cypress --save-dev

5. Run Tests
    ```
    npm run test


## Walkthrough Video
Link to Walkthrough Video coming soon

## License
This project is licensed under the MIT License.


