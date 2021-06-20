Who uses Cypress?
-----------------
Our users are typically developers or QA engineers building web applications using modern JavaScript frameworks.

Cypress enables you to write all types of tests:

* End-to-end tests
* Integration tests
* Unit tests

> Cypress can test anything that runs in a browser.

Cypress ecosystem
-----------------
Cypress consists of a free, open source, locally installed Test Runner and a Dashboard Service for recording your tests.

Explain abit about cypress Architecture
----------------------------------------
Most testing tools (like Selenium) operate by running outside of the browser and executing remote commands across the network. Cypress is the exact opposite. Cypress is executed in the same run loop as your application.

Behind Cypress is a Node server process. Cypress and the Node process constantly communicate, synchronize, and perform tasks on behalf of each other. Having access to both parts (front and back) gives us the ability to respond to your application's events in real time, while at the same time work outside of the browser for tasks that require a higher privilege.

Cypress also operates at the network layer by reading and altering web traffic on the fly. Communication between front end and backend can be manipulated or mocked using cypress.

How we can install cypress only for dev:
----------------------------------------
>npm install cypress --save-dev

How we can switch browsers in Cypress?
----------------------------------------
The Cypress Test Runner attempts to find all compatible browsers on the user's machine. The drop down to select a different browser is in the top right corner of the Test Runner.

![image](https://user-images.githubusercontent.com/2181212/122684750-9f0d8700-d207-11eb-998c-c37c542b50f7.png)

How to write test in cypress?
------------------------------
https://docs.cypress.io/guides/getting-started/writing-your-first-test

What is Cypress Studio?
-------------------------
Cypress Studio provides a visual way to generate tests within the Test Runner, by recording interactions against the application under test.

![image](https://user-images.githubusercontent.com/2181212/122684836-35da4380-d208-11eb-9e7b-4088aa29022c.png)

What is Cypress Dashboard
------------------------------
![image](https://user-images.githubusercontent.com/2181212/122684874-7043e080-d208-11eb-8361-c8d885c27a60.png)
https://docs.cypress.io/guides/dashboard/introduction

Cypress Dashbaord also provides additional features to connect to GitHub/GitLab/ Jira Integration

What is Cypress Runner?
-------------------------
It is used to execute the testcase.

What is Cypress Dashboard?
-----------------------------
The Cypress Dashboard is a service that gives you access to recorded test results - typically when running Cypress tests from your CI provider. The Dashboard provides you insight into what happened when your tests ran.

What is cypress Kitchen sink?
---------------------------------
It has example app used to showcase complete featutes of cypress testing.  

What is Node?
-------------
Node is a JavaScript runtime built on Chrome's V8 JavaScript engine.

What is npm?
------------
Node Package Manager, enables to do all short of node operations, like install, run , test, update etc..



> Cypress Syntax Cheet Sheet - https://cheatography.com/aiqbal/cheat-sheets/cypress-io/


Some additional Questions
----------------------------
https://docs.cypress.io/faq/questions/general-questions-faq#Is-Cypress-free-and-open-source
https://docs.cypress.io/faq/questions/using-cypress-faq
