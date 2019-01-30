# bookstore

Web application to create a list of google books ISBN's making POST requests to a web API and retrieving their cover and data by making GET requests to GoogleBooks API.
Frontend built with React and backend with Node.js + Express

### To run server-side:

/server

```PORT=8080 npm run start```

To test listing route: http://localhost:8080/api/items?q= **search**

To test item description route: http://localhost:8080/api/items/ **:id**

### To run client-side:

/client

```npm run start```

To test application: http://localhost:3000/
