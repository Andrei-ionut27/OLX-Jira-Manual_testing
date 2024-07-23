<h1>Testing Project for OLX </h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: OLX

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories was created in Jira and describes the functional specifications of the **Jobs** => Call Center - Customer Support module, for which the final project is performed upon.

![aft_board_2024-05-14_08 58pm](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/8930ee1f-c974-4b10-8cb6-fbcd7cf4dd76)


Here you can find the release that was created for this project:
![Screenshot_3](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/b695100e-c371-4b39-8e2f-a45cd621f179)
![Screenshot_4](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/50178dbb-7ffc-456b-880e-fb56f569f0c5)
![Screenshot_5](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/a2234580-ad06-4b38-880c-3480cee4eede)
![Screenshot_6](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/3cf2039f-8019-439f-8d01-82a821da8ef6)







<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found [Here](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/blob/main/Test%20Plan%20-%20OLX%20Version%202.0.pdf)

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager</li> Gaube Natasha<br>
  <li>Product owner</li> Varga Alexandra
  <li>Software developer</li> Magdau Maria
  <li>QA Engineer</li> Florea Andrei
</ul>

<h4> 1.1.2 Entry criteria defined </h4>

- Business requirements are available and agreed\
- Roles and responsibilities are clear and agreed\
- Project risks  are identified and mitigated\
- Deadline established 
- Project objective established and communicated with the team QA


<h4> 1.1.3 Exit criteria defined </h4>

- 95% of tests are passed\
- No Critical issues have Open status\
- Update tests are 100% passed (update tests will not generate other new issues that impact the application)\
- Retests are passed and 
- regression testing are passed\
- The deadline has been reached\
- The objectives has been accomplished\
- The testing documentation is done and communicated to the stakeholders\
- The test summary report is communicated to the stakeholders\
- All the defects have been documented and communicated to the stakeholders


<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

 We are focusing our tests on the following areas:
1) The main category Jobs - In this section will test the category call center 
 Here will test the following areas:
- Job mobility
- Type job
- Work schedule
- Open to students
- Remote requirement
  
2) Add new ad
 Here will test the following areas:
- Add title
- Category
- Add imagines
- Description
- City
- Contact person
- Email address
- Phone number
- Post new add
Will make also make the following tests:
- Functional testing
- Retest
- Regression testing
- Positive testing
- Negative testing
Non functional testing:
- Usability testing
- Portability testing
- Maintainability testing
- Compatibility testing 
- Localization testing
  
  We will perform BlackBox testing (EP, BVA, STT, DT) and WhiteBox (Statement coverage and Decision Coverage).
  Also we will use google chrome and opera browser for testing.

<h5>Tests not in scope: </h5>

On the job area the following areas are out of scope:
- Subcategory
- Type of contract
- Level of education
- Level of experience
- Open role for people with disabilities
- Requires work permit
  
The following tests are out of scope:
- Automation testing is out of scope
- Performance testing is out of scope and all the subcategories of performance testing is out of scope
- Security testing will not be done
- Compliance regulation testing is out of scope


<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

•	Confusing navigation interface that could cause negative feedback from the users and, therefore, a possible loss of customers.\
•	Because of the short deadline the majority of tests might remain undone, and they might have functionalities problems.


<h5> Product risks: </h5>

•	The web app may crash on 3rd parties’ software.\
•	stability risks (crashes, disconnects, etc.)\
•	The older versions of Google Chrome can impact the performance.\
•	The opera browser may crash on this version.\
•	web page pagination could be impacted when opened on mobile devices.\
•	new browser might not be supported.\
•	Some categories may not work on different languages.\
•	The translation on the web app is not working. 



<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

 We measured and analyzed continuously of specific metrics to gain valuable insights, assess progress and proactively identify potential issues, Offering feedback 
  to the QA team and other stakeholders regarding the progress of sprint test cycles.

Test monitoring involves several tasks,
- Providing updates to the QA team and stakeholders about the ongoing sprint test cycles.
- Sharing the current test results with everyone involved.
- Keeping track of important test metrics.
- Planning and determining what to do next based on the tracked metrics.
  
  The following metrics will be monitored during the testing process,
- Cost 
- Schedule
- Resources
- Quality

  
  ![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/79099aff-cd81-4fd1-98e0-1875f124941e)

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements.

The following test conditions were found: <br>

![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/86f7ce67-7567-4e41-b106-848440ff6f8c)
![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/1b4b0a69-9a90-4bbc-982a-4c174c0eaab2)



<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here: https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/blob/main/ZFJ-Executions-05-02-2024.csv

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

https://www.olx.ro/

- Test environment is up and running and ready for testing
- We make sure the test data is available and accurate 
- We make sure we have the permissions to access the web application
- We group the most important test cases for testing
- Smoke test passed
- Permissions available 

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: 
- Olx Testing functionality on call center filters and the main category logo Jobs
- Testing Posting new ad fields where the user need to fill
- Olx Graphical user interface (gui) and Functionality

Bugs have been created based on the failed tests. The complete bug reports can be found here: [Jira.csv](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/files/15187549/Jira.csv)

The following is a summary of the bugs that have been found
![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/5b823e4f-3965-46c6-9f8e-0daed23e46a7)
![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/e7fa47c7-1235-4a73-9226-68c9f457ea36)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3>1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/blob/main/Forward%20Traceability%20for%20OLX.xlsx

Test execution chart was generated and can be found below. 

![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/24180627-9719-4ab6-ad90-8151c3e21c53)

The final report shows that a number 2 tests have failed of a total of 17.

A number of 10 total bugs were found, from which the priority is: 3 bugs are high and 7 are medium.

We executed a total of 17 tests and covered a total of 90% of the business requirements, the launch is not impacted by the bugs found, they can be fixed even if the app is launched.The product risks have been mitigated and the app can be launch.
