# Just-Tech-News

## Description
Just Tech News—a tech news website where users can post, upvote, and comment on links to news articles. Just Tech News uses Sequelize, an object-relational mapping (ORM) library, to simplify MySQL queries, add password hashing so that users can create secure passwords, and the application is connected to JawsDB, a MySQL add-on for Heroku.

## Skills Acquired
- Configure the Sequelize ORM in a Node.js application.
- Create models for categories, products, and tags in a relational database and a through table that will connect the product and tag models.
- Define and implement CRUD methods, using Sequelize to interact with your models in each API endpoint through proper RESTful commands (GET, POST, PUT, DELETE).
- Create and implement Sequelize associations to join tables.
- Use environment variables to protect sensitive data, such as your MySQL username and password.

## Technology
Javascript - scripting language </br>

Node.js - runtime environment</br>
- Express Module</br>
- Sequelize Module</br>
- DotEnv Module</br>
- BCrypt Module</br>
    
MySql 2 - relational database</br>

Heroku - app deployment</br>
- JawsDB MySQL - Heroku add on</br>
  
Insomnia - Endpoint testing software</br>

## To Run
- Clone Github repository
- On the root directory, enter `npm install` in the terminal to download all the dependencies
- Enter `npm start` in the root terminal to boot up the server
- Use a third party software (Postman, Insomnia) to test out the end points

## Usages
Create a user
![image](https://user-images.githubusercontent.com/101683611/182640400-ffa24dca-33b1-48fc-8373-0fdbf7d06798.png)

Login
![image](https://user-images.githubusercontent.com/101683611/182640587-dd09297b-3f02-4068-aa12-d1b1790134b9.png)

Create a post
![image](https://user-images.githubusercontent.com/101683611/182640710-4c660966-8fb8-40a3-9eb7-cdb8fcceaf7f.png)

