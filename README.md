# Eliana Mendez — QA Automation Engineer

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:your@email.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=flat&logo=github&logoColor=white)](https://github.com/ElianaMendez)

---

## About

I'm a QA Automation Engineer focused on building scalable, maintainable test automation frameworks for web applications and REST APIs. This portfolio documents a full specialization path — from writing structured BDD scenarios to implementing CI pipelines with Jenkins — applying industry-standard tools, design patterns, and best practices throughout.

---

## Skills & Technologies

**Test Automation**
`WebdriverIO` · `Playwright` · `Cucumber` · `TypeScript` · `JavaScript` · `Node.js`

**Assertion & API Testing**
`Chai` · `Axios` · `REST API Testing` · `Joi (schema validation)`

**Architecture & Design**
`Page Object Model` · `BDD / Gherkin` · `Layered Architecture (Core / Business / Tests)`

**Code Quality & CI/CD**
`ESLint` · `Prettier` · `Jenkins` · `GitHub Actions`

---

## Portfolio Overview

This portfolio is organized as a progressive specialization — each repository and branch builds on the previous one, reflecting how a real test automation framework evolves over time.

| # | Repository | Branch | What it demonstrates |
|---|------------|--------|----------------------|
| 1 | *(No repo)* | — | 8 Gherkin BDD scenarios covering sign-up, login, profile, cart, checkout, and more |
| 2 | [Specialization_AT_JS_Scenarios](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios) | `main` | WDIO setup, headless multi-browser execution (Chrome, Firefox, Safari), parallel runs, retry logic |
| 3 | [Specialization_AT_JS_Chai](https://github.com/ElianaMendez/Specialization_AT_JS_Chai) | `main` | Chai integration with Assert, Should, and Expect interfaces |
| 4 | [Specialization_AT_JS_Scenarios](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios/tree/feature/refactor) | `feature/refactor` | Page Object Pattern, DRY/KISS/YAGNI principles, Core / Business / Tests layered architecture |
| 5 | [Specialization_AT_JS_Testing_WebServices](https://github.com/ElianaMendez/Specialization_AT_JS_Testing_WebServices) | `main` | API test framework with Axios, full CRUD flows, response header/status/body/schema assertions |
| 6 | [Specialization_AT_JS_Results_Reporting](https://github.com/ElianaMendez/Specialization_AT_JS_Results_Reporting) | `main` | Spec (console) + HTML reporters with Playwright, report files excluded from Git index |
| 7 | [Specialization_AT_JS_Results_Reporting](https://github.com/ElianaMendez/Specialization_AT_JS_Results_Reporting/tree/feature/formatting) | `feature/formatting` | Prettier + ESLint with 4+ custom rules, linting scripts in package.json for UI and API |
| 8 | [Specialization_AT_JS_Scenarios](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios/tree/feature/typescript) | `feature/typescript` | Cucumber + TypeScript migration, feature file tags, CLI script, CI integration |
| 9 | [Specialization_AT_JS_Results_Reporting](https://github.com/ElianaMendez/Specialization_AT_JS_Results_Reporting/tree/feature/ci-jenkins) | `feature/ci-jenkins` | Jenkins pipelines for UI and API tests, scheduled execution every 2 hours, reporter plugin |

---

## Repository Highlights

### UI Automation Framework — three-stage evolution

The [`Specialization_AT_JS_Scenarios`](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios) repository tells the clearest story of growth across this portfolio:

**Stage 1 — `main`:** Initial WDIO framework wired directly to BDD scenarios. Tests run in headless Chrome, Firefox, and Safari with 2 parallel instances and automatic retry on failure.

**Stage 2 — `feature/refactor`:** Full architectural refactor using the Page Object Model. Code split into three distinct layers — Core (reusable utilities), Business (app-specific logic), and Tests (specs and config). All duplication eliminated following DRY, KISS, and YAGNI principles.

**Stage 3 — `feature/typescript`:** Migration to Cucumber + TypeScript. Feature files enriched with tags, enabling targeted test runs via CLI. Integrated into CI to run on every push.

---

### API Testing Framework

[`Specialization_AT_JS_Testing_WebServices`](https://github.com/ElianaMendez/Specialization_AT_JS_Testing_WebServices) is a standalone API framework built against the [Restful Booker API](https://restful-booker.herokuapp.com/apidoc/index.html).

Covers:
- GET requests with filter combinations
- Full CRUD flow: create → read → update → delete
- Basic auth headers on protected endpoints (PUT, DELETE)
- Assertions on response headers, status codes, response body, response time, and JSON schema (Joi)
- Dedicated npm script to run API tests independently via CLI

---

### CI & Reporting

[`Specialization_AT_JS_Results_Reporting`](https://github.com/ElianaMendez/Specialization_AT_JS_Results_Reporting) brings together the cross-cutting concerns of the framework — reporting, code quality, and CI — each isolated in its own branch.

- **`main`:** Playwright Spec reporter (console output) + HTML reporter; generated report folders excluded from Git via `.gitignore`
- **`feature/formatting`:** Prettier for consistent formatting, ESLint with 4 custom rules, scripts added to `package.json` for both UI and API projects
- **`feature/ci-jenkins`:** Two Jenkins pipelines cloning the repo and running UI and API tests independently, scheduled every 2 hours, with a reporter plugin displaying results in the Jenkins dashboard

---

## How to Navigate This Portfolio

If you're reviewing this for the first time, the recommended path is:

1. Start with [`Specialization_AT_JS_Scenarios / main`](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios) to see the baseline framework
2. Compare [`feature/refactor`](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios/tree/feature/refactor) to see how the architecture was improved
3. Check [`feature/typescript`](https://github.com/ElianaMendez/Specialization_AT_JS_Scenarios/tree/feature/typescript) to see the Cucumber + TypeScript migration
4. Review [`Specialization_AT_JS_Testing_WebServices`](https://github.com/ElianaMendez/Specialization_AT_JS_Testing_WebServices) for API test patterns
5. Browse [`Specialization_AT_JS_Results_Reporting`](https://github.com/ElianaMendez/Specialization_AT_JS_Results_Reporting) for reporting, linting, and CI setup

---

## Contact

I'm open to QA Automation Engineer roles and collaborations. Feel free to reach out:

- **LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)
- **Email:** [your@email.com](mailto:your@email.com)
- **GitHub:** [github.com/ElianaMendez](https://github.com/ElianaMendez)
