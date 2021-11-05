# E-Commerce_Back_End

## User Story

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies.

## Installation

Both Node.js and MySQL must be installed on your computer.

Install dependencies 
```terminal
npm init --y
``` 
```terminal
npm install express sequelize mysql2
```
Open up MySQL shell and input 
```terminal
source db/schema.sql
```
and 
```terminal
use ecommerce_db
```
Then quit MySQL shell and input the following in your terminal
```terminal
npm run seed
```
to start running application simply input 
```terminal
node server.js
```
Open up Insomnia core to GET, POST, PUT and DELETE from different routes.

## General Info

We’ll take a working Express.js API and configure it to use Sequelize to interact with a MySQL database. This application won’t be deployed so I’ll show a walkthrough video that demonstrates its functionality.

Demonstration Video:

<img src=./assets/g.gif>


## Technologies
Project is created with 
* [Javascript](https://www.javascript.com/)
* [Node.js](https://nodejs.org/en/)
* [MySQL2](https://www.npmjs.com/package/mysql2)
* [Sequelize](https://www.npmjs.com/package/sequelize)
* [Express](https://www.npmjs.com/package/express)
* [Dotenv](https://www.npmjs.com/package/dotenv)