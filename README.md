# 13 Object Relational Mapping (ORM): E-commerce Back End

## Description

This app is the backend of an E-Commerce website. Express.js was used for the API server, MySQL for the database and Sequelize to interact between them. The SQL database includes tables for products, categories, tags, and product tags. RESTful API routes are used with their respectbale CRUD functionality.


## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

&nbsp;

---
## Installation

The User should clone the repository from GitHub.

&nbsp;

In the command-line, you will need to enter the following commands;
```
npm init -y
npm install express sequelize mysql2 dotenv
```
&nbsp;

Open up MySQL shell and input the following;
```
source db/schema.sql;
Then exit mySQL. 
```
&nbsp;

You will also need to place a **.env** file to the root directory of the project, in order to connect to your MySQL database. Then you should add the following code to your **.env** file;
```
DB_NAME='ecommerce_db'

DB_USER='root' or 'Your username'

DB_PW='Your mySQL password'
```
&nbsp;

Last step is to run the folliwing command in your command-line;
```
npm run seed
```
&nbsp;

---
## Usage

Initialize the APP server by using the following command in your command-line;
```
node server.js
```
You can test the API routes using Insomnia.

&nbsp;

---
## Links

[GitHub Repository](https://github.com/MorningSol/e-commerce-backend)
 
&nbsp;

---
## Demonstration Video


https://user-images.githubusercontent.com/98545619/169570108-d5f8002e-0ce4-4b96-83da-db314a9fb0e5.mp4


&nbsp;

---
