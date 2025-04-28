# Test Plan (Manual Testing Amazon) 
## Authors: Tatarintev Denis 
## Introduction 
This is the test plan made by Tatarintev Denis intentionally for upgrading Manual Testing skills by working with e-commerce web application:   
**Amazon** [[https://www.amazon.com/ref=nav_logo]]   
Here will be covered most important features of the application and covered the valuable tests for app. 

## Approach 
This project is implemented in Waterfall Model (SDLC) which means all tasks are providen step by step. This project provide only Black Box testing with no access for code. Will be included Test Design Techniques such as Boundary Value Analysis, Equivalence Class Partition and etc. Each Test Case will also be noted as Positive, Negative or no positivity quility depending on input it gets.

### Types of testing
- Functional (include positive, negative and no positivity tests)
- Non-Functional (include only positive and no positivity tests)

### Subtypes of testing
- Smoke Testing
- Exploratory Testing
- Load Testing
- Localization Testing
- Accessibility Testing 

### Implementation Steps
**Step 1**: Creation of Excel Tables for every type and subtype of testing, such as Localization, Smoke testing and others from the list. The queue of enwriting of test cases is not important and will be modified during the project implementation.  
**Step 2**: Smoke Testing - verification of core functionality of the product. Here is presented the whole list of smoke test items that will include both positive and negative approach (if it is possible)
#### Smoke Test items:
- Registration 
- Log In 
- Product Search 
- Product Filtering 
- Cart Management 
- Checkout Process (without payment)

**Step 3**: Exploratory Testing - no verification scenario, just searching and roaming through application for a period of time  
**Step 4**: Load Testing - verification of how fast is load speed for several pages and actions on the website  
**Step 5** Localization Testing - verification of posibility to change the country and region, verification of translation of basic text lines on different languages, verification of money currency and measurement systems  
**Step 6** Accessibility Testing - verification if application works properly and satisfies needs of all people, including those with disabilities

## Item pass/fail criteria 
**Pass**: the application works as it is expeted

**Fail**: the applcation behaviour is wrong and not as expected (Error Messages, Bad Performancing) 

### Bug Reporting Procedure
The bugs are reported right after all test cases were implemented.  
Here is the sctructure of bug reporting:  
1. **Title** (outline the defect)
2. **ID** (related to the test case)
3. **Type** (to outline the problem)
4. **Description** (is not necessary, only if needed) 
5. **Steps to Reproduce** (for managing problem)
6. **Expected Result** (what should system work like)
7. **Actual Result** (what we get in reality)
8. **Priority**  
P1 = High - has to be changed as soon as possible  
P2 = Medium - has to be changed, but not immediately  
P3 = Low - can be changed when other problems are resolved
9. **Severity**  
S1 = Critical - is crushing the whole application work  
S2 = Major - has a big impact on the system, but it can still work  
S3 = Minor - has a small impact on the system, or grammar  
S4 = Cosmetic - impacts only on the system view
10. **Environment** (include Browser Version and Web Application Version)
11. **Logs** (Screenshots)

### Summary Reporting
Summary Report is done at the end of the project and is a good way to track the statistics.  
Here is the template of summary report:
1. **Who worked on project** 
2. **Summary** (progress/regress, critical problems)
3. **Testing Process Description** (Methods, Technics and Tools)
4. **Testing Time Table** (For each coworker description of duties)
5. **Recommendations** (Status of the project and the tested system)
6. **Bug Statistics** (a table with status of bugs, quantity and their priority)
7. **New Bugs Found** (ID and Name)

### Test Environment and Tools 
Windows 10 - Google Chrome  
Windows 11 - Opera GX  
Android Mobile OS - Google Chrome

### Schedule 
**Time**: 2 weeks (14 days) (May be fixed)  
**Start Point**: 15.04.2025  
**End Point**: 28.04.2025 


