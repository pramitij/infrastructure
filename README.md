
Developed a secure, scalable & fault-tolerant distributed application for user data management with microservices architecture, allowing users to perform CRUD operations.

- Used Express for RESTful API framework, Node.js for backend, Mysql for DB connection and Mocha & Chai for unit testing.
- Created resource stack using AWS CloudFormation including networking resources such as - Virtual Private Cloud (VPC), Internet Gateway, Route Tables, etc to host backend application
- Built CI/CD pipelines to automate deployment on AWS with Github actions & CodeDeploy
- Handled load across auto-scaled EC2 instances using application Load Balancer, designed routing policies to map HTTPS requests to ELB, and collected metrics using CloudWatch
- Applied IAM policies, and security groups & defined firewalls using AWS WAF to restrict access to the services
- Polled SNS and triggered AWS Lambdas for a serverless email verification microservice to ensure secure user activity, exploiting DynamoDB for persistence and utilizing AWS S3 service for object storage.
- Issued a secure DNS name from Namecheap and mapped it on AWS Route53

  
# User Stories Implemented
All API request/response payloads should be in JSON.
As a user, I expect all API calls to return with a proper HTTP status code (Links to an external site.).
As a user, I expect the code quality of the application to be maintained to the highest standards using the unit and/or integration tests.
As a user, I should be able to create a user profile
As a user, I should be able to read my profile data
As a user, I should be able to update my information (First Name, Last Name, Profile Pic, Address)
As a user, I should be able to delete my data

# Steps to run the project
1. Clone the repository
2. Run command: aws cloudformation deploy --profile demo --stack-name AWS-CLI-CICD --template-file assignment9.yml --capabilities CAPABILITY_NAMED_IAM --parameter-overrides KeyName=key AmiID=ami-0aa11060ab006f034
   
# Tech stack used
Created using a Node.js backend web development and Mysql for DB connection. Used express for web ResAPI framework and mocha and chai for Unit testing.



