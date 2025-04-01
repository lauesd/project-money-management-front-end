# ProjectMoneyManagementFrontEnd

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.1.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

To install the dependencies of this project, run:

```bash
npm install
```

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

# project-money-management-front-end
This is the front-end of this project.

# User stories

## 1. As a user, I want to view my total personal budget.

**Acceptance Criteria**:
- The personal budget  must have the following attributes:
  - **Amount**: The monetary value amount for the budget (e.g., "$3,000").

**Security**:
- The software must use strong encryption (e.g., AES-256) to protect all financial data, including income records.
- User data must be securely stored and transmitted to prevent unauthorized access.
- The software must be protected against common security vulnerabilities such as SQL Injection, XSS, CSRF, and DDoS attacks.

**non-functional requirement**
- The software must be responsive and accesible

## 2. As a user, I want to add my income sources to my personal budget.

**Acceptance Criteria**:
- I can input multiple income sources (e.g., salary, freelance, investments, side business).
- Each income source must have the following attributes:
  - **Name**: A description or title of the income source (e.g., "Salary," "Freelance Work").
  - **Amount**: The monetary value or expected amount for each income source (e.g., "$3,000").
- I can edit or delete any income source if necessary.
- The software must automatically update my total budget when a new income source is added or modified.
- The software provides an overview or summary of my total income.

**Security**:
- The software must use strong encryption (e.g., AES-256) to protect all financial data, including income records.
- User data must be securely stored and transmitted to prevent unauthorized access.
- The software must be protected against common security vulnerabilities such as SQL Injection, XSS, CSRF, and DDoS attacks.

**non-functional requirement**
- The software must be responsive and accesible

---

## 3. As a user, I want to add my spending entries to my personal budget.

**Acceptance Criteria**:
- I can input and view all of my spending entries.
- Each spending entry must have the following attributes: 
  - **Name**: A description or title of the spending (e.g., "Groceries," "Coffee").
  - **Amount**: The monetary value of the spending (e.g., "$45.00").
- I can edit or delete any spending entry if needed.
- The software must automatically update my total budget whenever a new income source is added or modified.
- The software provides an overview or summary of my total income and the remaining budget after income is added.

**Security**:
- The software must use strong encryption (e.g., AES-256) to protect all financial data, including spending records.
- User data must be securely stored and not exposed without proper authorization.
- The software must be protected against common security vulnerabilities such as SQL Injection, XSS, CSRF, and DDoS attacks.

**non-functional requirement**
- The software must be responsive and accesible

---

## 4. As a user, I want to view statistics about the total income and spending, along with a comparison.

**Acceptance Criteria**:
- The software must display the total income and total spending.
- The software must show a comparison between total income and total spending (e.g., a bar chart or percentage comparison).

**Security**:
- The software must use strong encryption (e.g., AES-256) to protect all financial data, including income and spending records.
- User data must be securely stored and transmitted to prevent unauthorized access.
- The software must be protected against common security vulnerabilities such as SQL Injection, XSS, CSRF, and DDoS attacks.

**Non-functional Requirement**:
- The software must be responsive and accessible across various devices and platforms.

---

## 5. As a user, I want to register and log in to the software, and I want all my data to be deleted after 2 hours of registration.

**Acceptance Criteria**:
- I can register for an account by providing my personal details (e.g., email, password).
- I can log in using my registered credentials (e.g., email and password).
- A budget is automatically created when the user account is registered.
- All user data, including personal and financial information, is automatically deleted 2 hours after registration.
- The software ensures that after the 2-hour window, all data associated with the account is fully deleted and cannot be recovered.

**Security**:
- The software must use strong encryption (e.g., AES-256) for storing and transmitting sensitive user data, including personal and financial details.
- User data must be securely stored and transmitted to prevent unauthorized access.
- User passwords must be hashed with a salt to ensure secure storage.
- The software must be protected against common security vulnerabilities such as SQL Injection, XSS, CSRF, and DDoS attacks.

**Non-functional Requirement**:
- The software must be responsive and accessible across various devices and platforms.

---
