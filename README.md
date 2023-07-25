# commerce-back-end

## description 
this contains the back end code to manage an e-commerce site. It can read, create, update, and delete categories, products, and tags for an e-commerce database using MySQL, MySQL2, Sequelize, Express.js, and dotenv.

## Installation
To install any necessary dependencies run the following command: 

    npm install

## Usage 
Clone the repo to your local machine and open in an IDE. Make sure you have node.js and npm installed (hint: `node -v` & `npm -v`). In the packages root directory, install the following packages: express.js, sequelize, mysql2, and dotenv (`npm i express sequelize mysql2 dotenv`). Also create a `.env` file in the root directory to save sensitive information such as your MYSQL username and password, and database name (ex: `DB_NAME='', DB_USER='', DB_PW=''`). These variables are referenced in the /config/connection.js file. From the mysql shell, run `source db/schema.sql;` to create the schema, quit the mysql shell and run `npm run seed` to seed the tables. Finally run `npm start` to initiate the program, open Insomnia and the app is ready to test/demonstrate API routes: GET, POST, PUT, and DELETE for categories, products, and tags. 

## Video Walkthrough 
https://drive.google.com/file/d/190OkNMyRCPIjwUNKhSZzDhZ_2sH6f-jB/view