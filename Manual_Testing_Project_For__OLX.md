<h1>Testing Project for OLX </h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: OLX

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories was created in Jira and describes the functional specifications of the **Jobs** => Call Center - Customer Support module, for which the final project is performed upon.

![aft_board_2024-05-01_03 37pm](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/acb25e69-6ffa-4e18-9684-7863e41abd7c)

Here you can find the release that was created for this project:

![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/19a1e9ff-1f3b-44b4-92b6-d559278fc587)
![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/ff9aadf4-8ce1-4a46-91e7-c7efcb121b8d)
![image](https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/assets/167453855/a8da57d2-1575-43fc-b241-60a9fc3e9f7c)




<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here https://github.com/Andrei-ionut27/OLX-Jira-Manual_testing/blob/main/Test%20Plan%20-%20OLX%20Version%202.0.pdf

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager</li> Gaube Natasha
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

- Some categories may not work on different languages 
- The translation on the web app is not working 

<h5> Product risks: </h5>

- load testing would be necessary because the system crashes when there are many users in the web application
- The web app may crash on 3rd parties softwares
- stability risks (crashes, disconnects, etc)
- The older versions of Google Chrome can impact the performance
- The opera browser may crash on this version
- the web page pagination could be impacted when opened on mobile devices
- new browser might not be supported


<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

We measured and analyzed continuously of specific metrics to gain valuable insights, assess progress and proactively identify potential issues,Offering feedback to the QA team and other stakeholders regarding the progress of sprint test cycles.

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
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**(aici puteti fie sa puneti o poza din jira cu titlurile tuturor testelor - din issues filtrare dupa type test sau sa scrieti cu bulinuta numele fiecarei conditii de testare pe care ati identificat-o)**

<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(inserati linkul catre fisierul cu testele, in format pdf, word sau csv)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

**(inserati lista de elemente care sunt evaluate in etapa de implementare)**

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(inserati aici fisierul cu bug-urile pe care le-ati identificat)**

The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(inserati aici raportul de executie generat din jira din sectiunea de dashboards)**

The final report shows that a number **(inserati numarul de teste)** tests have failed of a total of **(inserati numarul de teste)**

A number of **(inserati numarul de bug-uri)** total bugs were found, from which the priority is: **(inserati numarul de bug-uri)** are high and **(inserati numarul de bug-uri)** are medium.

**(inserati aici o concluzie generala a testarii care sa cuprinda cate teste au fost create si executate, ce procentaj aproximativ din cerintele in scop au fost acoperite, daca exista vreo functionalitate pe care nu ai apucat sa o testezi, daca bug-urile gasite impacteaza lansarea produsului in productie sau se pot fixa si ulterior, daca ai identificat riscuri de produs care trebuie mitigate, daca e vreo reecomandare pe care vrei sa o faci pentru lansare, daca sunt ceva lessons learned de care trebuie sa se tina cont la proiectele viitoare etc.)**

