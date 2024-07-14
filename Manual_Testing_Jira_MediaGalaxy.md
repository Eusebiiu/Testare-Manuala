<h1>Testing Project for **Media Galaxy**</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **Media Galaxy**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The stories attached [here](https://github.com/Eusebiiu/Testare-Manuala/blob/main/stories-jira.doc) was created in Jira and describes the functional specifications of the "User atuthentication" module, for which the final project is performed upon.

You can find a example of one of the stories that were created below: 

![image](https://github.com/user-attachments/assets/24ec79e2-3b15-4ecf-b8d2-3f849dcc3864)

##Realease
Here you can find the release that was created for this project:

![image](https://github.com/user-attachments/assets/ccac7641-cca2-44b9-a57b-ac44d923a91a)


<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for User authentication module for Media Galaxy e-commerce app.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the project risks associated with the plan. The test plan that was created for this project can be found here **(inserati link catre documentul cu planul de testare)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>


<table>
<tr><td>Project manager</td> <td>Ion Stratulat</td></tr>
<tr><td>Product owner</td><td>Mihai Avramescu</td></tr>
<tr><td>Software developer</td><td>Mierl Stoicescu</td></tr>
<tr><td>QA Engineer</td><td>Eusebiu Mihalache</td></tr> 
</table>

<h4> 1.1.2 Entry criteria defined </h4>

<li>The bussiness requirments must be finalized
<li>The roles should be alcoated
<li>Test plan must be finished and sent to stakeholders
<li>The Entry Criteria And exit Criteria must be defined
<li>The project risks must have been identified and mitigated

<h4> 1.1.3 Exit criteria defined </h4>

<li>All key features of the software have been tested and work according to specifications.
<li>All critical use cases have been successfully tested.
<li>No major or critical defects have been identified that could impact the usability of the software.
<li>The software is compatible with other systems and applications that it needs to interact with.
<li>No significant compatibility issues have been identified that could prevent the software from being used
<li>The deadline has been reached

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

In order to fullfill the testing objectives we are going to focus on the Register Module(and Log In Moduke) which has been places on the scope and has been targeted for improvement over the next 3 months.

From the point of view the testing types and tehniques we are going to use are mostly black box testing with the fallowing test design tehniques:
<li>Boundary Value Analysis
<li>Equivalence Partiotioning
<li>decision table

From non-functional testing we are going to cover only usability testing and compatibility testing.
Also negative and positive testing are to be done and retesting and regression testing will be done when defects are be going to be fixed or when modification of any type are going to be brought to the code.

<h5>Tests not in scope: </h5>

Performance and security testing will not be performed during this session of testing.

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

**(enumerati aici toate riscurile de proiect pe care le-ati identificat pentru proiectul vostru)**

<h5> Product risks: </h5>

**(enumerati aici toate riscurile de produs pe care le-ati identificat pentru proiectul vostru)**

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

**(inserati aici motivul pentru care a fost facuta etapa de monitorizare si control si respectiv cum s-a facut aceasta etapa. Aici veti insera de asemenea si raportul de status (test status report) din zephyr - test metrics - primul din lista care sa reflecte activitatea si evolutia testarii. Recomand aici sa executati teste aproape in fiecare zi ca sa vada angajatorul implicarea voastra in testare)**

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. 

The following test conditions were found: <br>
![image](https://github.com/user-attachments/assets/1104b129-4f23-4d5d-aab2-2da0a34b4ec5)



<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here](https://github.com/Eusebiiu/Testare-Manuala/blob/main/test-cases-jira.pdf) 

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:



<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary:

Bugs have been created based on the failed tests. The complete bug reports can be found [here](https://github.com/Eusebiiu/Testare-Manuala/blob/main/jira-bug.pdf)

The following is a summary of the bugs that have been found
![image](https://github.com/user-attachments/assets/1a7c6d04-dde8-4902-a8b7-4e572732be29)

<li>ST3EM-28 Priority High, Severity Medium
<li>ST3EM-21 Priority High, Severity High
<li>ST3EM-15 Priority High, Severity High


Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: 

![image](https://github.com/user-attachments/assets/2d984592-1706-47fb-abf6-d5820674370f)

Test execution chart was generated and can be found below. 

![image](https://github.com/user-attachments/assets/9b986b11-4212-49e3-9d12-72fb321a29af)


The final report shows that a number 12 tests have failed of a total of 3**

A number of 3 total bugs were found, from which the priority is: 3 are high and 1 are medium.

Software testing incomplete: defects identified in stories 1 and 3. 75% requirement coverage achieved, but minor bugs require fixing before launch. Recommend additional testing for remaining requirements (25%) and post-launch monitoring for continued stability.
