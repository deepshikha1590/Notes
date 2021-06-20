Let's Learn Cypress
---------------------
Over the past few days, I have been playing around with cypress, and it has been an enriching experience. I have been doing end-to-end testing for a few years now, but working with cypress has been a different experience altogether, mostly because of its intuitive commands and test debugging features. 

What is Cypress
------------------
Cypress is opensource next-gen front-end testing tool specifically developed for modern web apps(React, Vue, Angular). Cypress End To End test makes it incredibly easy for users to debug and write.

Most of the modern testing tools including selenium operate in a certain way. They run outside of the web browser and execute different remote commands.
On the other hand, Cypress operates directly within a web or internet browser. This in turn helps Cypress to modify the behavior of the browser by altering or mocking network responses.

Cypress currently has more than 30K starts, around 2K Fork(1) in Github which is way more than Selenium(2). Cypress lets user wirte or debug quality test easily. 

Lets Try TODO APP
-----------------

< git clone https://github.com/deepshikha1590/cypress-tutorial-build-todo-starter

**In order to run this project we need to have node and npm installed.**

< npm install
< npm install cypress

Add NPM Script for cypress
```json
"scripts": {
    "build": "webpack",
    "watch": "webpack --watch",
    "serve": "json-server db.json",
    "dev": "concurrently \"npm run watch\" \"npm run serve\"",
    "cypress": "cypress open"
  }
```

Now its showtime, Let's run Cypress
npm run cypress

Questions
----------

What is node?

What is npm?

What is webpack and how to run app using webpack?
