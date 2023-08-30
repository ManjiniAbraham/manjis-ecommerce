# E-commerce backend
  
  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)]

## Description

The project is to build the back end for an e-commerce site by configuring a working Express.js API to use Sequelize to interact with a MySQL database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)

## Installation

Install NodeJS. Also install 'Express v4.17.1','mysql2 v2.1.0', 'dotenv v8.2.0', 'sequelize v6.32.1' packages. Also install Insomnia to test to test all API routes.


## Usage

To run the application, do the following actions:
1. Go to folder db, and open integrated terminal and login to mysql using 'mysql -u root -p' command.
2. Source schema.sql to create your database.
3. Go to the main folder and open intergrated terminal.
4. Execute 'npm i' to install all dependencies.
5. Execute 'npm run seed'.
6. Execute 'npm start'.
7. Open Insomnia and test all API routes.


Demo URL:  https://drive.google.com/file/d/122wxUN6vCJGR8-ZBJOhJn8avqUFYVsoy/view


## License

License: [ISC License (ISC)](https://opensource.org/licenses/ISC)

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)]


## Credits

https://sequelize.org/docs/v6/core-concepts/validations-and-constraints/

https://stackoverflow.com/questions/50354817/sequelize-decimal-data-save-with-2-decimal-points 

## Features

* On the Express.js API, when user add database name, MySQL username, and MySQL password to an environment variable file, user is able to connect to a database using Sequelize.
* WHEN user enters schema and seed commands, a development database is created and is seeded with test data.
* WHEN user enters the command to invoke the application,the server is started and the Sequelize models are synced to the MySQL database.
* WHEN user open API GET routes in Insomnia for categories, products, or tags, the data for each of these routes is displayed in a formatted JSON
* WHEN user  open API GET routes in Insomnia and append the id for categories, products, or tags, data for each of these routes sorted by id is displayed in a formatted JSON
* WHEN user gives API POST, PUT, and DELETE routes in Insomnia, user is able to successfully create, update, and delete data in my database.









