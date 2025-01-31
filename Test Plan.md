Test Plan 
Title: Expanse Tracker

Table of Contents

|Section |Page No.|
| :- | :- |
|1. Introduction||
|1.1 Purpose of the Test Plan ||
|2. Scope||
|2\.1 Feature to be Tested (Inclusions)||
|2\.2 Features Not to be Tested (Exclusions)||
|3. Approach||
|3\.1 Testing Type  ||
|3\.2 Testing Level||
|3\.3 Testing Strategy ||
|4. Test Deliverables||
|4\.1 Test Plan ||
|4\.2 Test Cases ||
|4\.3 Test Logs||
|4\.4 Bug Reports ||
|4\.5 Test Summary Reports||
|5. Test Schedule||
|5\.1 Test Start Date ||
|5\.2 Test End Date ||
|5\.3 Test Case Execution||
|5\.4 Summary Reports Submission||
|6. Resources||
|6\.1 Testing Team ||
|6\.2 Tools ||
|7. Test Environment||
|7\.1 Hardware Requirements||
|7\.2 Software Requirements||
|8. Test Case Design ||
|8\.1 Test Case Format ||
|8\.2 Traceability ||
|9. Entry and Exit Criteria ||
|9\.2 Suspension and Resumption Criteria||
|10. Risk and Mitigation||
|11. Approvals ||
|12. Sign of Test Case ||

1. **Introduction**

The **Expanse tracker web Application <https://expense-traker-six.vercel.app/>** is designed to provide users an intuitive interface to manage their **income expanse and investment.** Testing will ensure that the application meets the functional requirements and Non-functional requirements outlined in **Functional Requirements Specifications** guaranteeing a seamless user experience and reliable performance. This high-level test plan outlines the project's scope, test strategy, schedule, resource requirements, and deliverables.

**1.1 Purpose of the Test Plan**

The Purpose of this Test Plan is to ensure that the **Expanse Tracker Web Application** is meet the **user** and **business** requirements. Key goals include: 

1. **Verification of Functionality**: Validate all the features, including logging in to application, track expanses, see all categories and report generation in Dashboard, work as expected.
1. **User Experience insurance**: Ensure the application provides a user-friendly experience and clean user interface and user satisfaction.
1. **Bug identification and Resolution:** Detects bugs or inconsistencies and document it into Jira software and verify their resolution.
1. **Performance Validation:** Confirms application works seamlessly under all under expected workloads without delay or crashes.
1. **Security Evaluation:** Ensure that user credentials and their data is securely stored in the database.

1. **Scope**

The scope of this test plan encompasses all testing activities required to ensure the successful functionality, performance, usability, and security of the Expense Tracker Web Application. This application is designed to assist users in managing their financial transactions, providing insights into income, expenses, and savings.

**2.1** **Inclusions (Features to be tested)**

1. Registration.
1. Login.
1. Logout.
1. Update password.
1. Update username.
1. Update Email.
1. Add Transactions (Transactions Nav).
1. Add Category (Category Nav).
1. Delete Categories (Category Nav).
1. Graph update (Dashboard).
1. Search and Filter (Dashboard).
1. Cross Browser Compatibility.
1. Mobile responsiveness.
1. Home page.
1. Session Timeout.

**2.2 Exclusions (Features not to be tested)**

- Features mentioned in the inclusions
- Non-functional can be done by developers.

1. **Approach**

   **3.1 Types of Testing** 

1\. Functional Testing:

- Validation of core features like expanse tracking, category management and reports 
- Testing user authentication like registration, login and logout features.

2\. Usability Testing 

- Ensure the application is easy to navigate.
- Ensure interface is easy to use by the end users.

3\. Performance Testing 

- Ensure the application is load under 2-3 seconds 
- Ensure the application responsiveness under high workloads
- Identify any performance bottlenecks

4\. Compatibility Testing:

- Verify that web application runs on all browsers (Chrome, Safari, edge, Mozilla, and Firefox).
- Ensure that applications will be responsive and work on all devices.

5\. Security Testing

- Ensure that the credentials stored hashed.
- Ensure that unauthorized person cannot access the authorized account.

6\. Defect Management 

- Track and manage all reported defects in Jira for resolution and retesting 

**3.2 Testing Levels**

1. **Unit Testing**:
   1. To be conducted by developers to validate individual components or modules (not part of this test plan but will align with it).
1. **Integration Testing**:
   1. Validate interactions between different modules (e.g., login and dashboard).
1. **System Testing**:
   1. End-to-end testing of the entire application to ensure it meets the requirements.
1. **Acceptance Testing**:
   1. Validate the application against the business requirements to ensure it’s ready for deployment.

Here’s a structured approach to define the **Approach**, **Testing Types**, **Testing Levels**, and **Testing Strategy** for your test plan:

**1. Approach**

The testing approach will follow a structured methodology to ensure all features and functionalities of the **Expense Tracker Web Application** are validated. The approach includes:

- Understanding the functional and non-functional requirements of the application.
- Preparing test cases for each feature listed in the scope.
- Conducting testing in a phased manner, starting with functional testing, followed by usability, compatibility, and performance testing.
- Reporting and tracking defects in **Jira** for resolution.

**3.1 Testing Types**

The following testing types will be performed:

1. **Functional Testing**:
   1. Ensure all core functionalities (e.g., login, registration, adding transactions) work as expected.
1. **Usability Testing**:
   1. Evaluate the user interface and user experience to ensure the application is easy to use.
1. **Performance Testing**: Assess the application’s responsiveness and behaviour under different load conditions.
1. **Compatibility Testing**:
   1. Validate the application’s performance across multiple browsers and devices.
1. **Security Testing**:
   1. Identify and mitigate vulnerabilities like SQL injection, XSS, and unauthorized access.
1. **Regression Testing**:
   1. Re-test existing functionalities to ensure that changes or fixes have not introduced new issues.

**3.2 Testing Levels**

1. **Unit Testing**:
   1. To be conducted by developers to validate individual components or modules (not part of this test plan but will align with it).
1. **Integration Testing**:
   1. Validate interactions between different modules (e.g., login and dashboard).
1. **System Testing**:
   1. End-to-end testing of the entire application to ensure it meets the requirements.
1. **Acceptance Testing**:
   1. Validate the application against the business requirements to ensure it’s ready for deployment.

**3.3 Testing Strategy**

1. **Requirement Analysis**:
   1. Understand the functional and non-functional requirements.
   1. Identify test scenarios based on the features and workflows.
1. **Test Case Design**:
   1. Write detailed test cases in alignment with the scope and testing types.
1. **Test Execution**:
   1. Execute test cases in a prioritized order.
   1. Perform manual testing for features listed in the test plan.
1. **Defect Reporting and Tracking**:
   1. Log defects in **Jira** with detailed descriptions and steps to reproduce.
   1. Track defect resolution and re-test fixed issues.
1. **Test Closure**:
   1. Prepare a final test summary report documenting test coverage, defect trends, and unresolved issues.


**4. Test Deliverables**

The following are to be delivered to the client 

|**Deliverables**|**Description**|**Target Completion**|
| :-: | :-: | :-: |
|Test Plan|||
|Test Cases|||
|Test Logs|||
|Bug Reports|||
|Test Summary Reports|||


`	`**5. Test Schedule** 
**
`	`Following is the test schedule plan for the project

|Task|Time Duration|
| :-: | :-: |
|Test Creating Date||
|Test End Date||
|Test Case Execution ||
|Summary Report ||
.

**6. Resources**

**6.1 Testing Team**

|Category|Details|
| :- | :-: |
|Test Leads||
|` `QA||
|Devs||
|Project Managers||



**6.2 Testing Tools**

|**Category** |**Details**|
| :- | :-: |
|Test Management Tool||
|Documentation||
|Browser Testing ||
|Version Control ||
|Debugging Tools||
|Reporting||

**7. Test Environment** 

**7.1 Hardware Environment**

- This application does not require any specific hardware configuration this testing will be carried out on only standard devices and browsers.

**7.2 Software Environment**

- Windows 10 -11
- Browser (Chrome or Safari)
- Android Mobile OS (Chrome)
- iPhone Mobile OS (Safari)

**8. Test Case Design**

**8.1 Test case format**

- **Test Case ID**: A unique identifier for the test case.
- **Test Scenario**: A brief description of what the test will validate.
- **Test Description**: A more detailed explanation of the test case’s purpose.
- **Pre-Conditions**: Any necessary setup or conditions required before executing the test case.
- **Test Steps**: A step-by-step guide on how to execute the test.
- **Expected Result**: The expected behaviour of the system after executing the test steps.
- **Actual Result**: The result after the test case execution (filled in after the test).
- **Status**: The outcome of the test case (Pass/Fail).
- **Defects**: Any defects identified during testing, referenced by defect IDs.

**8.2 Traceability**

Test case traceability will be maintained to ensure all requirements are covered, and defects can be traced back to test cases. This is typically managed using Jira.

The Traceability matrix will be maintained as follows.

|Test case ID|Requirement ID|Scenarios |Test Status |
| :- | :- | :- | :- |
|||||
|||||


**9. Entry and Exit Criteria**

The below are the entry and exit criteria for every phase of Software Testing Life Cycle:

**Requirement Analysis**

**Entry Criteria:**

• Once the testing team receives the Requirements Documents or details about the

Project

**Exit Criteria:**

• List of Requirements are explored and understood by the Testing team

• Doubts are cleared

**Test Planning**

**Entry Criteria:**

• Testable Requirements derived from the given Requirements Documents or Project

details

• Doubts are cleared

**Exit Criteria:**

• Test Plan document (includes Test Strategy) is signed-off by the Client

**Test Designing**

**Entry Criteria:**

• Test Plan Document is signed-off by the Client

**Exit Criteria:**

• Test Scenarios and Test Cases Documents are signed-off by the Client

**Test Execution**

**Entry Criteria:**

• Test Scenarios and Test Cases Documents are signed-off by the Client

• Application is ready for Testing

**Exit Criteria:**

• Test Case Reports, Defect Reports are ready

**Test Closure**

**Entry Criteria:**

• Test Case Reports, Defect Reports are ready

**Exit Criteria:**

• Test Summary Reports

**9.2 Suspension and Resumption Criteria**

Based on the Client decision, we will suspend and resume the Project. We will ramp up and ramp down the resources as per Client needs.

**10. Risks and Mitigations**

The following are the list of risks possible and the ways to mitigate them:

• Risk: Non-Availability of a Resource

Mitigation: Backup Resource Planning

• Risk: Build URL is not working

Mitigation: Resources will work on other tasks

• Risk: Less time for Testing

Mitigation: Ramp up the resources based on the Client needs dynamically

**11.Approvals and Sign-off**

Team will send different types of documents for Client Approval like below:

• Test Plan

• Test Scenarios

• Test Cases

• Reports

Testing will only continue to the next steps once these approvals are done.
