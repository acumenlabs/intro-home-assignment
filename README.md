# Acumen Intro Homework

As part of our application process, we'd like to see what you can produce by giving you a small assignment. It should take you no more than a few hours to complete the assignment, but any extra polish or features you might want to put in will not go unnoticed.

## The assignment

We would like you to create a simple key/value store using node.js and sqlite.
Specifically, we need to create an HTTP server which will respond to the following requests -

 - [ ] Store a specific string for key
 - [ ] Store a specific number for key
 - [ ] Fetch a specific string for key
 - [ ] Fetch a specific number for key

The server should use URL parameters for the key.
The HTTP GET method would be used for retrieval while a POST method should be used for storing.

Examples:

GET /str/keys/some-key ==> fetches string for "some-key"
POST /str/keys/foo-key ==> stores string for "foo-key"

#### Extra credit features

 - [ ] Support for arrays and/or complex objects
 - [ ] Add methods for retrieving all keys / values
 - [ ] Tests

## Requirements

You should use the following tools to accomplish this task:

 - node.js
 - express.js

If you have any questions, please ask!

To complete your homework, please fork this repo and commit your work to your fork. When you are ready for us to look at it, give us access to your fork so we can review and run it.
