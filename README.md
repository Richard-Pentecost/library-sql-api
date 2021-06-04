# Library SQL API

This is a project from a tutorial for McrCodes.

Creating an api using a MySQL database.

## Using traditional SQL queries

The Book part of the api is created without sequelize and uses traditionaly SQL queries in order to interact with the database.

## Using Sequelize

The Reader part of the api is created using sequelize to make model creation and controller creation.

## Setting up database in order to run the application

Run:
```docker run -d -p 3307:3306 --name libary_mysql -e MYSQL_ROOT_PASSWORD=password mysql```

N.B. script in the bin folder not currently working.