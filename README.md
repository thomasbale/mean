# MEAN Stack Single Page Application
Here we have an example MEAN stack project. The mean stack allows developers to quickly produce secure, fast and dynamic sites ready to scale. The MEAN stack is the perfect tool for startups and product developers. 

# What is a Single Page Application?
A SPA serves a single index.html which includes script imports which dynamically re-renders what the user sees - without re-requesting a page. Angular is used to dynamically update (fetch/post) the DOM and makes this process very simple. The result is a highly interactive application following the M-V-C design paradim. 

# Architecture overview
The client side is the web page which runs in the browser. On the client we use Angular to render the content in JS. The client side runs on the server and we use Express, MongoDB and Node for the logic. We are using a Node backend, however, the Angular client could be served by any storage serving. The logic (dynamic endpoints) are all managed on the server - it's obviously important that things like authentication can't be edited directly by the client! 

We make AJAX requests and pass data in JSON format between the client and server. We make these requests over a RESTful API

# Worksheet overview
These worksheets set out the steps to build a fully functioning single page application (SPA) from scratch using the MEAN stack. Our sample project is based around free hosting on Heroku (File server) and MLab (Database) and was developed and tested on Ubuntu 18.04. There are, of course, many different ways to achieve the same results as described here; it is simply a guide for those looking for a rough roadmap of how to proceed.

## 1.DevOps & Continious Integration (CI)
CI is the practice of merging all developers' working code to a staged 'Master' branch, testing, then deploying to production. Ideally CI is achieved with integrated and automated testing to ensure that bugs are never introduced on a staging or live environment. Good practices around CI begin at the start of a project before anyone has typed a line of code! 
### Hosting: Site & DB
### Using Git hooks
### Tests

## 2.Angular & building the client side
### Modules, components, events
### Posts
### Forms

## 3.NodeJS & building the API
### RESTful
### Express
### GET
### Angular HTTP
### POST Endpoints

## 4.MongoDB & persistent storage
### Angular -> MongoDB
### POST
### Storing data
### Updating client side

## 4.User Authentication
### SPA Authentication
### New user on request
### Handling tokens

## 5. Testing and errors
### Error handling
### Improving the testing




