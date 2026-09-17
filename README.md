# QA Intern Practical Assignment

**Candidate Name:** Sunny Kumar
**Submission Date:** 17 September 2026

## Tools Used
- Manual Testing
- Java
- Selenium WebDriver
- TestNG
- Maven
- Microsoft Excel
- Google Chrome (DevTools for inspection)

## Browser / Environment
- Google Chrome [Chrome Version 128] on Windows
- Staging URL: http://base-application-stage.oomnieye.com/

## Documents Included
1. Application-Understanding.docx — application purpose, modules, workflows, assumptions
2. Test-Scenarios.xlsx — 15 test scenarios across all required categories
3. Test-Cases.xlsx — 10 detailed test cases
4. Bug-Report.xlsx — genuine defects found during testing (at least 2)
5. Test-Execution-Summary.docx — execution counts, defects, automation result, final QA assessment
6. Automation/ — basic Selenium + Java + TestNG automation project (Maven)
7. Final-Explanation.mp4 — 5-8 minute video walkthrough (linked below, not included in ZIP due to size)

## Assumptions and Limitations
- ["No test account was provided, so I created one via the signup flow" or "I assumed the primary user role since no role-based instructions were given."]
- [any feature you couldn't fully test within the time limit, and why]
- [any environment quirks you noticed, e.g. slow staging response times]

## Automation
Basic Selenium + TestNG automation was implemented for the login workflow (one positive
test, one negative test), following the Page Object Model. See `Automation/` for the
Maven project. Run with:
```
cd Automation
mvn test
```
