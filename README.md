# Local Setup

## Installation

[PostgreSQL](https://www.postgresql.org/download/)

[Node.js/npm](https://nodejs.org/en/download/)

## Instructions 
Detailed guide [Here](https://drive.google.com/file/d/12-wDsdsj-fSjO4mJPRtPdC0eYjVJ0kkm/view?usp=drive_link) 

## Running Project
Running React (under frontend): `npm start`

Running Node.js (under backend): `node server.js`


# Project directory

```
backend/ 
├── config/       Configuration files for database and server
├── controllers/  Handles request processing and business logic
├── middleware/   Custom middleware for authentication and error handling 
├── models/       Database schemas and ORM models 
├── migrations/   Database migrations 
├── routes/       API routes linking endpoints to controllers 
├── scripts/      Additional scripts (e.g., database seeding, utilities) 
    ├── services/ API for sending email notifications 
├── .env          Environment variables for database, server, email notifications 
├── server.js     Entry point for the backend application 
```
```
frontend/ 
├── build/           Compiled and minified production build 
├── public/          Public static assets (e.g., HTML, images, fonts) 
├── src/             Main source code for the frontend 
    ├── assets/      Images, icons, and other static resources 
    ├── components/  Reusable React components 
    ├── pages/       Page-level components (e.g., Dashboard, Login) 
    ├── services/    API service functions for communicating with the backend 
    ├── themes/      Styling and theme files 
    ├── App.js       Root component defining the app structure 
    ├── index.js     Entry point for the React app 
    └── routes.js    Frontend route definitions 
├── .env             Environment variables for the frontend 
├── package.json     Dependencies and scripts for the React app
```


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
## Available Scripts
In the project directory, you can run:
### `npm start`
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
The page will reload when you make changes.\
You may also see any lint errors in the console.
### `npm test`
Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.
### `npm run build`