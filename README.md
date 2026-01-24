# Node.js Express MongoDB Project

This is a Node.js application built with Express and MongoDB that demonstrates how to create a web application using MVC architecture. The project uses EJS templates for views and serves static files from the public folder.

## Features
Server and routing handled by Express.js, database management with MongoDB, MVC structure with Models, Views, Controllers, dynamic frontend using EJS, and static files served from the public folder.

## Project Structure
controllers/ handles request logic, models/ contains MongoDB schemas, routes/ defines Express routes, views/ contains EJS templates, public/ contains static files (CSS, JS), app.js is the main application file, and package.json lists project dependencies.

## Getting Started
1. Clone the repository: `git clone https://github.com/Mats914/Node-js-express-mongodb.git && cd Node-js-express-mongodb`
2. Install dependencies: `npm install`
3. Set up MongoDB: run locally or use MongoDB Atlas and update the connection string in app.js if needed
4. Start the application: `npm start` or `node app.js`
5. Open in your browser: `http://localhost:3000`

## Usage
Add, view, update, and delete data via the web interface. Routes and logic are in routes/ and controllers/, templates are in views/ using EJS.

## Dependencies
express, mongoose, ejs, body-parser, nodemon (optional for development)


