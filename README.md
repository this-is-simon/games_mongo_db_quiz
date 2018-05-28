# Quiz Answers

## What is responsible for defining the routes of the games resource?
The games_router.js file defines the routes.

## How is the server configured to know about the route definitions for the games resource?
By using the node.js framework, Express.

## What is the responsibility of server.js?
Server.js is the go-between between our index_router and database, and it 'listens' on port 3000.

## What are the responsibilities of the indexRouter?
The indexRouter is the go-between between the server and the gamesRouter which allows us to add a number of routers as needed.

## What are the responsibilities of the gamesRouter?
The gamesRouter receives data from the games model and passes it to the indexRouter along with the request to the server.

## Which of the games API routes does the front-end application consume?
The API routes include:
index '/' => GET
read '/:id' => GET
create '/' => POST
destroy '/:id' => DELETE
update '/:id' => PUT

