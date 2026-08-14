# SauceDemo E-Commerce Website - Manual QA Testing

## Project Overview

This project demonstrates manual software testing of the SauceDemo E-Commerce Website. The objective was to test the main functionalities of the website, identify defects, execute test cases, and document the testing results.

Jira was also used for defect tracking and Scrum-based project management.

## Project Objectives

- Create a structured Test Plan
- Design and execute manual test cases
- Identify and document software defects
- Perform functional and UI testing
- Track defects using Jira
- Prepare a Test Execution Report
- Practice Scrum workflow in Jira
- Document the complete manual QA testing process

## Scope of Testing

The following modules and functionalities were tested:

- Login
- Sign Up
- Product Catalog
- Product Details
- Search
- Shopping Cart
- Checkout
- Wish List
- Logout
- Navigation

## Testing Process

The project followed these manual QA activities:

1. Test Planning
2. Test Scenario Creation
3. Test Case Design
4. Test Case Execution
5. Defect Identification
6. Bug Reporting
7. Bug Tracking in Jira
8. Test Execution Reporting
9. Scrum Sprint Management

## Test Cases

A total of **100 test cases** were created and executed for the website.

The test cases covered the major functional areas of the application, including Login, Sign Up, Catalog, Product Details, Shopping Cart, Checkout, Wish List, Logout, and Navigation.

## Test Execution Results

| Result | Count |
|---|---:|
| Total Test Cases | 100 |
| Passed | 75 |
| Failed | 13 |
| Not Executed | 12 |
| Pass Rate | 75% |
| Fail Rate | 13% |

## Bug Report

A total of **8 bugs** were identified and documented during testing.

### Major Defects Identified

1. Product sorting option is missing from the Catalog page
2. Search field is not available on the Catalog page
3. Wish List page does not open when clicked
4. Add to Wish List option is missing from the Product Details page
5. Decrease quantity button is missing from the Shopping Cart
6. Empty Wish List page is not displayed when no products are added
7. User is redirected to the Home page instead of the Login page after logout
8. Wish List navigation link is not functional

All identified defects were documented in the Bug Report and tracked in Jira.

## Jira Defect Tracking

Jira was used for defect tracking and Scrum project management.

The Jira project includes:

- Scrum project
- Product backlog
- 8 Bug issues
- Bug assignment
- Sprint planning
- Active Scrum board
- Bug status tracking
- Defect workflow

### Jira Bugs

| Bug ID | Bug Summary | Status |
|---|---|---|
| MQP-1 | Product sorting option is missing from Catalog page | In Progress |
| MQP-2 | Search field is not available on Catalog page | To Do |
| MQP-3 | Wish List page does not open when clicked | To Do |
| MQP-4 | Add to Wish List option is missing from Product Details page | To Do |
| MQP-5 | Decrease quantity button is missing in Shopping Cart | To Do |
| MQP-6 | Empty Wish List page is not displayed | To Do |
| MQP-7 | User is redirected to Home page instead of Login page after logout | To Do |
| MQP-8 | Wish List navigation link is not functional | To Do |

### Jira Workflow

`To Do → In Progress → In Review → Done`

The identified bugs were added to the Jira backlog, assigned, included in a sprint, and tracked using the Scrum board.

## Jira Evidence

Screenshots demonstrating the Jira testing workflow are included in the repository:

- Jira Backlog showing the 8 identified bugs
- Jira Sprint Board showing bug status
- Jira MQP-1 bug details showing the defect documentation and In Progress status

## Tools Used

- **Microsoft Excel** - Test Cases, Bug Report, and Test Execution Report
- **Microsoft Word** - Test Plan
- **Jira** - Bug Tracking and Scrum Project Management
- **Google Chrome** - Test Execution
- **SauceDemo** - Application Under Test
- **GitHub** - Project Documentation and Version Control

## Project Deliverables

| File | Description |
|---|---|
| `Test Plan SauceDemo Website.docx` | Test planning document |
| `Test Cases SauceDemo.xlsx` | 100 manual test cases |
| `Bug Report SauceDemo.xlsx` | Documented defects |
| `Test Execution Summary SauceDemo.xlsx` | Test execution results |
| `SauceDemo Jira Bugs Report.xlsx` | Jira bug tracking documentation |
| `README.md` | Project documentation |

## Repository Structure

```text
SauceDemo-Manual-QA/
│
├── Test Plan SauceDemo Website.docx
├── Test Cases SauceDemo.xlsx
├── Bug Report SauceDemo.xlsx
├── Test Execution Summary SauceDemo.xlsx
├── SauceDemo Jira Bugs Report.xlsx
├── Jira Screenshots/
│   ├── Jira Backlog - 8 Bugs.png
│   ├── Jira Sprint Board.png
│   └── Jira Bug MQP-1.png
│
└── README.md
