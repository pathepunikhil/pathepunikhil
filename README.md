# WEB APPLICATION
This project is a web application that uses AWS Amplify, Lambda, API Gateway, DynamoDB, and IAM to create a serverless architecture for hosting a web applicati

# Project Overview
The web application is built to provide a simple CRUD (Create, Read, Update, Delete) functionality for users to manage their tasks. The application is built using React and is hosted on AWS Amplify. The backend is built using AWS Lambda, API Gateway, and DynamoDB. IAM is used for access control and authentication.

## AWS Services Used
### AWS Amplify:
A development platform that allows us to build, deploy,and manage modern web and mobile applications.
### AWS Lambda:
 A serverless compute service that allows us to run code without provisioning or managing servers.
### Amazon API Gateway:
A fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale.
### Amazon DynamoDB:
A fully managed NoSQL database service that provides fast and predictable performance with seamless scalability.
### AWS IAM:
A web service that helps you securely control access to AWS resources for your users.

# Architecture
The application architecture is designed to provide high availability and scalability, as well as to ensure security of the data and users.
![image](https://user-images.githubusercontent.com/131676013/236117859-e07008cf-03a8-4c84-b81f-c4b3a552f362.png)

## Setup:

Create an AWS account and login to the AWS Management Console.

Create an IAM user and attach an appropriate policy to the user.

Create a DynamoDB table to store the data required for the application.

Create a Lambda function to handle the requests made by the user.

Create an API Gateway to provide a RESTful interface to the Lambda function.

Configure Amplify to deploy the web application.

## Usage:
Once the setup is complete, users can access the web application by navigating to the deployed URL. The application will interact with the Lambda function and the DynamoDB table to retrieve and store data as required. Users will also be authenticated and authorized using IAM.

Conclusion
The web application architecture using Amplify, Lambda, API Gateway, DynamoDB, and IAM is a powerful way to build secure and scalable web applications on AWS. With this architecture, developers can quickly and easily build web applications that are highly available, scalable, and secure
