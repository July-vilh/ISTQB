## Software testing: ##

### 1.Validation (we build the right product) ###

This T-shirt is effect for me (comfortable, beautiful)

Делаем ХОРОШИЙ/ПРАВИЛЬНЫЙ продукт

### 2.Verification (we build the product right) ###

We need the SPECIFICATION about our product: right/not right.

About T-Shirt: this T-Shirt blue/not blue
size of T-Shirt

Мы делаем продукт ХОРОШО
____

Facebook

1. Validation

- Is the user satisfaction or not

- Take a foto

2. Verification

- Amount about memory size of application

- Security

## Goals (цели): ##

### 1. Work-product evoluation ###

Anything what we are developing (requirements conseder work-product, design conseder work product). Include any errors

### 2. Requirements Fulfillment (выполнение) ###

Client gives us some requirements - and tester сравнивает конечный продукт с requirements from client
___
Evaluation = оценка

Fulfillment = выполнение
____
### 3 goal. Building confidence (укрепление доверия) ###

Sometimes we test no to find defect. Testing for know this working

NP, I recording now video and before recording I checked camera, microphone, etc. for buiding confidence
___
### 4.Providing information to Stakeholder (предоставление информации заинтересованным сторонам) ###

manager ask tester what about our product and tester answer truth about status of product to manager and than manager tell this information to client
___
### 5. Preventing defects (предотвращение дефектов) ###

Before defects will be found (before defect happened).

Tester review that the requirements need more informations.

And when tester will be know more information about requirements it helps to preventing defects.
___
### 6. Finding defects ###

Tester finding defects - report them - to developer
___
### 7. Reduce risk (уменьшение рисков) ###

When we preventing defects - reduce risk

If I found defect in code this reduce risk in integration/system testing to find defects.
___
### 8. Compliance with Laws (соблюдение законов) ###

Contract with the client
___
### 9. Objectives (goals) may vary (Цели могут быть разными) ###

- Depending on who is testing

- Depending what is he testing
____________________________

## Test levels ##

### 1. Unit testing ###

### 2. Integration testing ###

### 3. System testing ###

### 4. Acceptance testing ###


### Testing/Debugging/Confirmation testing ###

Confirmation testing (Re-testing) - подтверждающее тестирование = тестирование, при котором выполняются тестовые сценарии которые были не пройдены при последнем запуске с целью подтвердить успешность исправления

- Re-testing = to reproduce same steps that leads (приводят) to bugs

When this bug is exist (существует) - tester re-open this bug again

When this bug is not exist - all is good

___

Responsibility = ответственность

___

Testing (resp = tester) - Debugging (resp = developer) - Re-testing (resp = tester)

BUT

In Agile development testers may be involved in debugging and components testing

_________________________

### 1. Testing = tester send bugreport to developer ###

### 2. Debugging = to remove the bug. Developer remove the bug (opennind the code and fix) ###

### 3. Confirmation testing (Re-testing) ###

### Debugging = identify the cause of a defect, reparing the code and checking the fix is correct = a developer finds and fixes a defect ###

- Dynamic testing shows failures caused by defects.

- Debugging finds, analyzes, and removes the causes of failures in the software.

_______
CONTRIBUTION = ВКЛАД 

### Tester's Contribution (вклад) to success ###

#### 1. Rewiev the requirements. ####

Reduce the risk of incorrect untestable functionality being developed.

#### 2. Review the design. ####

Reduce the risk of design defects and enable (включение) tests to be identified at an early stage.

#### 3. Review the code (testers work closely with developers) ####

Reduce the risk of defects within (внутри) the code and the tests.

- static way (which language, dicumentation, standarts)

- dynamic way (White Box Technique, Unit testing)

#### 4. Review and tests the final product (verify and validate the software) ####

_________________

- ADHERENCE TO PROPER PROCESSES = соблюдение надлежащих процессов

- DEFECT PREVENTION = предотвращение дефектов

___

## QA ##

is typically focused on adherence to proper processes

Proper processes - Work product higher - defect prevention

- ACHIEVEMENT = достижение

- APPROPRIATE = соответствующий

## QC ##

involves various activities, including test activities that support the achievement of appropriate levels of quality

- REGARDS = ОТНОСИТСЯ

### QC regards the product ###

### QA regards the process ###

___

- 1. QA about PROCESS. If we QA apply in correct way - we are prevent defects

- 2. QC abouT PRODUCT. If we QC apply in correct way - we will find not prevent defects.

__

!!! QC is a part of QA (is a part of process (QA))

can defects the failures that might have been missed and support the process of removing the defects that caused the failures (debugging)


_______________

## 1. Error/ Mistake ##

- developer writting code and then make mistake while writting code

- product owner writting requirements and then make mistake in the requirements

___

## 2. Defects (Bug/ Fault) ##

Defect is a result of the error.

Developer make mistake while writting code/ This error caused a defect of the code

Mistakes can lead to the introduction of a defect.

A requirements error can lead to a requirements defect - then developer make mistake in the code because requirements have error - as a result = a defect in the code
____

## 3. Failure ##

= the software isn't apply to perform this functional (программное обеспечение не применяется для выполнения этой функции)

When I click on the login and button doesn't working = it is a failure.

NOT ALL DEFECTS CAUSED FAILURES.

ERROR/MISTAKE - DEFECT - FAILURE OR NOT FAILURE

___

## WHY DO ERRORS HAPPEN? ##

### 1. TIME PRESSURE = НЕХВАТКА ВРЕМЕНИ ###

### 2. HUMAN FALLIBILITY = ЧЕЛОВЕЧЕСКАЯ ПОДВЕРЖЕННОСТЬ ОШИБКАМ ###

### 3. LACK OF EXPERIENCE = НЕДОСТАТОК ОПЫТА ###

### 4. MISCOMMUNICATION between team members ###

### 5. COMPLEXITY OF WORK PRODUCT = СЛОЖНОСТЬ РАБОЧЕГО ПРОДУКТА ###

### 6. SYSTEM INTERACTIONS = ВЗАИМОДЕЙСТВИЕ С СИСТЕМОЙ ###

### 7. NEW TECHNOLOGIES ###

### 8. ENVIROMENTAL CONDITIONS ###

________________________

### Errores of testers: ###

#### 1. False Positive ####

Means the risk something

- Finding the defects 

- We found a defect, but we were wrong/false (it is not a defect)

#### 2. False Negative ####

Means the risk nothing 

- We didn't find a defect 

- We didn't find a defect, but there is a defect in functionality (ex. the end customer find a defect)
____

Root cause = первопричинный (изначальный)

Removed = устранение

Decreased = уменьшение

The occurence = вероятность возникновения

contribution = способствовать

___

1. Root cause (глосс.) = a source of a defect such that if it is removed (устранение), the occurence (вероятность возникновения) of the defect type is decreased (уменьшается)

2. The Root causes (ISTQB syll.) of defects are the earliest actions or conditions that contributed (способствовало) to creating the defects

improvement = усовершенствование

prevent = предотвратить 

significate = значительный

___

Root cause analysis can lead to process improvents that prevent a significant number of future defects from being introduced

_______________________

hkjhkjhkhoi


