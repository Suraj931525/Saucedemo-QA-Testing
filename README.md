# SauceDemo | Manual & Automation Testing

![Testing](https://img.shields.io/badge/Testing-Manual%20%7C%20Automation-blue)
![Java](https://img.shields.io/badge/Java-17-orange)
![Selenium](https://img.shields.io/badge/Selenium-4.27.0-green)
![TestNG](https://img.shields.io/badge/TestNG-7.10.2-red)
![Maven](https://img.shields.io/badge/Build-Maven-purple)

## Project Overview

This repository contains a structured Quality Assurance (QA) testing project for the **Swag Labs (SauceDemo)** e-commerce application.

The project demonstrates a practical approach to software testing through manual test design, defect identification, test documentation, and UI automation using Selenium WebDriver, Java, TestNG, and Maven.

The objective is to evaluate core application workflows, validate expected behavior, identify potential defects, and improve test coverage through a combination of manual and automated testing.

**Application Under Test:** https://www.saucedemo.com/

---

## Project Objectives

- Understand and validate key e-commerce application workflows.
- Design and execute functional and negative test cases.
- Verify login, product catalogue, cart, and checkout functionality.
- Identify, document, and track application defects.
- Automate selected test scenarios using Selenium WebDriver.
- Maintain clear and organized QA documentation.

## Scope of Testing

The following application modules are included:

| Module | Testing Coverage |
|---|---|
| Login | Valid, invalid, and locked-out user scenarios |
| Product Catalogue | Product visibility and details |
| Product Sorting | Sorting functionality |
| Shopping Cart | Add, remove, and cart validation |
| Checkout | Form validation and required fields |
| Order Summary | Item prices, subtotal, tax, and total |
| Order Completion | Order confirmation and navigation |

## Testing Approach

### Manual Testing

- Functional Testing
- Positive Testing
- Negative Testing
- UI Testing
- Exploratory Testing
- Defect Reporting

### Automation Testing

Selected test scenarios are automated using:

- Selenium WebDriver
- Java
- TestNG
- Maven

Automation focuses on validating important user workflows and expected application behavior.

## Technology Stack

| Technology | Version / Purpose |
|---|---|
| Java | 17 |
| Selenium WebDriver | 4.27.0 |
| TestNG | 7.10.2 |
| Maven | Project build and dependency management |
| Google Chrome | Test execution browser |
| IntelliJ IDEA / Eclipse | Development environment |
| Git & GitHub | Version control and project hosting |

## Test Environment

- **Application:** Swag Labs (SauceDemo)
- **Browser:** Google Chrome
- **Automation Language:** Java
- **Automation Framework:** Selenium WebDriver with TestNG
- **Build Tool:** Maven
- **Operating System:** Update with your actual test environment

## Test Data

SauceDemo provides public demo accounts for testing different login scenarios.

| Username | Password | Purpose |
|---|---|---|
| standard_user | secret_sauce | Standard user workflow |
| locked_out_user | secret_sauce | Locked-out user validation |
| problem_user | secret_sauce | Application behavior testing |
| performance_glitch_user | secret_sauce | Performance-related behavior |
| error_user | secret_sauce | Error behavior testing |
| visual_user | secret_sauce | Visual behavior testing |

## Repository Structure

```text
saucedemo-qa-testing/
│
├── README.md
│
├── test-plan/
│   └── SauceDemo_Test_Plan.pdf
│
├── manual-testing/
│   ├── Manual_Test_Cases.xlsx
│   └── Bug_Report.xlsx
│
└── automation/
    ├── pom.xml
    └── src/
        └── test/
            └── java/
                └── SauceDemoAutomation/
                    └── Test/
                        ├── CheckoutTest.java
                        ├── LockedUserTest.java
                        └── LoginDataProviderTest.java
```

## Automation Framework Setup

### Prerequisites

Ensure the following are installed:

- Java JDK 17
- Apache Maven
- Google Chrome
- IntelliJ IDEA or Eclipse

### Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/saucedemo-qa-testing.git
```

Replace `YOUR-USERNAME` with your GitHub username.

### Import the Project

1. Open the project in IntelliJ IDEA or Eclipse.
2. Import it as a Maven project.
3. Allow Maven to download the required dependencies.
4. Verify the Java and Maven configurations.

### Execute Automation Tests

Navigate to the automation project directory and run:

```bash
mvn clean test
```

The command executes the tests configured in the Maven/TestNG project.

## Test Documentation

The repository contains the following QA deliverables:

| Deliverable | Description |
|---|---|
| Test Plan | Defines testing objectives, scope, approach, and environment |
| Manual Test Cases | Documents test scenarios, steps, and expected results |
| Bug Reports | Records reproducible defects and supporting details |
| Automation Scripts | Contains Selenium-based automated test cases |

## Defect Reporting

Identified defects are documented with the following information:

- Bug ID
- Bug Title
- Module
- Environment
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity and Priority
- Status

Only verified and reproducible defects should be included in the final defect report.

## Project Outcomes

This project provides practical experience in:

- Software Testing Life Cycle (STLC)
- Test Case Design and Execution
- Defect Life Cycle
- Functional and Negative Testing
- Selenium WebDriver Automation
- Java and TestNG
- Maven Project Management
- QA Documentation and Reporting

## Author
Suraj patil

**QA Tester | Manual & Automation Testing**


