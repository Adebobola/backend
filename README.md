## Backend Development 

The server side aspect of web development, focusing on creating and managing the server logic, databases and APIs. 

It involves handling user authentication, authorization, and processing user requests. 

## What is a back-end? 
The backend is all of the technology required to process the incoming request and generate and send the response to the client. This typically invloves three major parts:
- The server: This is the computer that receives requests
- The app: This is the application running on the server that listens for requests, retrieves information from the database, and sends a response. 
- The database: Databases are used to organize and persist data 

## Core functions of the app?
- The server runs an app that contains logic about how to respond to various requests based on the HTTP verb and the Uniform Resource Identifier(URI). The pair of an HTTP verb and a URI is called a route, and matching them based on a request is called routing. 
- Some of these handler functions will be middleware. Middleware is any code that executes between the server receiving a request and sending a response. 

These middleware functions might modify the request body, query the database, or process the incoming request. 

Middleware functions typically end by passing control to the next middleware function, rather than sending a response. Eventually, a middleware function will be called that ends the request-response cycle by sending an HTTP response back to the client. 

## What is a Web API?
- An API (Application Programming Interface) is a collection of clearly defined methods of communication between different software components. 
- It is the interface created by the back-end: the collection of endpoints and the resources these endpoints expose. 