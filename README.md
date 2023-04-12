# Final project for IT Factory Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application. 

Application under test: https://opensource-demo.orangehrmlive.com/

API Documentation: https://orangehrm.github.io/orangehrm-api-doc/

The final project will be split into 2 sections: Testing section and SQL section.

Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench.

# Functional specifications

The below Epic was created in JIRA and describes the functional specifications of the Admin module, for which the final project is performed upon.

![Epic-Admin Module 5.0.PNG](https://github.com/AdinaIT/Repo_Project_Jira/blob/main/Epic-Admin%20Module%205.0.PNG) 

# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the Admin module from the OrangeHRM application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

#### 1.1.1 Roles assigned to the project and persons allocated

* Project manager - Andrei Marinoiu
* Product owner - Andy Simpetrean
* Software developer - Gabriela Radulescu
* Software QA Tester - Adina Boeru

#### 1.1.2 Entry criteria defined

* functional specifications are defined
* roles needed for the project are allocated
* initial project risks were detected and mitigated

#### 1.1.3 Exit criteria defined

* number of unresolved bugs is insignificant or they have low priority
* all tests have been executed
* all resolved bugs have been re-tested and approved by the QA team
* deadline was reached
* no detected major risk remained un-mitigated
* exploratory regression testing must be performed on the My Info module, which includes the Dependents section


#### 1.1.4 Test scope

* __Tests in scope:__ All the feature of Dependents module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing
* __Tests not in scope:__ performance testing, integrations of the dependents module with other modules, compatibility testing with multiple browsers

#### 1.1.5 Risks detected

* Project risks: lack of experience of the QA team, short term for the Zephyr Squad test, unavailability of the test environment, relatively unclear and sometimes insufficient business requirements.
* Product risks: the validation constraints on the fields could be too restrictive for the end user, the application has a low quality of non-functional parameters (usability, performance, maintainability),sometimes the app crash causes a re-login and then a password change is required for security reasons


#### 1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue

## 1.2 Test Monitoring and Control

Variou periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.
The following status report was generated after 40% of the test cases were executed, on 1st of April 2023:

Test Executions by Test Cycle   

![Jira.PNG](https://github.com/AdinaIT/Repo_Project_Jira/blob/main/Jira.PNG)
