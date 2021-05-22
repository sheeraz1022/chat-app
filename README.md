# Chat Application

This application has been created over React using webpack 5. It's basically using a GraphQL server to communicate with other users.

## Structure of this application

Its using a websocket to listen to server continously. If server receives any message, its directly fetched by the user. Also, its using graphql subscription instead of graphql query to subscribe for any incoming messages.

Its using postMessage as mutation to send a message to server, which will eventually be listened by other clients.

## Hosting

Netlify: This application is hosted on netlify (https://thirsty-almeida-074cb5.netlify.app/)
Server Github: https://github.com/sheeraz1022/chat-app-server
