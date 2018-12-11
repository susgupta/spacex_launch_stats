# Sushil G GraphQL SpaceX App

Sushil GraphQL SpaceX App is a complete application that uses a [**GraphQL**](https://graphql.org/) Express backend to connect to get **SpaceX Launch data**.

The server is an [Express App](https://expressjs.com/) but with one GraphQL endpoint exposed to support getting data for SpaceX Launch Data. The backend will leverage open API available from [SpaceX Rest API](https://github.com/r-spacex/SpaceX-API)

The client is created in [React](https://reactjs.org/) using [Apollo](https://www.apollographql.com/docs/)

## Development Quick Start

```bash
# Install dependencies (server & client)
npm install
cd client && npm install

# Run server on port 3000 & client on port 5000
npm run dev

# Server only on port 3000
npm run server

# Client only on port 3000
npm run client

# Build for production (Builds into server ./public)
cd client && npm run build
```

## Technologies Used

**Server**

- Express
- GraphQL (with GraphQL For Express)
- Axios

**Client**

- ReactJS
- ReactRouter
- Apollo for React

## Real-Time Viewing

The application was publised using [Heroku](https://www.heroku.com/).

Here is link to view the application:

[Sushil G GraphQL SpaceX App](https://sus-spacex-graphql-app.herokuapp.com/)
