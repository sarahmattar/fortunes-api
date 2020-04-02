# Fortunes API

This is a small API endpoint project using a JSON-based datastore. It was based on a project app from David Katz's Node and Postgres course on [UDEMY](https://www.udemy.com/course/node-postgresql/). Currently there are 10 fortunes hardcoded in.

Fortune Cookie data was adapted from Josh Madison's collection of fortune cookie-based fortunes, found [here](https://joshmadison.com/2008/04/20/fortune-cookie-fortunes/).  My ultimate goal is to get all of Josh's fortunes that he has collected over the years into a Postgres database that my API endpoints will pull from. 

### Installation

`npm run start` 

This will start the Node server on your local machine, running on port `3000`.  In Postman it can be accessed via `http://localhost:3000`

### Endpoints

Path | Description
---- | ------------
/fortunes 				| Query all Fortunes
/fortunes/random	| Get a randomized Fortune as a response
/fortunes/:id			| Update, Delete, or Query a specific Fortune 











