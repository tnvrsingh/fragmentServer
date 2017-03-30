# fragmentServer

A Node.JS framework and Express server.

### /messages POST Route

All messages are posted to the /messages API endpoint.

Once the server recieves the POST request, it will use the trigger method of the Pusher node module which POSTs to the Pusher API (where its visible in the Debug Console in the Pusher dashboard) and if needed can be used to push the message to all connected clients.
