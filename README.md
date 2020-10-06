# MEAN Stack Single Page Application
Here we have an example MEAN stack project. The mean stack allows developers to quickly produce secure, fast and dynamic sites ready to scale. The MEAN stack is the perfect tool for startups and product developers. 

# What is a Single Page Application?
A SPA serves a single index.html which includes script imports which dynamically re-renders what the user sees - without re-requesting a page. Angular is used to dynamically update (fetch/post) the DOM and makes this process very simple. The result is a highly interactive application following the M-V-C design paradim. 

# Architecture overview
The client side is the web page which runs in the browser. On the client we use Angular to render the content in JS. The client side runs on the server and we use Express, MongoDB and Node for the logic. We are using a Node backend, however, the Angular client could be served by any storage serving. The logic (dynamic endpoints) are all managed on the server - it's obviously important that things like authentication can't be edited directly by the client! 

We make AJAX requests and pass data in JSON format between the client and server. We make these requests over a RESTful API



