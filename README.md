### Express Backend Service for Login feature

This is a standalone Express.js server that handles authentication i.e., login and registration.

## How to run locally

Clone the git repository run `git clone https://github.com/SakshamGairola/Login-express-backend.git`

Install required dependencies `npm install`

To run the application run `npm start`

## Components in application

`index.js` is the staring point of the application.

`controller/` directory holds methods for respective use cases.

`models/` directory contains required data model.

`routes/` directory contains routes for server to get to respective use case methods.

## Environment Variables

`PORT` : specifies on which port to run application on. Default is `5000`

For `DB_CONNECTION` url please refer to the [Officail docs](https://www.mongodb.com/docs/atlas/tutorial/connect-to-your-cluster/) to get your connection url
