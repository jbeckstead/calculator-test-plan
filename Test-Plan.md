# TI-108 Calculator
## Test Plan

Prepared by: Jared Beckstead
_10/09/2018_

![TI-108 Image](./calc-image.jpeg)

> Above is an image of the calucator that is to be used for this Test Plan.

### _Table of Contents_

### **1.0 Introduction**
The purpose of this document is to describe the overall test plan and strategy for testing the TI-108 calculator.
- **_1.1 Scope_**
    - The overall purpose of testing is to ensure that the TI-108 calculator meets all of its technical and functional requirements. The approach described in this document provides the framework for all testing related to this product. This document will also be updated as required throughout the test.
- **_1.2 References_**  
    
    - Owners Manual.
    - https://en.wikipedia.org/wiki/TI-108
    - https://education.ti.com/en/products/calculators/elementary-calculators/ti-108


### **2.0 Requirements for Test**
- **2.1 _Unit testing_**  
    
    Criteria-   
    
    - Have Test Plan document available. Follow instructions in sub-section 3.1 of the (3.0) Test Strategy, and Section 8.0 Test Cases to complete and/or validate every test.
    - Validate that each feature performs as intended, individually. See section 6.0 to see what features need to be tested.
    - Validate that each required feature performs as intended in every possible combination.

    Tools-  

    - TI-108 Calculator Simulator and/or physical TI-108 Calculator.

- **2.2 _Integration Testing_**
    
    Criteria-  

    - If any "red flags" are raised while validating any function of a feature, isolate are far as you can the building blocks of the issue occurred.
    - Full regression test from the point of stopping to the beggining must be completed after after testing the integrated part of the system where the issue occurred.
    - See sections 3.2 and 8.0 for further information and instructions. 2.5 and 3.5 for further information or instructions for any regression tests needed.

    Tools-  

    - TI-108 Calculator Simulator and/or physical TI-108 Calculator.

- **2.3 _Performance and Stress Testing_**
    
    Criteria-  

    - Must be tested to withstand harsh temperature environments from 0° F to 130° F.
    - Each required feature button must be pressed 100,000 times, either by automated machine or person. (Must be test on a physical TI-108 calculator.)
    - See sections 3.3 and 8.0 for further information and instructions.

    Tools-  

    - TI-108 Calculator Simulator and/or physical TI-108 Calculator.
    - Automated machine or person.
    - Drawer/Desk.

- **2.4 _User Acceptance Testing (UAT)_**
    
    Criteria-  

    - Once full final System test/Regression test is completed. MOdels

    Tools-  

    - TI-108 Calculator Simulator and/or physical TI-108 Calculator.

- **2.5 _Automated Regression Testing_**
    
     Criteria-  

    - Once the initial unit tests are completed for a feature (addition, multiplication, etc.), Complete a regression going from the last steps occurred all the way back to the beginning.
    - After each feature has validated that it functions correctly on its own, all the required features must complete a full regression test to validate that each function works together properly. See sections 3.5 and 8.0 for further information and instructions.

    Tools-  

    - TI-108 Calculator Simulator and/or physical TI-108 Calculator.

### **3.0 Testing Startegy**
- **3.1 _Unit Testing_**
    
    - 3.1.1 Test Objective  
    
        Validate each of the required features of the software so that they perform as intended.
    
    - 3.1.2 Technique  

        Follow instructions in section 8.0 Test Cases.

    - 3.1.3 Completion Criteria  

        Test each required feature individually and every possible combination. 

    - 3.1.4 Special Considerations  

        Test each feature while the calculator is turned off. Test each feature so when the solar-power bar is being obstructed from recieving solar-power from the sun.
        May also need multiple physical calculators if unable to acquire a simulator.

- **3.2 _Integration Testing_**
    
    - 3.2.1 Test Objective  

    - 3.2.2 Technique  

    - 3.2.3 Completion Criteria  

    - 3.2.4 Special Considerations  

- **3.3 _Performance and Stress Testing_**
    - 3.3.1 Test Objective  

    - 3.3.2 Technique  

    - 3.3.3 Completion Criteria  

    - 3.3.4 Special Considerations  

- **3.4 _User Acceptance Testing_**
    - 3.4.1 Test Objective  

    - 3.4.2 Technique  

    - 3.4.3 Completion Criteria  

    - 3.4.4 Special Considerations  

- **3.5 _Automated Regression Testing_**
    - 3.5.1 Test Objective  

    - 3.5.2 Technique  

    - 3.5.3 Completion Criteria  

    - 3.5.4 Special Considerations  

- **3.6 _Beta Testing_**
    - 3.6.1 Test Objective  

    - 3.6.2 Technique  

    - 3.6.3 Completion Criteria  

    - 3.6.4 Special Considerations  

### **4.0 Environment requirements**

- Freezer (that can go below 0° F and run efficiently at that tempertature for 1 year)
- Heated area that can reach temperatures over 130° F and maintain tempertature for a year.

### **5.0 Test Schedules**


### **6.0 Features to be tested**
1. On/Clear
2. Addition
3. Subtraction
4. Multiplication
5. Division
6. Decimal Point
7. 0 thru 9 Numerals
8. Equal Sign

### **7.0 Features not to be tested**
Ignore the six red buttons above the Numerals (Three memory buttons and three advanced math buttons).

### **8.0 Test Cases**
    What questions do I want the cases to answer? How and what am I solving?
### **9.0 Test Scenarios**


### **10.0 Assumptions**


### **11.0 Suspension Criteria**
    When to stop testing.