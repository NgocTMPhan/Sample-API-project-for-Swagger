# Katalon Studio Samples: Simple API project for Swagger
Katalon Studio is a free and easy-to-use automated functional and regression testing platform. It provides users the ability to implement full automated testing solutions for their application projects with minimal engineering and programming skill requirements.
______

The **Sample API project for Swagger*** perform API automation test on Swagger using Katalon Studio. The examples in this project very common test cases.

# Getting Started
These instruction will get you a copy of the project up and running on your local machine.

# Prerequisites
- [Katalon Studio](https://www.katalon.com/) - [Installation and Setup](https://docs.katalon.com/x/HwAM)
- Permission access to [Jira System](https://katalon.atlassian.net) (provided in the sample code)
- Application Under Test (AUT):using Swagger Petstore: http://petstore.swagger.io/

### Setting Up
- [Check out](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository) the code from this .git
- [Open the project](https://docs.katalon.com/katalon-studio/docs/manage-test-project.html) from Katalon Studio
- Import swagger by using url or file location: 
### Send request with simple case
## GET METHOD
#Story#: Find Pets by status
- After import successfully, user able to find pets by status. First, user must verify what parameter work with it? how many status in this data, refer this link at find pests by status: https://petstore.swagger.io/v2/swagger.json
- Add parameter with value choose at enum( available, pending, sold)

### Story: Create issue with defined information
```Gherkin     
   User story
        As a Jira user, I would like to be able to create a new issue with defined information via web service, so that I could manage my issues without logging in Jira web application
     
      Feature: Create issue
          Scenario: Create issue with defined information successfully
	    Given The web serice is available
	    When I send a request to create issue with defined information
	    Then The issue is created successfully in the system
```
## Test Cases	
    - Simple Test Cases
    - Advance Test Cases
    - Data-driven Test Cases
    - Tips and Tricks Test Cases
    - BDD Cucumber Test Cases

### Simple Test Cases
Test cases at this section will help the users to understand:
- How to create simple API testing with hard coding test data
- How to create a RESTful Web service object at Object Repository with different method: 
  - GET
  - POST
  - PUT
  - DELETE
- How to use simple built-in keywords to 
  - Send request
  - Verify response code
  - Verify response information

### Data-driven Test cases
Data-driven approach is important to API testing, since it helps users testing a Web service endpoint with different dataset without cloning the test case. Test cases in this section demonstrate:
- How to create test cases with input parameters
- How to use data-file in test suites
- How to execute test cases with data-file as a data-driven approach

### Tips & Tricks
Tips & Tricks part contains samples solving common questions from users:
- Parameterize:
  - Parameterize request body
  - Parameterize authentication
  - Parameterize request query
  - Parameterize request path
- RequestObject
- ResponseObject
- Verification
- Authentication

### BDD Cucumber Test Cases
From version 5.7, Katalon Studio has supported native BDD Cucumber testing approach. The example in this section show:
- How to create test features
- How to create test scenario, test scenario out-line
- How to implement step definition
- How to execute BDD Cucumber features.
______
 ### Execute a Test Suite with Data-Driven
 ![Execute a test suite with data-driven](https://github.com/katalon-studio-samples/jira-api-tests/blob/master/Tutorials/Figures/Execute%20a%20test%20suite%20with%20data%20driven.png?raw=true)
 
 This example demonstrates how to apply data-driven approach to test execution with Katalon Studio. 
1. Select the test suite
2. Select the test case you want to apply data-driven approach
3. Select data file
7. Bind test data and test case's parameters
 
 ### Execute a Test Suite
 ![Execute a test collection](https://github.com/katalon-studio-samples/jira-api-tests/blob/master/Tutorials/Figures/Execute%20a%20test%20suite.png?raw=true)
 
 This example demonstrates how to execute a test suite collection.
1. Select the Test suite
2. Add test cases into the test suite 
3. Execute the test suite

## See Also
Update configurations for integration: [Jira](https://docs.katalon.com/x/7oEw), [Katalon Analytics](https://docs.katalon.com/x/KRhO)

Katalon Documentation: http://docs.katalon.com/, especially some [Tips and Tricks](https://docs.katalon.com/x/PgXR) to run a successful automation test. 

Katalon Forum: https://forum.katalon.com/

Katalon Business Support: https://www.katalon.com/support-service-options/
