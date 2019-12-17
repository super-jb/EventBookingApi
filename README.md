# Events Booking Api using Graphql, Node.js (Express), React & MongoDb

![GraphQL](https://avatars2.githubusercontent.com/u/13958777?s=50&v=4)  
![Node](https://cdn.worldvectorlogo.com/logos/nodejs-icon.svg | height=50)  
![React](https://cdn.worldvectorlogo.com/logos/react.svg | height=50)  
![MongoDb](https://cdn.worldvectorlogo.com/logos/mongodb.svg | height=50)  


## Notes
* backend runs on localhost: 8000
* frontend runs on localhost: 3000


## Steps
1. Go to mongodb.com and setup a new cluster, new user (with permissions to read/write) and security (IP whitelisting)
https://www.youtube.com/watch?v=ugI1riTacbw


1. update the backend ```nodemon.js``` file with your values
```javascript
"env": {
  "MONGO_USER": "YOUR MONGO USERNAME",
  "MONGO_PASSWORD": "YOUR MONGO PASSWORD",
  "MONGO_DATABASE": "YOUR MONGO DATABASE NAME",
  "JWT_SECRET": "A SECRET YOU DEFINE TO ENCRYPT / DECRYPT PASSWORDS"
}
```

1. Run backend:
 ```bash
cd backend
npm start
```
go to:
```http://localhost:8000/api```


1. Run backend
 ```bash
cd frontend
npm start
```
go to:
```http://localhost:3000/```


1. Play around with the UI
* create an account (can use fake emails, no email confirmations sent)
* login and create some Events
* logout
* create a different account
* login with new account and create some Events
* go back and forth between accounts, create Events and confirm Bookings
