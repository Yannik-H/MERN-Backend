### Introduction

This is the backend part of project. It's consists of the controller as well as model in the MVC design patterns and the routing logic for sending HTTP requests.

### Controller

In the `controllers` directory, there are two js file: `place-controller.js` and `user-controllers.js`. 

- In the place controller,  functions for getting, posting, updating, deleting places are built.
- In the user controller, functions for logging in and signing up are built. There is also some features for generating tokens for SPA + REST API to strengthen the security of confidential information.

### Middleware

Customized middlewares are also built for the Express.JS used in this project. `check-auth.js` is used for dealing with the token follow by any HTTP request with a token. `file-upload.js` is for tackling the user upload images.

### Model

This part is for customized error object and the schema of data in MongoDB

### Route

In the `routes` directory, definition of routings are built with Express.JS. For the detailed RESTFUL routing design, please check the README.md in the frontend part.