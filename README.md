### Object-Relational Mapping (ORM): E-Commerce Back End
----------------------------

<br>

#### Overview:
- This application is a back end application for an e-commerce website that configures **Express.js** API using **Sequelize** to interact with **MySQL**.

<br>

#### Installation:
- This application requires **Node.JS**
- To run application, first the neccessary information in **.env** file to connect MySql
- Install necessary npm packages:
```md
    npm install
```
- Run schmea database in **db** folder:
```md
    mysql -u root -p
    source schema.sql
```
- Start application:
```md
    npm start || node server.js
```

<br>

#### Process:
- The application was developed by using a given starter code for an E-Commerce website using Object-Relational Mapping (ORM).
- Different models for each of the 4 objects (Product, Category, Tag, ProductTag) were created in the **models** folder.
- In the routes folder, the different http methods were routed accordingly based on the various objects.

<br>

#### Additional Documents:
- Link to walkthrough video: https://www.youtube.com/watch?v=EyGhuxlL8bY&ab_channel=PaulWon
- Link to github Repo: https://github.com/paulwon2223/ORM-ECommerce-BackEnd-PW

<br>

#### Contact:
- email: wonpaul2223@gmail.com
- github: https://github.com/paulwon2223