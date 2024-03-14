# Insider QA Automation Bootcamp

## Table of Contents
- [Overview](#overview)
- [Automated UI Testing](#automated-ui-testing)
- [CI/CD Pipeline Integration](#cicd-pipeline-integration)
- [Test Results Visualization](#test-results-visualization)

## Overview
The purpose of this bootcamp is to implement an end-to-end automated testing solution that encompasses UI test automation and its integration into a Continuous Integration and Continuous Deployment (CI/CD) pipeline.

## Automated UI Testing
### Task Instructions:
- Navigate to [Insider's Homepage](https://useinsider.com) to verify its accessibility.
- From the navigation bar, select "Company", then "Careers" and verify if the Career page, including its Locations, Teams, and Life at Insider sections, are accessible.
- Visit the [Quality Assurance Careers Page](https://useinsider.com/careers/quality-assurance/), click "See all QA jobs", filter the jobs by location (Istanbul, Turkey) and department (Quality Assurance), and check for the job listings' presence.
- Ensure each job position lists "Quality Assurance" in both the Position and Department fields and "Istanbul, Turkey" in the Location field.
- Verify that clicking the "View Role" button redirects to the Lever Application form page.

### Test Case Requirements:
- Utilize any programming language and framework (Python with Selenium is recommended) for writing test cases.
- Avoid Behavior-Driven Development (BDD) frameworks such as Cucumber, Quantum, or Codeception.
- Optimize Xpath and CSS selectors for buttons, dropdowns, and other UI elements.
- Implement assertions within test cases.
- Maintain clean and readable code.
- Capture screenshots upon test failure.
- Ensure compatibility of test cases with Chrome and Firefox browsers, incorporating parameterized browser selection.
- Adopt the Page Object Model (POM) design pattern for test code organization.

## CI/CD Pipeline Integration
### Tasks:
- Establish a CI/CD pipeline that automates the execution of the UI test cases.
- Configure the pipeline to initiate tests for new pull requests or when changes are pushed to an existing pull request.
- Use any CI/CD tools such as Jenkins, GitLab CI/CD, Travis CI, or CircleCI.
- Generate and store test reports and screenshots after each test run.
- Integrate test results as required checks for pull requests.

## Test Results Visualization
### Tasks:
- After executing the UI test cases, incorporate a step in your CI/CD pipeline to log test results (including pass/fail status, durations, etc.) into a chosen database (MySQL, PostgreSQL, MongoDB).
- Set up Grafana and integrate it with your database to visualize testing metrics.
- Develop Grafana Dashboards that exhibit test metrics such as pass rates and execution times.
