CSYE6225-Assignment 04

Name: Pramithi Jagdish
Email: jagdish.p@northeastern.edu

# Task
Create a web application using a technology stack that meets Cloud-Native Web Application Requirements. Start implementing APIs for the web application. Features of the web application will be split among various applications. For this assignment, we will focus on the backend API (no UI) service. Additional features of the web application will be implemented in future assignments. We will also build the infrastructure on the cloud to host the application. This assignment will focus on the user management aspect of the application. You will implement RESTful APIs based on user stories you will find below.

# User Stories Implemented
All API request/response payloads should be in JSON.
No UI should be implemented for the application.
As a user, I expect all API calls to return with a proper HTTP status code (Links to an external site.).
As a user, I expect the code quality of the application is maintained to the highest standards using the unit and/or integration tests.

# Steps to run the project
1. Clone the repository
2. Run command: aws cloudformation deploy --profile demo --stack-name AWS-CLI-CICD --template-file assignment9.yml --capabilities CAPABILITY_NAMED_IAM --parameter-overrides KeyName=key AmiID=ami-0aa11060ab006f034

# Steps to test the project

   
# Tech stack used
Created using a Node.js backend web development and Mysql for DB connection. Used express for web ResAPI framework and mocha and chai for Unit testing.



