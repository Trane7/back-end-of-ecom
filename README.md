# BACK-END-OF-ECOM!! (AN OBJECT-RELATIONAL MAPPING (ORM): E-COMMERCE BACK END)

## Description
A mySQL backend for a e-commerce database and application site. Built using MySQL2, Express, Sequelize, and dotenv.

Link to demo video: https://watch.screencastify.com/v/A7ktPCXWxOIPFmQCrIGb

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria
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
THEN I am able to successfully create, update, and delete data in my database.


## Installation
1. npm init
2. npm install mysql2
3. npm install sequelize
4. npm install dotenv

## Usage
Please run the following commands at the root of your projects directory then enter the prompted questions that follow:
mysql -u root -p

Enter PW when prompted
-then run-
source db/schema.sql
quit
npm run seed
npm start

### Contributing/Links
GitHub Repo link: https://trane7.github.io/back-end-of-ecom/

Demo Video Link again: https://watch.screencastify.com/v/A7ktPCXWxOIPFmQCrIGb
