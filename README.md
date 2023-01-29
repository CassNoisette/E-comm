# EE-commerce Back End

## Description
As a developper, I want to build the backend for an e-commerce site for my company SO THAT it can compete with other e-commerce companies, using MySQL2, Express, Sequelize and dotenv.

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Usage
Run:
- mysql -u root -p
- source db/schema.sql
- npm i
- npm run seed
- npm start
- insomnia 

## License
MIT license

