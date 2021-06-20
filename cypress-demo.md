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

> git clone https://github.com/deepshikha1590/cypress-tutorial-build-todo-starter
>
![image](https://user-images.githubusercontent.com/2181212/122682975-b004cb00-d1fc-11eb-9ba5-c2f01d2646ea.png)

**In order to run this project we need to have node and npm installed.**

> npm install -- Installs the project dependencies.

 ![image](https://user-images.githubusercontent.com/2181212/122683007-eb06fe80-d1fc-11eb-9629-f4989b23f534.png)

Once all the dependencies of project is installed, we should see **node_moudules** folder in the project.
![image](https://user-images.githubusercontent.com/2181212/122683049-40dba680-d1fd-11eb-81a3-85e61525058f.png)

Now to run the appliation we are required to run below command(Webpack)
> npm start / nmp run dev - (It is configureable can be changed using package.json / also depends on javascript framework or dependencies.)

First install cypress dependecies and peoject skeltion to our project using below command.
> npm install cypress

Now we should be able to see below folder structure of cypress in our project.

![image](https://user-images.githubusercontent.com/2181212/122683266-67e6a800-d1fe-11eb-9cbe-c80e127710ab.png)

Lets add custome run script to run cypress runner.

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
> npm run cypress

When cypress runs for the first time it displays the it will provide some examples for reference.

> cypress/integration folder is used to write test cases

Lets add a file
    input-form.spec.js
![image](https://user-images.githubusercontent.com/2181212/122683315-b5631500-d1fe-11eb-8683-45670f3ffd18.png)

Text inputs
-------------
Now lets write 1st real test....

Identification of elements is one of most important part of the automation testing. Lets try to identify the element using the class name.
![image](https://user-images.githubusercontent.com/2181212/122683579-68803e00-d200-11eb-94f8-0f6109e70e83.png)

Lets add statement to verify the focussed element in page using above class.

![image](https://user-images.githubusercontent.com/2181212/122683609-a7ae8f00-d200-11eb-8c39-1f68d895097f.png)

Once we save this cypress will detect the file change and cypress runner will run our test.

![image](https://user-images.githubusercontent.com/2181212/122683626-c57bf400-d200-11eb-86b0-33cdef3140bf.png)

Our test failed because cypress coudn't find the focussed element with given class name so test failed. It also shows which step the test has failed on.

Now lets write some more test in same file.
![image](https://user-images.githubusercontent.com/2181212/122683751-9619b700-d201-11eb-8ee7-0aafde017567.png)

lets remove the duplication of the script:

![image](https://user-images.githubusercontent.com/2181212/122683808-f1e44000-d201-11eb-8242-50b304423d76.png)

We can configure our base url in cypress.json file which is avaliable at project level.
![image](https://user-images.githubusercontent.com/2181212/122683835-1e985780-d202-11eb-9fbf-0f33dc699994.png)

With that in place we can go back to our test script and change simply change visit to root of our site.
![image](https://user-images.githubusercontent.com/2181212/122683865-4c7d9c00-d202-11eb-92a9-df05ee9a90dd.png)

