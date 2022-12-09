# mern-crud-backend
Focus on MongoDB, Express, Node for CRUD (Create, Read, Update, Delete) API. Based on this [tutorial](https://www.bezkoder.com/node-express-mongodb-crud-rest-api/)

## Steps to set up
1. `npm install`
2. `mkdir config && touch config/config.js`

### config.js content

```
module.exports = {
    url: "Placeholder"
  };
```

3. For your url, go [here](https://www.mongodb.com/atlas/database)
4. Create an account if you don't have one
5. Once you have one, login
6. Create and name an project
7. Create a cluster
8. Create user with username and password; keep your username and password safe
9. Add your current IP address; you may need more for each wifi you have access
10. Click on "Connect on the cluster"
11. Click on "Connect your application"
12. Grab the given url; the url should start with "mongodb"
13. Replace the placeholder for uri inside the quotes with uri
14. `node server.js`
