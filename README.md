[![Playwright.dev](https://img.shields.io/badge/Documentation-Playwright-45ba4b.svg?logo=playwright)](https://playwright.dev/docs/intro)
[![Cucumber](https://img.shields.io/badge/Documantation-Cucumber-23d96c.svg?logo=cucumber)](https://cucumber.io/)

<br>

# Playwright with Typescript - Cucumber - BDD

This is my personal project to improve my skills in automated testing using Cucumber and BDD.
This project was created solely for my learning process and to showcase my testing skills.

## Installation

- <kbd>CTRL</kbd> + <kbd>SHIFT</kbd> + <kbd>P</kbd> => Install Playwright => OK
- Install Cucumber plugin
- Install dependencies: 
  - `npm i @cucumber/cucumber -D`
  - `npm i ts-node -D`
- Create folder `src/test/features` and `src/test/steps`

- Make Sure @playwright/test is Installed
- `npm install -D @playwright/test`

- Restart TypeScript Server (in VS Code)
 - `Open Command Palette (Ctrl + Shift + P)`
   
- TypeScript: Restart TS server

- Install ESLint `npm install eslint --save-dev`
- Configuration `npm init @eslint/config`
- Add prettier in `.eslintrc.json` :
```json
"extends": [
    "eslint:recommended",
    "plugin:@typescript-eslint/recommended",
    "prettier"
],
```
- Install Prettier `npm install --save-dev --save-exact prettier`
- Add file `.prettierignore` :
```
package-lock.json
README.md
```
- Add Prettier rule `.prettierrc.json` :
```json
{
    "singleQuote": true
}
```
- Run formatting with Prettier `npx prettier --write .`
- Linking Prettier with ESLint `npm install --save-dev eslint-config-prettier`


- How to Run Cucumber Tests`
npx cucumber-js`

- Run Tests by Tag from Command Line
- `npx cucumber-js --tags "@smoke"`


- Run the tests + generate report:
- `npx cucumber-js --format json:reports/report.json`
- `node generate-report.js`
