#Name
#Student number

#Tutorial 09

##Table of content
-Overview
-prerequisites
-Installation
-testing
-link to the demostration

##Overview
The purpose of this tutorial is to get you familiar with relational database concepts and using the SQLite database from its CLI (Command Line Interface). You should watch the video lecture on Database Concepts and look at the notes on installing SQLite before attempting this tutorial.

## Prerequisites

Before you begin, ensure you have the following prerequisites installed:

- [Node.js](https://nodejs.org/): This project requires Node.js to run. You can download and install it from the official Node.js website.

- [SQLite3]: This project requires Sqlite3 to run. You can download and install it from the official Sqlite3 website.

##Installation

- [Node.js]
This project relies on Node.js for its runtime environment. Visit the [Node.js official website](https://nodejs.org/) for installation steps.

This project relies on Sqlite3 for its runtime environment. Visit the [Sqlite3 official website] for installation steps.


##Testing 
to test the assignment follow the steps:
- navigate to the directory of the server.js
- run "node server.js" to enter the sqlite3 environment
- type "http://localhost:3000/index.html" in your browser
- Log in with userid : Qusai and password: sam924 NOTE: this is the admin role
- type "http://localhost:3000/songs?title=My+Love" in your browser 
- notice the 4 songs listed  (exercise 3)
- type "http://localhost:3000/users" in your browser to navigate to the users page
- this should show the list of user because of the current user is an admin
- log in again user a different userid and password ie userid : Louis , password : secret
- type "http://localhost:3000/users" in your browser to navigate to the users page
- Notice the the error pages displayed because the user is a guest and not an admin



##link to the demostration


