# sse-example
React , Nodejs application demonstrating server side events

#server
 - npm i
 - node server.js

 Endpoints
 - http://localhost:3000/events GET - This is the endpoint clients connect to receive server sent events
 - http://localhost:3000/status GET  -> Returns the number of connected clients
 - http://localhost:3000/facts  POST  -> allows creation of facts.Sends events to al the connected clients when a new fact is created.

#client
 - npm i
 - npm start

  A sample interface showing updates received from the SSE(shows facts)
