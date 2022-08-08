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
- HandleBars</br>
- Express Sessions</br>
- Connect Session Sequelize
    
MySql 2 - relational database</br>

Heroku - app deployment</br>
- JawsDB MySQL - Heroku add on</br>
  
Insomnia - Endpoint testing software</br>

Jest - unit testing </br>


## Usages
Login / Sign-up Page
![image](https://user-images.githubusercontent.com/101683611/183310278-bc9aea2f-ad97-49cc-960e-1e709df26782.png)

Dashboard - view all posts
![image](https://user-images.githubusercontent.com/101683611/183310260-89e173cc-eeb5-4317-b926-899c93b2197b.png)

Create a Post
![image](https://user-images.githubusercontent.com/101683611/183310233-39f5df4b-035b-491c-9f26-7902534d62e0.png)

## Install Dependecies

npm init -y </br>
npm install sequelize express mysql2 </br>
npm install dotenv </br>
npm install bcrypt </br>
npm install express-session connect-session-sequelize <br/>
npm install jest -D
