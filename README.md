Bootcamp Task: Automated UI Testing, CI/CD Pipeline and Database Integration

Objective: The goal of this hackathon is to create an end-to-end automated testing solution that includes UI test automation and seamless integration into a CI/CD pipeline. Participants will write test cases to validate the functionality of the Insider website QA application, and the tests will be executed as part of a CI/CD pipeline.



Automated UI Testing

Visit https://useinsider.com/ and check Insider home page is opened or not
Select “Company” menu in navigation bar, select “Careers” and check Career page, its Locations, Teams and Life at Insider blocks are opened or not
Go to https://useinsider.com/careers/quality-assurance/, click “See all QA jobs”, filter jobs by Location -  Istanbul, Turkey and department - Quality Assurance, check presence of jobs list
Check that all jobs’ Position contains “Quality Assurance”, Department contains “Quality Assurance”, Location contains  “Istanbul, Turkey”
Click “View Role” button and check that this action redirects us to Lever Application form page


Test Case Requirements:

Write test cases using any programming language and framework (Python or Java + Selenium is preferable)
Do not use BDD (Cucumber, Quantum, Codeception, etc.) frameworks
Buttons, dropdowns and other elements should have optimized Xpath and CSS selectors
Assertions should be used in test case
Code should be clean and readable
Take a screenshot if a test step fails
Ensure test cases can run in both Chrome and Firefox browsers and allow for parameterized browser selection
Implement the Page Object Model (POM) design pattern for test code organization


CI/CD Pipeline Integration

Create a CI/CD pipeline that automates the execution of the UI test cases.
The pipeline should trigger the tests whenever a new pull-request is created or changes are pushed to pull-request.
Any CI/CD tool can be used (e.g., Jenkins, GitLab CI/CD, Travis CI, CircleCI).
After each test run, the pipeline should generate and store test reports and screenshots. Also it should send test results as required checks to pull requests.



Test Results visualization 

After the UI test cases have been executed, add a step in your CI/CD pipeline to write the test results (including pass/fail status, durations, etc.) to a database. You can use a database of your choice, such as MySQL, PostgreSQL, or a NoSQL database like MongoDB.
Set up an integration between your database and Grafana
Create Grafana Dashboards to display metrics such as test pass rates, execution times
