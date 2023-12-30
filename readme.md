# Portfolio
- [About me](#about-me)
- [CV](#cv)
- [Skills](#skills)
- [Tools](#tools)
- [Education](#education)
- [Examples of my work](#examples-of-my-work)
  * [Test case and work in Qase](#test-case-and-work-in-Qase)
  * [Bug report and work in Jira](#bug-report-and-work-in-jira)
  * [Test run in Postman](#test-run-in-Postman)
  * [Scenario in framework on CucumberJs](#scenario-in-framework-on-cucumberjs)
  * [Implements function click](#implements-function-click)
- [Books I have read](#books-i-have-read)

## About me

I'm a QA Engineer who has 9 monthes experience in manual QA engineer for web applications and 6 monthes in UI/API authomated testing. 

I started my IT journey with Manual Testing, working on web apps in blogging, education, and marketing. I used Jira & Qase for managing test documentation.

I also have some experience in Automation testing, where I worked on tests for an e-commerce platform and using NodeJS frameworks: CucumberJS, WebDriver IO, and Axios.

Additionally, I'm good at keeping things organized, familiar with the Agile way of working using SCRUM and Kanban, and I understand concepts of REST API, OOP, JSON, XML, HTML, and CSS.

I enjoy learning, and my focus is on improving in testing and quality assurance. I'm looking for opportunities to develop and contribute my skills.

## CV
You can download my CV as [a PDF from my Google Drive](CV.pdf).

## Skills

You can find examples of the described skills in the [Examples of my work](#examples-of-my-work) section.

__Technical experience:__
- Adding/editing UI/API tests in custom NodeJS BDD automation framework based on CucumberJS, WebDriverIO and Axios for e-commerce product
- Writing test documentation for blogging, educational and marketing web applications:
   * Test cases
   * Bug reports
   * Check-lists
   * Test plans
- Test-design techniques usage:
   * Equivalence Partitioning
   * Boundary Value Analysis
   * Ad-hoc Testing etc
- API testing using Postman
- API structure analysis using documentation in Swagger
- Working with Jira, Qase for adding and editing test cases, bug reports, test plans
  
__Strengths:__
- Accuracy and attention to details
- Analytical Thinking and problem solving skills
- Team-oriented mindset with ability to unite people to achieve a goal

## Tools

- NodeJS frameworks: CucumberJS, WebDriverIO, Axios
- Postman
- GitBash
- MS SQL questing for testing purposes testing e-commerece
- Visual Studio Code (for IDE) as an editor with syntax highlighting for the Gherkin        language, which simplifies managment of feature files  * Jira
- Qase
- Jenkins pipelines usage for:
  * Test framework versioning on GitHub
  * Running framework  tests for e-commerce product

## Education
  
- Bachelor degree in system engineer (Vinnytsia National Technical University)
- 9-month course with personal mentoring on theory and practice of manual testing based on real web applications
- 6-month course with personal mentoring  on theory and practice of automation testing using a custom framework based on CucumberJS, WebDriver IO and Axios, testing the UI and API of the application after BDD
- Основи тестування програмного забезпечення (Lviv IT School) [Prometeus course](https://prometheus.org.ua/course/course-v1:LITS+115+2017_T4)
- SQL Basics courses [SQLBolt](https://sqlbolt.com/) 
- JavaScript with Sololern [Sololearn](https://www.sololearn.com/en/learn/languages/javascript)

## Examples of my work

### Test cases and work in Qase: 
   
- Test case to check how the main page opens for a logged-in user in the  Blog application:
 * Test Case Name  
 * Preconditions
 * Steps to Reproduce
 * Expected Result
 * Actual Result
 * Priority
 * Environment
 
![test cases](images/Qase.gif)

### Bug report and work in Jira

--An example of a bug where bold text is not saved when saving a post in the Quasigalley Blog application
 * Title
 * Bug Report ID
 * Description
 * Steps to Reproduce
 * Expected Result
 * Actual Result
 * Environment
 * Attachments 
 * Priority
 * Tester
 * Status

![bug report](images/Jira.gif)


### Test run in Postman:

- Test run in Postman in QuizSpike application

![For example test run API QuizSpike application](images/TestRun.png)

![Headers from POST UpdateProfile](images/Heders.png)

![Pre-requestScript from POST UpdateProfile](images/Pre-requestScript.png)

![Body from POST UpdateProfile](images/Body.png)

![Request-Responce from POST UpdateProfile](images/Request-Responce.png) 

![![Tests from POST UpdateProfile](images/Tests.png)  

 ![![Request-responce2 from POST UpdateProfile](images/Request-responce2.png)
 

### Scenario in framework on CucumberJs

- A simple positive login verification BDD scenario on Gherkin 

![scenario](images/VSCLoginFeature1.png)
 
 
### Implements function click:

- For example, like on lines 7 and 15 from the script of BDD scenario on the previous screenshot

![when](images/When.png)

- The clickElementByName(elementName) function allows you to click on an element with the name elementName, and in turn, is implemented like this

![clickElementByName](images/clickElementByName.png)

- The click function is taken from the WebDriverIO framework, and the getSingleElementBySelectorName(selectorName) function allows you to get the element by selector and is implemented as follows.

![getSingleElementBySelectorName](images/GetSingleElementBySelectorName.png)

- To extract a selector from elementsSelectors in a PageObjekt (in our case, LoginPage) by the name of the selector (in our case, loginButton)

![elementSelectorspng](images/elementSelectorspng.png)

- the getPageElementSelectorByName(selectorName) function is used, which is implemented like this:

![getPageElementSelectorByName](images/2fun.png)

- The getSingleElementByPath(selector) function allows you to determine the required web element using the extracted selector (in our case - button.login-button) and is implemented like this:




## Books I have read

  * __"Software Testing - Base Course"__ by Svyatoslav Kulikov 
  * __"Software Testing Revealed"__  by International Software Test Institute