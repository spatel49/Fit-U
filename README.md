# CS554 Web Programming II Final Project - FitU

## Group Members
Siddhanth Patel, Jeffrey Lee, Adam Farid, Cheng Cheng

## Setup
First, install Redis and start the Redis server.

Go into the server directory, then run the following commands in order:
```
npm install
npm run seed
npm start
```
This will install the necessary dependencies, run the seed task to populate the website with data, and run the server side of our web application.
The server side will run on localhost:4000.

Then, go into the client directory, then run the following commands in order:
```
npm install
npm start
```
This will install the necessary dependencies and run the client side of our web application.
The client side will be hosted on localhost:3000. http://localhost:3000/ is where you will be interacting with our web application.

## Logging In
You can sign up for an account or use the account sign-in informations generated by the seed.
The emails of the users in the seed are seeduser@email.com, seeduser1@email.com, seeduser2@email.com, ... , seeduser10@email.com
All passwords of the users are 123456.
You can see this information in seed.js in the server folder as well.

## Other Notes:
We use a MongoDB database, so feel free to use MongoDB Compass if you would like to view the data in the database.