# E-commerce Back-end with ExpressJS and Sequelize (SQL ORM)

## Description 
Back-end using ExpressJS and Sequelize ORM

## Walktrough video
[]()


## Table of Contents

* [Walkthrough Video](#walkthrough-video)
* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)

## Installation
1. Clone the repo 
```
git clone git@github.com:luluvann/sequelize_express_e-commerce-backend.git
```
2. Open a terminal and cd to the root of the cloned repo
3. Make sure to have MySQL, Insomnia or Postman installed 
4. Create a .env file at the root of the repo
5. Paste the following text in the .env file and make sure to replace the value in DB_PW and DB_USER with your own credentials. Keep the value of DB_NAME
```
DB_PW=yourMySQLPassword
DB_NAME=ecommerce_db
DB_USER=yourMySQLUsername
```
5. Install all the dependencies
```
npm install
```
6. Open MySQL Terminal and connect with your MySQL password
```
mysql -u root -p
```
7. Create the database and use it
```
source db/schema.sql
USE ecommerce_db;
```
8. Open a new terminal and start a new server
```
node server.js
```
9. Open a new terminal and seed the tables data
```
npm run seed
```

## Usage 
1. Open Insomnia or Postman
2. Test the various endpoints at http://localhost:3001/


## Technologies
- MySQL2
- Sequelize
- ExpressJS

