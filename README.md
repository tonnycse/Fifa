**FIFA Homepage Testing with Playwright (TypeScript)**

This project uses Playwright with TypeScript to automate testing of the FIFA homepage, including testing the title, logo, and navigation bar. 

**Prerequisites**

- Node.js 
- npm
- VS Code
  
**Installation**

**1. Clone the repo:**

git clone https://github.com/tonnycse/Fifa 

**2. Install dependencies:**

- npm install
- npm init playwright@latest

**Project Structure**

fifa-homepage-playwright-tests/

├── tests/                 # Test scripts (TypeScript files)

├── playwright.config.ts   # Playwright config

├── README.md              # Project documentation

└── package.json           # NPM config

**Running Tests**

**1. All Tests:**

npx playwright test

**2. Specific Test:**

npx playwright test tests/homepage.spec.ts

**3. Headed Mode:**

npx playwright test --headed

**4. UI Mode:**

npx playwright test --ui

**5. Run Test on Different Browsers:**

npx playwright test --project webkit [Used Webkit As Example]

**Reporting**

To view a detailed HTML report:

npx playwright show-report
