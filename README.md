# Middleware
This repository contains a collection of simple Express.js applications showcasing the use of middleware for various purposes.

# Express Middleware Examples

## index1.js
An Express application utilizing the `body-parser` middleware to handle form data. The server serves an HTML file on the root route ("/") and logs form submissions on the "/submit" route.

## index2.js
A simple Express server demonstrating the use of the `morgan` middleware for request logging. It responds with "Hello" on the root route ("/").

## index3.js
Express server showcasing a custom middleware function called `logger`. This middleware logs the HTTP method and URL for each incoming request.

## index4.js
Express application with `body-parser` middleware to handle form data. It includes a custom middleware (`bandNameGenerator`) that generates a band name based on form input and displays it on the "/submit" route.

