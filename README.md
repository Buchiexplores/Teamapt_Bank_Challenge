# Teamapt_Bank_Challenge
A bank transaction application

Technology Stack: Java, SpringMVC, MySQL

# About

This is a web application for handling bank transactions developed for entry challenge for https://teamapt.com . The online banking app is to have the following features/requirements:

Accounts  

-	Primary
-	View Transaction list
-	Search Transaction
-	Savings
-	View Transaction list
-	Search Transaction

Transfer  
-	Between Accounts
-	Person-To-Person
-	Add/Edit Recipients

Transaction 
-	Deposit
-	Withdrawal

Menu  
-	Profile Settings
-	Schedule Appointment

Registration  

# Spring MVC
Spring MVC is a library of classes for building web applications, using a model-view-controller (MVC). MVC is a very high-level approach to organizing code. It is not specific to web applications or Java. 
At a high-level, MVC means separating code into three independent but communicating parts:  
•	model code is concerned with data management and business logic.  
•	view code is concerned with how data is displayed to users or other systems.  
•	controller code is concerned with handling commands, which primarily means deciding; (i) what model code to call for a given command (ii) what view code to call when the model code is done.

So for example, in a banking application,   
•	model code would manage users and bank accounts, provide methods for credits and debits, reject improper operations such as withdrawing more money than is available, and so on.    
•	view code would show a user a visual display of their account balances, a history of transactions, and some kind of visual elements -- buttons or menus -- to allow a user to manage the display, deposit, withdraw, or transfer money, and so on.    
•	controller code would respond to user actions including login, clicking buttons and menu items, and so on; the controller calls model code to do the actual changes to the accounts, if any, and retrieve the appropriate data, and  then it calls view code to display the results.    
The controller is clearly a central element of an application, but it should be primarily a dispatcher. It should not include any business logic, such as deciding who has access to what information, or calculating results, nor should it have any interface logic, such as how to display data or what kinds of interface widgets to use.

The MVC organization can be applied to both the back end and the front end.
In an MVC web page interface,   
•	model code will be JavaScript to manage objects, networks calls, and so on.   
•	view code will create the HTML.   
•	controller code will respond to window events, button clicks, and so on.    
In an MVC web application back end,   
•	model code will be Java object and repositiory classes, responsible for business logic and database management.   
•	view code will generate HTML using templates, such as ThymeLeaf.    
•	controller code is responsible for passing HTTP requests to the appropriate model code, and then calling the appropriate view code.   

Spring MVC provides classes and annotations for implementing controllers. In particular it makes it easy to connect URLs to the appropriate controller method to call, and easy to say what view code should be called after a method is finished.



# Installation/Usage

1.	Install spring tools suite (STS) plugin from eclipse market place.
2.	Clone the repo to your machine.
3.	Import as Maven project in Eclipse.
4.	Start MySQL server (You can use MySQL Workbench)
5.	Set your database user name and password inside C:\...\UserFront\src\main\resources\application.properties
6.	Right click and run as Spring Boot App
7.	Wait for Tomcat to start 
8.	Check for port number (Default: 8080)
9.	 Open browser and access application on localhost:8080

# References
https://www.udemy.com/build-an-online-bank-with-java-angular-2-spring-and-more/?start=0
https://gbstool.learningbydoingtools.com/ebooks/g/item?id=32









