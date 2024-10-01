**FIFA Homepage Testing with Playwright (TypeScript)**

This project uses Playwright with TypeScript to automate testing of the FIFA homepage. It is part of a personal portfolio to demonstrate testing skills.

**Prerequisites**

- Node.js (v14+)
- npm
  
**Installation**

**1. Clone the repo:**

git clone https://github.com/tonnycse/Fifa && cd Fifa

**2. Install dependencies:**

- npm install
- npx playwright install

**Running Tests**

**1. All Tests:**

npx playwright test

**2. Specific Test:**

npx playwright test tests/homepage.spec.ts

**3. Headed Mode:**

npx playwright test --headed

**Project Structure**

fifa-homepage-playwright-tests/

├── tests/                 # Test scripts (TypeScript files)

├── playwright.config.ts   # Playwright config

├── README.md              # Project documentation

└── package.json           # NPM config

**Running Tests**

To run the tests:

npx playwright test

**Reporting**

To view a detailed HTML report:

npx playwright show-report
