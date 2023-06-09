# ARusu-OrangeHRM-PIM-Module
ARusu-Testare-Manuala-OrangeHRM-PIM-Module



# Proiect-Testare-Manuala



### test design



<h2>test plan </h2>



| Role  | Name |
|---|---|
| Product Owner | Anca Pop |
| Software Developer | Diana Popescu |
| Software Tester | Andreea Rusu |


| Date  | Description | Author  | Comments |
|---|---|---|---|
| 28.04.2023 | V1.0 | Andreea Rusu  |   |
| 05.05.2023 | V1.1 | Andrada Pop  | More details added on Test Implementation |
| 05.06.2023 | V1.2 | Andreea Rusu  | Test completion report added |


1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item 

- First item
- Second item
- Third item
    - Indented item
    - Indented item
- Fourth item 

​


Orange HRM **project**.

Orange *HRM* project
​


## These are the test conditions

​


![Test conditions](https://github.com/andioniciuc/Proiect-Testare-Manuala/blob/main/271995698_143580008090271_4756762964896555660_n.jpg)

​



The test cases can be found here [Test Case No. 1](https://github.com/andioniciuc/Proiect-Testare-Manuala/blob/main/Regina%20Maria_Cum%20te%20poti%20proteja%20de%20canicula.pdf)



​



​



    1. Introduction
        1.1. Project objective
        1.2. Functionalities in scope
        1.3. Functionalities and tests out of scope
    2. Test process
        2.1. Test planning
        2.2. Test analysis
        2.3. Test design
        2.4. Test implementation
        2.5. Test execution
        2.6. Test closure
        2.7. Test monitoring and control
    3. Test deliverables
        3.1. Test plan
        3.2. Test conditions
        3.3. Test cases
        3.4. Daily test summary reports
        3.5. Traceability matrix
        3.6. Test case results
        3.7. Bugs report
        3.8. Test completion report


### 1. Introduction
This test plan document describes the strategies, process, workflows and methodologies used to plan, organize, execute and manage testing process for OrangeHRM.

#### 1.1. Project Objective
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge through the course and apply them in practice, using a live application. 

Application under test: https://opensource-demo.orangehrmlive.com/web/index.php/dashboard/index the focus will be only on Admin module

Application documentation: https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf 

Tools used: JIRA, Zephyr Squad, Postman, MySQL Workbench.

* If needed: The final project will be split into 2 sections: Testing section (Jira, Postman) and SQL Section (MySQL)


#### 1.2. Functionalities in scope
- All the features of Admin module which were defined in business requirements need to be tested: functional testing, GUI testing and API testing 
- The below user story was created in Jira and describes functional specifications of the PIM module, for which the final project is performed upon.

*Screenshots din Jira cu user story-ul 

#### 1.3.Functionalities and tests out of scope
- Non-functional testing like stress, performance is beyond scope of this project 
- No QA support for mobile application developed. Only web application will be tested. 
- Automation testing is beyond scope


    
    
    ### 2. Test process
#### 2.1. Test planning

The Test Plan is designed to describe all details of testing for the PIM module from the OrangeHRM application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

**Roles assigned to the project, persons allocated and responsibilities**
| Role  | Name |
|---|---|
| Product Owner | Anca Pop |
| Software Developer | Diana Popescu |
| Software Tester | Andreea Rusu |



**Entry criteria:**
- Business specifications are defined 
- Roles needed for the project are allocated 
- Initial project risks were detected and mitigated 

**Exit criteria:**
- All test cases have been executed 
- The unresolved bugs/defects have low priority 
- No detected major risks remained un-mitigated 
- All resolved bugs have been retested and approved by the testers
- Regression testing have been ran and no major bugs detected  
- All business requirements have been covered by test cases 
- All business requirements have been met 

**Risks:**
- Project risks: lack of experience of QA team, lack of tools, short deadline for Jira and Zephyr Squad, unavailability of OrangeHRM demo environment
- Product risks: Validation constraints on the fields might be too restrictive to the end user 

#### 2.2 Test analysis 
- Analyze the business requirements to make sure that we have all the details to create the test conditions 
- Write test conditions that will be tested in out test process 

#### 2.3 Test design
- Functional test cases will be created in Jira 
- GUI test cases will be created in Jira 
- API test case will be created in Postman 
- Queries in DB will be done in MySQL





#### 2.4 Test implementation
Verify if the following elements are ready before test execution:
* Test environment is up and running: https://opensource-demo.orangehrmlive.com/web/index.php/auth/login 
- Access to test environment is given: username Admin, password: admin 123
+ Cycle summary was created 
- Test cases were added to the cycle summary 
- Postman collection with the API methods was created 
- Authorization token was created accessing the API and it is valid 


#### 2.5 Test execution
- Test cases are executed on the created cycle summary 
- Bugs have been created based on the failed test cases. The complete bug reports can be found here: *se poate pune link catre un fisier cu bug reports in Github 
- API tests are executed based on the checklist (requirements)
- Full regression pack is executed after changes made to the application 
#### 2.6 Test closure
- All exit criteria were met as mentioned in the Test Planning section (2.1)
- The traceability matrix was generated to demonstrate the business requirements coverage
- Test execution chart was generated, the final report shows a number of 3 failed test cases of a total 30
- There are still 3 opened defects but they have low priority
#### 2.7 Test monitoring and control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken.




#### 3. Test deliverables

#### 3.1. Test plan
The plan identifies the items to be tested, the features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the resources and schedule required to complete testing and the risks associated with the plan. 

#### 3.2. Test conditions
_*The following test conditions were created: 

-screenshot Jira 

#### 3.3. Test cases
*The following test cases were created: 

-screenshot Jira 

#### 3.4. Daily test summary report 
*The daily report was generated: 

-screenshot Jira 

#### 3.5. Traceability matrix
*The traceability matrix was generated: 

-screenshot Jira 

#### 3.6. Test case results
*The test cases results:

-pdf exported from Jira with all test cases and results

#### 3.7. Bugs report
*The bug reports exported from Jira:

-pdf exported from Jira with all bug reports

#### 3.8. Test completion report
*The test completion report generated from Jira:

-screenshot with test completion report



#### 3.9. Schedule
A test schedule includes the testing steps or tasks, the target start and end date and responsibilities. 


| Task  | Date | Name/Team member  | 
|---|---|---|
| Run functional test cases for Job submenu of Admin module | 28.04. 2023 | Andreea Rusu  |   
| Run GUI test cases for Job submenu of Admin module | 02.05. 2023 | Andreea Rusu  | 
| Summary | 05.06.2023 | Andreea Rusu  | 

