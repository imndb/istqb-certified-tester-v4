
Review:

- Reviews increase the quality of requirements specifications and lead to fewer changes being needed in derived work products
- typical formal review activities: Planning, kick-off, individual preparation, review meeting
- inspection -> most formal review
- informal review: inexpensive way to get some benefit.
- formal review:
author, moderator, review leader, scribe
- formal review based on rules and checklists: inspection
-  Checklists should not contain items that are better suited as exit criteria. "The achieved statement coverage exceeds 85%" is an example of an exit criterion.




QA, QC, Testing:

- Testing is performed as part of QC
- Testing is a significant part of QC and helps to uncover these defects

QC: test results are used to fix defects
QC: Activities designed to evaluate the quality of a component or system
- QC aims to achieve appropriate levels of quality by focusing on identifying and correcting product defects. Testing is a significant part of QC and helps to uncover these defects. Although testing is a significant part of QC and helps to uncover defects, other (non-testing) techniques utilized in QC include formal methods like model checking and proof of correctness, as well as simulation and prototyping


- Testing: The process consisting of all lifecycle activities, both static and dynamic, concerned with planning, preparation and evaluation of a component or system and related work products to determine that they satisfy specified requirements, to demonstrate that they are fit for purpose and to detect defects.

QA:  Activities focused on providing confidence that quality requirements will be fulfilled.

QA:	test results provide feedback on how the test process is performing



Test Plan, design, ... :


- working with test data requirements, test conditions, test environment
requirements and test cases -> test design

- Test implementation includes creating or acquiring the testware necessary for test execution (e.g., test data)

- Master test plan , test level plan -> where test planning is documenten

- test control: guiding or corrective actions taken as a result of metrics and reports


whitebox/blockbox:

- White-box coverage measures can help testers evaluate black-box tests in terms of the
code coverage achieved by these black-box tests

- White-box test techniques are not able to identify the missing implementation, because they are based solely on the test object structure, not on the requirements specification



coverage/metrics:

- In decision table testing, the test cases are independent of how the software is implemented. In branch testing, test cases can be created only after the design or implementation of the code

- Branch coverage metric:
       number of branches exercised by the test cases divided by total number of branches in the code
- Mean time to failure is a product quality metric.




Configuration management:  

- how configuration management (CM)
supports testing: Having the version number of the environment, the CM tool can retrieve the version
numbers of libraries, stubs and drivers used in that environment

- configuration management: managing information for managing products, facilities and processes.


The incorrect configuration data represents faulty software in the fitness tracker (a defect), that may cause failures



Definitions:





uncategorized:



- If a sequential development model is used, then the dynamic testing is typically restricted to later in the lifecycle


- To be able to update and release systems on a more frequent basis, many automated
regression tests are required to reduce the danger of regression

- System testing examines the behavior and capabilities of the complete system and covers non-functional testing of quality
characteristics, which includes security testing. This type of testing is often performed by an independent test team based on syste specifications

- Regression testing is concerned with adverse effects in unchanged code, whereas
confirmation testing is concerned with testing changed code










- Test automation: provides coverage measures that are too complicated for humans to derive

- Model based test approache uses statistical information about failure rates

- functional testing- > specification based testing 

- when selecting test approach, consider: test objectives, nature of system, hazards and safety


- test case: a set of conditions and variables used by testers to find defects

- debuging: identifying a defect, fixing a defect, performed by developer

- Analytical test approach uses risk-based testing where testing is directed at areas of greatest risk


- structural testing to measure how much testing has been carried out

- work-products: collection of documentation and code used to create the final product


- During development, versions of the software are created called work products then various testing activities can be performed on these early versions




- Selecting an approach that best achieves the objectives within the project constraints is a typical task performed during test planning


- During test implementation: A document describes a sequence of test cases in execution order and any associated actions that may be required to set up the initial preconditions and any wrap-up activities post-execution.




- a test tool to be intrusive: The test tool would affect the outcome of the test

- 

- sequential, incremental, iterativ SDLC: for every SDLC activity there is a corresponding test activity

- acceptance test-driven development (ATDD) tests are written from acceptance criteria as part of the design process

- error guessing is that the tester tries to guess what errors may have been made by the developer and what defects may be in the test object based on past experience (and sometimes checklists)

- Exploratory testing is most useful when there are few known specifications and/or there is a pressing timeline for testing




- Estimated defect density is reached -> belongs to the exit criteria


- three-point estimation technique: E = (optimistic + 4*most likely + pessimistic)/6


- Burndown charts are a graphical representation of work left to do versus time remaining. They are updated daily, so they can continuously show the work progress






- Early and frequent feedback allows for the early communication of potential quality problems

- Regularly conducted retrospectives, when appropriate follow up activities occur, are critical to continual improvement of development and testing


- The test basis for acceptance testing is the user’s business needs (1D)  Communication between components is tested during component integration testing (2B)  Failures in logic can be found during component testing (3A)  Business rules are the test basis for system testing (4C


- three typical integration strategies:   Big-bang integration . Bottom-up integration . Top-down integration 

 - If clusters of defects are identified (areas of the system containing more defects than average), then testing effort should be focused on these areas

- Testers will work closely with business representatives to ensure that the desired quality levels are achieved. This includes supporting and collaborating with them to help them create suitable acceptance tests. 

- test levels for v-model: component, system


- Testing can show the presence of defects but cannot prove their absence, which makes it impossible to know if you have caught all the bugs. Further, the impossibility of exhaustive testing makes it impossible for you to catch all the bugs


- Exhaustive testing, all combinations of inputs and preconditions, is not feasible unless the software is trivially simple.Otherwise it would take too long and might not even be possible




- defining test conditions  is a part of test analysis


- The test management role is mainly focused on the activities of test planning, test monitoring and control and test completion. The testing role is mainly focused on the activities of test analysis, test design, test implementation and test execution

- It is important that testers are involved from the beginning of the software development lifecycle (SDLC). It will increase understanding of design decisions and will detect defects early.


- If all test cases are linked with requirements, then whenever a new test case (with traceability) is added, it is possible to see if any previously uncovered requirements are covered by the new test case


- project objectives: Organisational . Supplier . Technical 




- COTS: commericial off the shelf 



- Exploratory tests should be performed by experienced testers with knowledge of similar applications and technologies.

1. Risk-based testing is an example of an analytical approach, where tests are designed and prioritized based on the level of risk 2. The control algorithms is checked against industry-specific standard of the energy saving regulation. 3. This type of test strategy is driven primarily by the advice, guidance, or instructions of stakeholders, business domain experts, or technology experts, who may be outside the test team or outside the organization itself 4. Exploratory testing is a common technique employed in reactive strategies


 
- Defect - An imperfection or deficiency in a work product where it does not meet its requirements or specifications. Defects can be found in a test script, in source code, or in a supporting artifact such as a build file.



- The metrics-based approach: estimating the testing effort based on metrics of former similar projects or based on typical values

- Accepting invalid inputs is a failure




- Performing the impact analysis of a change will help selecting the right test cases for regression testing
- benefit of independence testing: When specifications contain ambiguities and inconsistencies, assumptions are made on their interpretation, and an independent tester can be useful in questioning those assumptions and the interpretation made by the developer
- a list of the work products produced in the SDLC:
Business requirements
Schedule
Test budget
User stories and their acceptance criteria
- 3-point boundary value analysis (BVA)
- Usually, component testing and component integration testing are automated using APIbased tools
- For system testing and acceptance testing, the automated tests are typically created using GUI-based tools
- One cannot say anything about risk likelihood. Risk impact and risk likelihood are independent.
- example of how product risk analysis influences thoroughness and scope of testing: Risk assessment revealed a very high level of performance risks, so it was decided to perform detailed performance efficiency testing early in the SDLC
- common metrics used for reporting on the quality level of the test object:
1) Number of defects found during system testing
2) Number of defects found divided by the size of a work product



- Alphanumeric is a combination of alphabets and numbers


- the combination of these two viewpoints determines the four quadrants:

Quadrant Q1:
technology facing, support the team
contains component & component integration tests
these tests should be automated & included in the CI process
Quadrant Q2:
business facing, support the team
contains functional tests, examples, user story tests, user experience prototypes, API testing, & simulations
these tests check the acceptance criteria and can be manual or automated
Quadrant Q3:
business facing, critique the product
contains exploratory testing, usability testing, user acceptance testing
these tests are user-oriented and often manual
Quadrant Q4:
technology facing, critique the product
contains smoke tests and non-functional tests (except usability tests)
these tests are often automated


- A tester finds that a test needs to be redesigned and retested during implementation and execution, he would then add another test analysis and design activity before retesting.

- During development, versions of the software are created called work products, then various testing activities can be performed on these early versions



1) Analytical approaches: Such as risk-based testing where testing is directed to areas of greatest risk (see later in this section for an overview of risk-based testing).

2) Model-based approaches: Such as stochastic testing using statistical information about failure rates (such as reliability growth models) or usage (such as operational profiles).

3) Methodical approaches: Such as failure-based (including error guessing and fault attacks), checklist based and quality-characteristic based.

4) Standard-compliant approaches: As specified by industry-specific standards such as The Railway Signaling standards (which define the levels of testing required) or the MISRA (which defines how to design, build and test reliable software for the motor industry).

5) Process-compliant approaches: These adhere to the processes developed for use with the various agile methodologies or traditional waterfall approaches.

6) Dynamic and heuristic approaches: Such as exploratory testing where testing is more reactive to events than pre-planned, and where execution and evaluation are concurrent tasks.

7) Consultative approaches: Such as those where test coverage is driven primarily by the advice and guidance of technology and/or business domain experts outside or within the test team.

8) Regression-averse approaches: Such as those that include reuse of existing test material, extensive automation of functional regression tests, and standard test suites.



- static analysis tools would be used by designers while software modeling is taking place.

- Team is not list under the code of ethics document stated by the ISTQB


- need for good management while using static analysis by tools: Fewer problems during test execution

- Test case: a set of input values, expected results, execution pre and post-conditions, made for an objective or test condition.


- Equivalence partitioning: software inputs are devided into groups that would exhibit similar behaviours

- Fault attack is a systematic approach



-  Dynamic/Heuristic approach uses exloratory testing where testing is reactive to events.

- Test Data: the input information used in a test to produce an expected output from the system.

- Decision table is used for capture system requirements containing logical conditions.

  
- In Agile software development, test management activities that span multiple teams are handled by a test manager outside the team, while some test management tasks are handled by the team itself


- Independent testers will find defects due to their different technical perspective from developers, but their independence may lead to an adversarial relationship with the developers


- Shift-left emphasizes the importance of starting testing earlier
in the software development lifecycle (SDLC). Implementing shift-left
testing necessitates additional training, and increased effort and costs
during the early stages of the SDLC, nevertheless, overall savings
should be higher. -> Where cost-effective, test activities are moved to be performed earlier in the software
development lifecycle (SDLC) to reduce the total cost of quality by reducing the number of
defects found later in the SDLC





- checklist based testing can rsult in increased coverage: 
- Two testers designing and executing tests based on the same high-level checklist items will
typically perform the testing in slightly different ways


- test pyramid model show thath test may have diifferent granularity

- Testing quadrants describe the degree of granularity of individual test types performed at
each test level

- The assessed risk level helps us to select the rigor of testing.  This is an example of how risk analysis influences the thoroughness and scope of testing



 Risk impact = Risk level / Risk likelihood
