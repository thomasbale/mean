# Walkthrough overview
Here we set out the steps to build a fully functioning single page application (SPA) from scratch using the MEAN stack. It is based around free hosting on Heroku (File server) and MLab (Database) and was developed on Ubuntu 18.04. There are many different ways to achieve the same results as described here; it is a guide for those looking for a rough roadmap of how to proceed. 

# Security
- Always store passwords, server details and other confidential information and environmental variables
- Hardcoding such things such never be done
- Although MongoDB is not vulnerable to SQL injection usual best practices around requests should be followed

# Setting up Angular CLI

Importantly Angular needs to be compiled (it is natively in Typescript) to run in the broswer on client side. Because of this Angular requires Node for development and production. We make use of the Angular CLI (via npm, which is installed via Node) to give us a project setup where all the dependancies/congiguration are dealt with.

We will add Node, Mongo and any other dependancies via the project. We make use of the Angular CLI development server for testing on localhost, however, this is not suitable for production (!!).  

Core dependancies:
- NodeJS
- Angular
- Angular CLI
- MongoDB
- Express

# Setting up NodeJS

# Setting up MongoDB

# Building a RESTful API
In this example we will use Express and Node to serve the API, however, importantly one could use a different file serving application. 

# Error handling

# User authentication

# Deployment

## CI

## Testing
