# AWS-PROJECTS WEB APPLICAION DEPLOYMENT USING SERVERLESS SERVICES.


This project mainly use the resources api gateway, lambda, dyanamoDB these are serverless servvices, coming to the project we will upload the application code into 
lambda function then we create one iam role to access the services by another service then create one table in dynamoDB and them create one rest api and create two 
get and post select lambda for integration type then deploy the api when ever user sends the request using invoke url to api gateway it wil trigger the lambda func-
tion(act as server in this project) it will run that code and store that details in the dynamoDB table.
