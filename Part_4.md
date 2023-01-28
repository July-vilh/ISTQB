## TEST PLANNING ##

!!!!!!!!! THE TEST DESIGN AND THE TEST IMPLEMENTATION ARE OFTEN COMBINED !!!!!!!!!!!!! 

Defining oblectives of testing and the approaches to meet these objectives.

- DEFINING = Определение

- OBJECTIVE = цель

- APPROACHE = подход
__________

1. Project plan about how we finished our project

2. Test plan considering only testing (this case only around testing)

Test leader/ test manager writting test planning

Test planning during the whole testing process (not only first step)
___________

## TEST MONITORING AND CONTROL ##

- COMPARISON = Сравнение

- DEFINED = Определенных

- TAKING ACTIONS = принятие мер

- TO MEET THE OBJECTIVES = для достижения ...

### Test Monitoring and Control ###

#### 1. Monitoring is on-going comparison of actual progress against the test plan using any test monitoring defined in the test plan. ####

I write 1000 test-cases each month. I planning write 2000 test cases. And I comparison actual result against test plan.

#### 2. Taking actions  to meet the objectives of the test plan. ####

#### 3. Supported by Exit Criteria (Criteria, that define: we finished this activity) or DOD (from Agile): Definition of Done. It is all about Control Activity. ####

Control is based on monitoring activities. In order to monitor my progress take the correct actions.

In the control activities consist Exit Criteria.

#### 4. Test progress against the plan is communicated to stakeholders in test progress reports. ####

____________________

## TEST ANALYSIS ##

Through are the whole project.

- Answer the question "What to test"

### ANALYZE THE TEST BASIS: ###

#### 1. Requirements Specifications ####

#### 2. Design ####

#### 3. Code ####

#### 4. Risk Analysis Report ####

- Define and Prioritize Test Condition

- Capturing bi-directional traceability

Traceability between 2 works products means that those 2 works products are related to eaсh other.

We need to connect req. and conditions .

If I have connect between req. and cond. by bi-directional traceability then Any change in req. will give me a type of warnings "those conditions need be change"

If I didn't have connect between req. and cond. it will be hard to connect them and warnings don't will be come.
_____
Requirement Traceability matrix maps the user requirements with the test cases. In simple words, the matrix helps in determining if all the requirements have been covered(i.e there are test cases which can be traced back to the requirements).

There are 3 types of RTM:

Forward:Requirements->Test Cases

Backward: Test Cases->Requirements

Bi-directional: Forward+Backward

Bidirectional traceability is the ability to trace both forward and backward (i.e., from requirements to end products and from end product back to requirements).

It means tracing the code from requirements and vice-versa throughout a Software Development Life Cycle (SDLC).

When you are in the course of your project, your fundamental aim would be to ensure that each and every requirement is translated into code. Tracing right from the requirements through the architecture and design, to the code, to ensure that the objectives or more precisely requirements have been met is referred to as the process of establishing Forward Tracea

#### TEST SCENARIO = TEST CONDITION ####

1. From the req. I can know which test scenario are testing that

2. From the test scenario I can know which test cases are testing that

If I change RE_01 (requirement) I need to change TS_02 (test case) and TC_O5, TC_07, TC_09


- Test condition can be used as objectives in the Test Charters

It means: In some cases we don,t write test cases (we write only conditions, document that caleed a test charter)

- CHARTER = испытательный
________________

## TEST DESIGH ##

### 1. HOW to test? ###

### 2. Design and prioritize test cases ###

### 3. Identify test data (идентифицировать тестовые данные) ###

### 4. Design test environment ###

TEST ENVIRONMENT CONSISTS:

- SOFTWARE

- HARDWARE

- NETWORK


EX.: AMAZON

- q.1 = WHAT IS THE SOFTWARE THAT THIS TEST APPLICATION WILL BE TESTED ON (Android 10.0 / iOS 4.0)

- q.2 = WNAT IS THE HARDWARE THAT THIS APPLICATION WILL BE TESTED ON (POCO X3 NFC with 24 mPxl camera, 40 gB memory etc.)

- q.3 = WHAT TYPE OF NETWORK THAT THIS IEST APPLICATION WILL BE TESTED ON (4G, 5G, 3G)

__________________

## TEST IMPLEMENTATION (РЕАЛИЗАЦИЯ) ##

- ARRANGE = УПОРЯДОЧИВАТЬ

- SCHEDULE = ГРАФИК

- SUIT = НАБОР

- TEST SUIT = like folder that contain test cases

### 1. Do we now have everything in place to run the tests? Есть ли у нас теперь все необходимое для проведения тестов? ###

### 2. Develop and prioritize test procedures ###

### 3. Create test suites, arrange them in test execution schedule / Создавайте наборы тестов, упорядочивайте их по расписанию выполнения тестов ###

### 4. Build test environment ###

____________________

## TEST EXECUTION (ВЫПОЛНЕНИЕ) ##

- CONFIRMATION (от CONFIRM) = ПОДТВЕРЖДЕНИЕ

- DISCRIPTION = ОПИСАНИЕ

- IMPACT = ВЛИЯНИЕ

____

### 1. RUN THE TEST SUITES ###

it's mean that we run the test cases in our test suites

### 2. COMPARE ACTUAL RESULT WITH EXPECTED RESULT ###

if they are the same = this test cases PASSED

if they are different = this test cases FAILED

### 3. REPORT DEFECTS ###

CONTAINS: 

- 1) BUG ID (ID number, Name, Reporter, Submit Date)

- 2) BUG OVERVIEW (Summary, URL, Screenshot)

- 3) ENVIRONMENT (Platform, Operating system, Browser(

- 4) BUG DETAILS (Steps to reproduce, Expected result, Actual result, Discription)

- 5) BUG TRACKING (Severity, Assign to, Priority)

#### PRIORITY = HOW IMPORTANT IS THIS DEFECT TO THE BUSINESS (IN JIRA: HIGH, LOW, etc.) ####

#### SEVERITY = is not depending on the business if severity f.ex. major = it means a high impact on the user ####

- 6) NOTES

_________

### 4. CONFIRMATION AND REGRESSION TESTING ###

_________________________

## TEST COMPLETION (ЗАВЕРШЕНИЕ) ##

Steps that come after test execution

We need to make a decision: we perform enough testing in this part of the project or not

- OCCURS = ПРОИСХОДИТ

- MILESTONES = ОСНОВНЫЕ ЭТАПЫ

- HAND OVER = ПЕРЕДАТЬ

- DEFFERED DEFECT = ОТЛОЖЕННЫЙ БАГ

_____

### 1) Collect data from completed test activities ###

Сбор данных из завершенных тестовых действий

collect information based on the execution (hoe many cases did we find, how many defects did we find, how many defects are solved, what about priority and severity of each defect

### 2) Occurs at project milestones ###

Происходит на основных этапах проекта

### 3) Check Defects Reports ###

DEFFERED DEFECTS = unsolved defects (not be solve now and will be solved letter (next week or mounth

### 4) Create test summary reports (what nappenes in those test progress reports) ###

- the same as the test progress report

- having in the end of activity

! if I create unit tests for app (for 1 mounth): test progress reports can happened each week of this mounth

! but test summary report happenes in the end of this mounth

SUMMARY REPORT make be not only in test completion but also make be in TEST MONITORING AND CONTROL

### 5) Hand over the testware ###

Передать тестовое программное обеспечение

ONLY FOR BIG COMPANY

_______________________

## 1. TEST PLANNING = TEST PLANS ##

## 2. TEST MONITORING AND CONTROL = TEST PROGRESS ##

## 3. TEST ANALYSIS = TEST CONDITIONS - TEST CHARTERS ##

## 4. TEST DESIGN = TEST CASES - TEST DATA ##

## 5. TEST IMPLEMENTATION = TEST PROCEDURES - TEST SUITES - TEST EXECUTION SCHEDULE ##

## 6. TEST EXECUTION = STATUS OF TEST DEFECTS - DEFECT REPORTS ##

## 7. TEST COMPLETION = TEST SUMMARY REPORTS - CHANGE REQUESTS ##

____________________

## Tester's Mindset ##

### 1. Curiosity = Любопытство ### 

### 2. Professional Pessimism ### 

### 3. Attention to Detail ### 

### 4. Critical Eye ### 

________________________________

the customer complaints  = ЖАЛОБЫ КЛИЕНТОВ (AN EFFECT) !!!!!!!!

insufficient = НЕДОСТАТОЧНЫЙ !!!!!!!!!!!
