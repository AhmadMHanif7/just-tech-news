# just-tech-news

## File Setup

Config
 -> Connection.js

 DB
 -> schema.sql

 Models
 -> index.js = Imports the user table
 -> user.js = Contains the code for the user table

 Routes
 -> api
    -> index.js = Brings in the routes
    -> unser-routes.js = Routes for the user model
 -> index.js =Brings in the routes from the API folder

 .env = Contains the individual user environment variables that override the varibles set in the etc/environment file. Needs to be added to gitignore file

 server.js = Calls the application


Dependences
dotenv: Automatically loads environment variable from a .env file inot the process.env object