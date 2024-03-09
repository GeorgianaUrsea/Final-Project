#The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test:


The final project will be split into 2 sections: Theoretical section and Testing section.

Tools used: JIRA

Functional specifications

-> Stories, Test-cases, Test-conditions, Traceability matrix, Test execution, Risk analysis, Bug-ticket.

Theoretical section:

1.BUSINESS REQUIREMENTS

-Business requirements, what do they use us for and who creates them?

Business requirements represent the client's expectations for the completion of a software product.

Business requirements are seen by the testing team as a manual with instructions that must be followed in order to create a software product that meets the client's expectations.

Business requirements are created by the Product Owner and the customer.

2.TEST CASE VS TEST CONDITION

-Test Case and Test Condition

TEST CONDITION- represents a feature that must be checked during the testing process, to validate the functionality of a feature.

TEST CASE- represents a set of instructions that must be followed the purpose of verifying a functionality.

3.RETESTING VS REGRESSION TESTING

-Retesting and regression testing

Retesting - is the process by which it is checked whether the defects that appear as fixed have really been corrected.

Regression testing - is the process by which it is verified that as in the past the changes made program have no result new defects.

4.STAGES OF THE TESTING PROCESS

-Planning 
• In this stage, it is determined which parts of the application are tested.

• Roles are assigned to each person in the team, entry and exit criteria are created, project risks are identified, a test plan is evaluated.

-Analyze

• In this stage, the documentation received from the client is analyzed.

• The test conditions are generated.

-Design

• The test plan is being developed

• The test data is identified

• The design of the test environment is done

-Implementation

• The test data and the test environment are created

• Tests are prioritized and grouped

-Execution

• The test cases are carried out according to the documentation

• The results are recorded, the status of the test is indicated (passed, failed or blocked)

• When the expected results do not coincide with the current ones, the existence of a bug is registered.

• Retesting and regression testing are performed

-Finish

• The exit criteria are evaluated

• Remaining tasks and bugs are solved

• Test materials are delivered and archived

• A closing report is generated (test summary report or test completion report)

• Product risks are identified

Monitoring and Control - Is performed throughout the testing process.


5.BLACK-BOX TESTING VS WHITE-BOX TESTING

BLACK-BOX TESTING - 
• Black-box testing techniques help us to develop test conditions, test data and test cases based on a rigorous examination of the documentation.

• It does not require knowledge of the code behind the program.

WHITE-BOX TESTING - 

White-Box testing, also called structural testing, refers to testing the internal structure of a system/component.

• Requires knowledge of the source code.

Functional Testing VS Non-functional Testing

Functional Testing-

• Functional testing answers the question: "What should it do?"
the product?"

• The tests are carried out based on the specifications and show what the product is supposed to do, what it is used for.

• All product functionalities are presented.

Non-functional Testing

• Non-functional testing answers the question: "HOW SHOULD THE PRODUCT BEHAVE?”

• Non-functional tests show how well the product performs the functionalities.

6.Testing techniques

6.1 Black Box

-Equivalent partitioning

-Analysis of limit values

-Testing state transitions

-The decision table

6.2 White Box

- Statement Coverage
  
-Decision Coverage

6.3 Experience-based

-Error guessing

-Exploratory Testing

-Checklist based testing

7.Verification vs Validation

Verification - The process of verifying the quality of the software. it
verify the proper execution of the processes for creating a product according to the client's expectations.
It focuses on documentation, code.

Validation - Validation of the client's requirements through the functionality of the software. It focuses on the fact that the finished product meets the customer's expectations.


8.Positive Testing vs. Negative Testing

Positive test - Testing the system with values it should be able to process

• Ex: Entering correct credentials. The wait being like its software
work.

Negative Testing - Testing the system with values that it should not be able to process, expecting it to fail.

• Ex: Entering wrong credentials. The system must fail.

9. Test levels

Unit testing - Testing each functionality in a system. Checking: functions, classes, etc.

Integration testing - The interaction between components and systems is tested.

There are 2 types of integration testing: integration between components and integration between systems.

System testing - It focuses on the behavior of the entire system, taking into account the behavior of the functionalities, but also the non-functional behavior of the tasks.

Acceptance testing - It focuses on the behavior and functionalities of the system.

Alpha testing: Testing an application when the development is
complete/almost complete.
It presents 2 phases:
1.The software is tested by the developers.
2. Testing is done by the QA team. 

Beta testing:
It takes place at the customer's site.



2. TESTING SECTION

1.1 Test Planning

The Test Plan is designed to describe all details of testing for the modules from the (https://epantofi.ro/) website.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

1.1.1 Roles assigned to the project and persons allocated:

Vlad - manager

ALex - junior tester

ALin - senior

ALexandra - automation tester

Roxana - product owner

Amalia - project manager


1.1.2 Entry criteria defined:

Complete documentation

Good team

High performance hardware

Windows version 4.1


1.1.3 Exit criteria defined

No Critical test case open

75% passed test cases


1.1.4 Test scope


Tests in scope:


-For the website www.epantofi.ro, as a new user, I would like to create an account with a non-existent e-mail address.

-For the "www.epantofi.ro" website, check the functionality of the "Forgot my password" button. By connecting with link.

-Check the functionality of applying two filters "Price" and "Color" for the site "www.epantofi.ro".

-For the website "www.epantofi.ro" check filter application functionality "Brand" for bags.

-Checking the "Size" filter application for the "www.epatofi.ro" website.

-Checking the functionality of the black "color" filter, for men.

-Check the functionality of the "Price" filter application for 200 lei

-Check for the website "www.epantofi.ro" if you can find the product "Sneakers Cuzima 28533550 Purple G507" by applying the filters



Tests not in scope:

-Verification of account creation for new users on the website "www.epantofi.ro"

-Check returns an error for connecting with an incorrect password to an existing account. For the website "www.epantofi.ro"

-For the website www.epantofi.ro, as a new user, I would like to create an account with a non-existent e-mail address.

-Checking for the website "www.epantofi.ro" connection with wrong credentials

-For the website "www.epantofi.ro" check the login with correct credentials for the existing account.


1.1.5 Risks detected

Project risks:

-New people in the team who do not have knowledge

-Misunderstandings in the team, loss of time, failure to meet the deadline

-The risk of exceeding the budget

-Bad, old hardware

-Poor code quality, developers

-Unclear requirements



Product risks:

- does not correspond to the requirements of the client, documentation

- dificult/not user friendly application
  
-  the product packaging to be broken
   
- functionality problems/fluctuations in product quality
  
- the risk of the product to be damaged
  
- the risk of compatibility of uploaded files
  

1.1.6 Evaluating entry criteria

The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

1.2 Test Monitoring and Control

It will be done by generating periodic reports that reflect the current status of the test.

1.3 Test Analysis

The testing process will be executed based on the above requirements for the Dependents module. The following test conditions were found:

-For the website www.epantofi.ro, as a new user, I would like to create a new account

-For the website www.epantofi.ro, I want to find a product of a certain color, size, brand.

-For the website www.epantofi.ro, as a new user, I would like to create an account with a non-existent e-mail address.

-For the "www.epantofi.ro" website, check the functionality of the "Forgot my password" button. By connecting with link.

-Check the functionality of applying two filters "Price" and "Color" for the site "www.epantofi.ro".

-For the website "www.epantofi.ro" check filter application functionality "Brand" for bags.

-Checking the "Size" filter application for the "www.epatofi.ro" website.

-Checking the functionality of the black "color" filter, for men.

-Check the functionality of the "Price" filter application for 200 lei

-Check for the website "www.epantofi.ro" if you can find the product "Sneakers Cuzima 28533550 Purple G507" by applying the filters

-Verification of account creation for new users on the website "www.epantofi.ro"

-Check returns an error for connecting with an incorrect password to an existing account. For the website "www.epantofi.ro"

-For the website www.epantofi.ro, as a new user, I would like to create an account with a non-existent e-mail address.

-Checking for the website "www.epantofi.ro" connection with wrong credentials

-For the website "www.epantofi.ro" check the login with correct credentials for the existing account.


1.4 Test Design

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are:


Test cases: 

Test case 1 - "-Check for the website "www.epantofi.ro" if you can find the product "Sneakers Cuzima 28533550 Purple G507" by applying the filters" - priority HIGH

Test case 2 - "Check the creation of a new user account on the website "www.epantofi.ro" - priority Highest

Test case 3- "Check the functionality of the "Price" filter application for 200 lei" - priority Medium

Test case 4 - "Checking the functionality of the black "color" filter, for men." - priority Medium

Test case 5 - "Checking the "Size" filter application for the "www.epatofi.ro" website." - priority Medium

Test case 6 - "For the website "www.epantofi.ro" check filter application functionality "Brand" for bags." - priority Medium

Test case 7 - "Check the functionality of applying two filters "Price" and "Color" for the site "www.epantofi.ro"" - priority Medium

Test case 8 - "For the website "www.epantofi.ro" check the login with correct credentials for the existing account." - priority Medium

Test case 9 - "Checking for the website "www.epantofi.ro" connection with wrong credentials." - priority medium

Test case 10 - "For the "www.epantofi.ro" website, check the functionality of the "Forgot my password" button. By connecting with link." - priority Medium

Test case 11- "For the website www.epantofi.ro, as a new user, I would like to create an account with a non-existent e-mail address." - priority Mediumn

Test case 12 - "Check returns an error for connecting with an incorrect password to an existing account. For the website "www.epantofi.ro" - priority Medium




1.5 Test Implementation

The following elements are needed to be ready before the test execution phase begins:

-The test environment

-Functional laptop

-An existing account

-Internet access

-Knowledge of the documentation


1.6 Test Execution


Test cases are executed on the created test Cycle summary: [cycle_summary_execution.pdf](https://github.com/GeorgianaUrsea/Final-Project/files/14539421/cycle_summary_execution.pdf)


Bugs have been created based on the failed tests. The complete bug reports can be found here: [Bug_reports.pdf](https://github.com/GeorgianaUrsea/Final-Project/files/14539509/Bug_reports.pdf)



1.7 Test Completion

Exit criteria was evaluated and passed

The traceability matrix was generated and can be found here: [Traceability_matrix.pdf](https://github.com/GeorgianaUrsea/Final-Project/files/14539540/Traceability_matrix.pdf)

Test execution chart was generated, the final report shows:

-TEST PASS- 9 OF 12 

-75 % PASS

-25 % FAIL

[Test_execution_chart.pdf](https://github.com/GeorgianaUrsea/Final-Project/files/14539598/Test_execution_chart.pdf)
