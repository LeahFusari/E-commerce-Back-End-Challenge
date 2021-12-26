# E-commerce-Back-End-Challenge

This is a backend project using MySQL, Node, sequelize, and dotenv.

##Licences

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Installation 

1. Install Node with MySql2, Express, Sequelize, and dotenv packages. 
2. Create a .env file to store your MySql username and password and database 
3. After the dependancies are installed, sign into the database and use the "source db/    schema.sql" command to load the models.
4. In the Command Line, run "npm run seed" to seed the database data. 
5. Start the server with "npm start" in the command line. 


## Project Demo Video

https://youtu.be/bT0YHtra0Xk
