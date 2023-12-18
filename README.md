# Aeries_Project #
| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 14.07.2023 | Test Plan for version 1.0 | Madalina Bogdan|   |

1. Introduction

    1.1 Project objective
   
    1.2 Functionalities in scope

    1.3 Functionalities and tests out of scope

2. Test process

    2.1 Test planning
   
    2.2 Test analysis

    2.3 Test design

    2.4 Test implementation
   
    2.5 Test execution 

    2.6 Test closure

    2.7 Test monitoring and control
   
3. Test deliverables

    3.1 Test plan
   
    3.2 Test conditions

    3.3 Test cases

    3.4 Daily test summary reports
   
    3.5 Traceability matrix

    3.6 Test case results

    3.7 Bugs report

    3.8 Test completion report

## 1. Introduction ##

The Aeries project aims to provide an information system for students and parents where they can log into to check grades, update contact information, and see any other information the school provides.
This release will have limited features. Over a period of time, new and new functionalities of the software product will be added.

### 1.1	Project Objective ###

We need to find and prevent defects and raise the trust in the quality of the project as high as possible before releasing it to customers.
- Application under test: [Aeries Parent Portal](https://demo.aeries.net/ParentPortal/LoginParent.aspx?demo=True&user=student%40aeries.com&pwd=1234)
- Application documentation: 
[suporting documentation](https://support.aeries.com/support/home) - [API documentation](https://support.aeries.com/support/solutions/articles/14000077926-aeries-api-full-documentation)

### 1.2 Functionalities in scope ###

- the following functionalities are going to be tested: 
Login Module, Settings Module: Change Password, Change E-mail, Configure Grade Alerts, Add New Student To Your Account, Log Out
-	the features in scope for testing: Login Module, Settings Module: Change Password, Change E-mail
-	testing types used: Functional testing like Smoke Testing, GUI Functional Testing
-	test level: System Testing 

### 1.3	 Functionalities and tests out of scope ###

-	the features out of scope: Settings Module: Configure Grade Alerts, Add New Student To Your Account, Log Out
-	non-functional testing like stress, load, performance is beyond scope of this project
-	no QA support for mobile applications developed, only web applications will be tested
-	automation testing is beyond scope.

## 2.	Test process ##
 	
### 2.1	 Test planning ### 

Roles and responsibilities

| Tester  | Madalina Bogdan  | Will test:  Login Module, Change Password, Change Email | Comments | 
|---|---|---|---|

Entry criteria:

-	functional business specifications are defined
-	test plan document is defined 
-	roles needed for the project are allocated


Exit criteria:

-	all test cases have been executed 
-	90% of tests are passed
-	no critical issues/bugs have open status (All unresolved bugs have low priority and low severity)
-	exploratory testing performed on the features: Login Module, Settings Module: Change Password, Change E-mail
-	update tests are 100% passed (update tests will not generate other new issues that impact the application)
-	complete functional coverage
-	regression tests are passed
  
Risks:
Project Risks: 
-	the complexity of requirements and the large number of changes may cause delay 
-	stability risks (crashes, disconnects, etc)
-	insufficient resources


Product Risks:
-	Internet Explorer browser might have performance issues
-	versions of Internet Explorer browser older than 1.5923e have security vulnerabilities (we could mention what vulnerabilities are)
-	the web page pagination could be impacted when opened on mobile devices
-	new browser might not be supported
-	stress conditions might impact the web application

### 2.2 Test analysis ### 

-	the testing process will be done based on the requirements for features: Login Module, Settings Module: Change Password, Change E-mail
-	we plan on running a full regression test on the current version to make sure that changes have not modified the curent system functionality 

### 2.3 Test design ###

-	all the test cases are written and reviewed 
-	functional test cases will be created in Jira Software Development Management Tool using Zephyr Squad Test Management Tool
-	GUI test cases will be created in Jira Software Development Management Tool using Zephyr Squad Test Management Tool
  
### 2.4 Test implementation ###

-	all the test data is available and reviewed (test data = email example, password example)
-	this test run includes only regression testing in which we will run tests that have the highest priority, this will be main priority
-	cycle summary was created and test cases were added to the cycle summary 
-	test environment is up and running: [link to test environment](https://demo.aeries.net/ParentPortal/LoginParent.aspx?demo=True&user=student%40aeries.com&pwd=1234)
-	smoke test passed 

### 2.5 Test execution ###

-	the tests will be executed on the top 4 used browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari. If time will be available we will extend tests on Opera Brave and Internet Explorer browsers
-	test cases will be executed on the created Test Cycle Summary
-	bugs will be reported based on the failed tests

### 2.6 Test closure ###

-	at least 90% of tests are passed
-	no critical issues have Open status
-	exploratory testing has been performed

### 2.7 Test monitoring and control ###

-	various periodic reports (daily/weekly/bi-weekly) will be generated to reflect the current status of the testing process. 

## 3.	Test deliverables ##

### 3.1 Test plan - [link to test plan](https://github.com/Madalina088/Aeries_Project/tree/main) ###

-	the Test Plan is designed to describe all the details of testing for the following features: 
-	the plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing process, the risks associated with the plan, the resources and schedule required to complete testing. 

### 3.2 Test conditions ###

-	we will use test environment
-	testing using new accounts and older account is necessary
-	the following test conditions could be found here: *[Test Conditions. ](https://github.com/Madalina088/Aeries_Project/blob/main/Test%20Cases.xlsx)

### 3.3	  Test cases ###

 - the test cases with steps could be found here: *[Test Cases. ](https://github.com/Madalina088/Aeries_Project/blob/main/Test%20Cases.xlsx)

### 3.4 Daily/Weekly/Bi-weekly test summary report ###

 - link to daily test summary report (number of tests ran today, % of them failed, passed, re-test, etc)
<p float="left">
  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Change%20email%20functionality%20V%201.0.png" width="32%"/>
  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Change%20the%20password_functionality%20V%201.0.png" width="33%"/>
  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Sign%20In%20functionality%20V%201.0.png" width="32%"/>
</p>

### 3.5 Traceability matrix ###

 - link to traceability matrix ![Traceability matrix!](https://github.com/Madalina088/Aeries_Project/blob/main/Aeries_Project_Traceability%20Matrix_2.png)

### 3.6 Test case results ###

 -  the test cases results could be found here: *[Test Cases Results. ](https://github.com/Madalina088/Aeries_Project/blob/main/Test%20Cases.xlsx)

### 3.7 Bugs report ###

 - the bugs reported could be found here: *[Bugs Report ](https://github.com/Madalina088/Aeries_Project/blob/main/Bugs%20report.csv)

### 3.8 Test completion report ###

 - link to test completion report (Test cases ran, how many TC are passed and how many are failed)*vom adauga screenshot cu test completion report din Jira la sfarsitul testarii (toate test case-urile au fost executate)

### 3.9 Schedule ###

 - we have 10 days of testing
 - we have 30 functional and GUI tests
 - in order to finish the regression run we would need to run an ~ of 3 tests/day




