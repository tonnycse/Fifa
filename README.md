**FIFA Homepage Testing with Playwright (TypeScript)**

This project uses Playwright with TypeScript to automate testing of the FIFA homepage. It is part of a personal portfolio to demonstrate testing skills.

**Prerequisites**
- Node.js (v14+)
- npm
  
**Installation**

**Clone the repo:**
git clone <repository-url> && cd fifa-homepage-playwright-tests

**Install dependencies:**
npm install
npx playwright install

**Running Tests**
npx playwright test

**Specific Test:**
npx playwright test tests/homepage.spec.ts

**Headed Mode:**
npx playwright test --headed

**Project Structure**
fifa-homepage-playwright-tests/
  ├── tests/                 # Test scripts (TypeScript files)
  ├── playwright.config.ts   # Playwright config
  ├── README.md              # Project documentation
  └── package.json           # NPM config

**Writing Tests**
Create new .spec.ts files in the tests directory:

import { test, expect } from '@playwright/test';

test('Verify FIFA homepage title', async ({ page }) => {
  await page.goto('https://www.fifa.com/en/home');
  await expect(page).toHaveTitle(/FIFA/);
});

**Reporting**
To view a detailed HTML report:
npx playwright show-report
