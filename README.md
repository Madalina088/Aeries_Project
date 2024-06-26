# Aeries_Project #
| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 14.07.2023 | Test Plan for version 1.0 | Madalina Bogdan|             |
| 05.03.2023 | Test Plan for version 1.1 | Madalina Bogdan|adding the last details for the implementation of the tests    |


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

The Aeries project intends to give students and parents with an information system where they may check grades, update contact information, and access any other school-provided information. 
This release will have restricted features. Over time, the software product's functionality will expand.

### 1.1	Project Objective ###

Before distributing the project to clients, we must detect and prevent defects while also increasing trust in its quality.
- Application under test: [Aeries Parent Portal](https://demo.aeries.net/ParentPortal/LoginParent.aspx?demo=True&user=student%40aeries.com&pwd=1234)
- Application documentation: 
[Suporting Documentation](https://support.aeries.com/support/home) - [API Documentation](https://support.aeries.com/support/solutions/articles/14000077926-aeries-api-full-documentation)

### 1.2 Functionalities in scope ###

- the following functionalities are going to be tested: 
Login Module, Settings Module: Change Password, Change E-mail, Configure Grade Alerts, Add New Student To Your Account, Log Out
-	the features in scope for testing: Login Module, Settings Module: Change Password, Change E-mail
-	testing types used: Functional testing like Graphical User Interface(GUI) Functional Testing

### 1.3	 Functionalities and tests out of scope ###

-	the features out of scope: Settings Module: Configure Grade Alerts, Add New Student To Your Account, Log Out
-	non-functional testing like stress, load, performance is beyond scope of this project
-	no QA support for mobile applications developed, only web applications will be tested
-	automation testing is beyond scope.

## 2.	Test process ##
 	
### 2.1	 Test planning ### 

Roles and responsibilities

| Tester  | Madalina Bogdan  | Will test:  Login Module, Change Password, Change Email | 
|---|---|---|

Entry criteria:

-	functional business specifications are defined
-	test plan document is defined 
-	roles needed for the project are allocated


Exit criteria:

-	all test cases have been executed 
-	90% of tests are passed
-	no critical issues/bugs have open status (All unresolved bugs have low priority and low severity)
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
-	versions of Internet Explorer browser older than 1.5923e have security vulnerabilities 
-	the web page pagination could be impacted when opened on mobile devices
-	new browser might not be supported


### 2.2 Test analysis ### 

-	the testing process will be done based on the requirements for features: Login Module, Settings Module: Change Password, Change E-mail
-	we plan on running a full regression test on the current version to make sure that changes have not modified the curent system functionality 

### 2.3 Test design ###

-	all the test cases are written and reviewed 
-	functional test cases will be created in Zephyr Squad Test Management Tool using Jira Software Development Management Tool  
-	GUI test cases will be created in Zephyr Squad Test Management Tool using Jira Software Development Management Tool  
  
### 2.4 Test implementation ###

-	all the test data is available and reviewed (test data = email example, password example)
-	cycle summary was created and test cases were added to the cycle summary 
-	test environment is up and running: [link to test environment](https://demo.aeries.net/ParentPortal/LoginParent.aspx?demo=True&user=student%40aeries.com&pwd=1234)
-	smoke test passed 

### 2.5 Test execution ###

-	the tests will be executed on the top 4 used browsers: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari. If time will be available we will extend tests on Opera Brave and Internet Explorer browsers
-	test cases will be executed on the created Test Cycle Summary  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Cycle%20Summary.png" width="75%"/>
-	bugs will be reported based on the failed tests

### 2.6 Test closure ###

-	at least 90% of tests are passed
-	no critical issues have Open status
-	exploratory testing has been performed

### 2.7 Test monitoring and control ###

-	various periodic reports (daily/weekly/bi-weekly) will be generated to reflect the current status of the testing process <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Daily%20Test%20Execution%20Progress.png" width="100%"/>

## 3.	Test deliverables ##

### 3.1 Test plan - [link to test plan](https://github.com/Madalina088/Aeries_Project/tree/main) ###

-	the Test Plan is designed to describe all the details of testing for the following features: Login Module, Settings Module: Change Password, Change E-mail
-	the plan identifies the items and the features to be tested, the type of testing to be performed, the roles and responsibilities for testing process, the risks associated with the plan, the resources and schedule required to complete testing. 

### 3.2 Test conditions ###

-	we will use test environment
-	the following test conditions could be found here: *[Test Conditions. ](https://github.com/Madalina088/Aeries_Project/blob/main/Test%20Cases.xlsx)

### 3.3	  Test cases ###

 - the test cases with steps could be found here: *[Test Cases. ](https://github.com/Madalina088/Aeries_Project/blob/main/Test%20Cases.xlsx)

### 3.4 Daily/Weekly/Bi-weekly test summary report ###

 - The report for the executed tests was generated after all the tests were run, out of total 17 tests executed: 14 tests were successfully executed for 3 tests reported errors
   
<p float="left">
  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Change%20email%20functionality%20V%201.0.png" width="32%"/>
  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Change%20the%20password_functionality%20V%201.0.png" width="33%"/>
  <img src="https://github.com/Madalina088/Aeries_Project/blob/main/Sign%20In%20functionality%20V%201.0.png" width="32%"/>
</p>


### 3.5 Traceability matrix ###

- Traceability matrix report:
![Traceability matrix!](https://github.com/Madalina088/Aeries_Project/blob/main/Aeries_Project_Traceability%20Matrix_2.png)

- for the first business requirement 7 tests were executed, of which 5 tests ran successfully and for 2 of them I reported defects (errors)
- for the second business requirement 5 tests were executed, of which 4 tests ran successfully and for 1 of them I reported defect (error)
- for the third business requirement 3 tests were executed, all of them ran successfully

### 3.6 Test case results ###

 -  the test cases results could be found here: *[Test Cases Results. ](https://github.com/Madalina088/Aeries_Project/blob/main/Test%20Cases%20Result.csv) 

### 3.7 Bugs report ###

 - the bugs reported could be found here: *[Bugs Report ](https://github.com/Madalina088/Aeries_Project/blob/main/Bugs%20report.csv)

### 3.8 Test completion report ###

 - link to test completion report (Test cases ran, how many TC are passed and how many are failed)*vom adauga screenshot cu test completion report din Jira la sfarsitul testarii (toate test case-urile au fost executate)

### 3.9 Schedule ###

 - we have 10 days of testing
 - we have 30 functional and GUI tests
 - in order to finish the regression run we would need to run an ~ of 3 tests/day




