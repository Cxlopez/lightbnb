# LightBnB
This is a web application that is using SQL as the database. It is used for browsing rental properties for events by filtering through the database.
## Project Structure ERD
![44D358A8-1FE2-4079-AFED-B778F56180CC](https://user-images.githubusercontent.com/93356900/176818932-22e22b8e-bdaf-41b8-9acb-6f7cd55dafa1.jpeg)

## Application setup
  * Open lightbnb_webmasterapp
  * Use `npm install` to get dependencies
  * Use `npm run local` command
  * Go to `http://localhost:3000/` in the browser

## Database setup
  * Clone the repo  
  * Run `psql` to start postgreSQL
  * Run the comman `CREATE DATABASE lightbnb`
  * Use `/c lightbnb` to access the database
  * Type `\i migrations/01_schema.sql` to add all tables
  * Type `\i seeds/02_seeds.sql` to add all seeds

## Dependencies 
  * Pg
  * PostgreSQL
  * Express
  * Bcrypt
  * Bodyparser
  * Nodemon
  * Cookie-session