# REST API built with Node.js, Express.js and PostgreSQL

The goal of this project is to build a REST API using Node.js, Express.js and PostgreSQL. For this project I created a table called Users which has three columns id, name and email.
NPM Packages used in this project

# You will learn this:

<br> How to start a Node.js project
<br> How to use express.js to create a web server
<br> How to create routes for your application
<br> How to use pg module to get connected to PostgreSQL relational database
<br> How to create CRUD operations in PostgreSQL relational database
<br> How to create a REST API implementing HTTP methods: GET, POST, PUT AND DELETE

# Modules used:

<br> express: web framework for node
<br> pg: connection driver for PostgreSQL relational database
<br> nodemon: module used to automatically restart the application when a change is made

# Resource Descriptions

<b>List all users</b>
<br><br> GET /users/
<br> Get all users registered
<br><br> Query Parameters
<br> None
<br><br> Success response
<br> HTTP Status 200
<br> An array of users
<br><br> users TYPE object[]
<br>&#9;id TYPE integer
<br>&#9;name TYPE string
<br>&#9;email TYPE string
<br><br> List an specific user
<br><br> GET /users/{id} Get information about
<br> POST /users/
<br> DELETE /users/{id}
<br> PUT /users/{id}
