# levelUpBackend
This is a Backend Project using Node js. 

## Build Setup
```bash
# install dependencies
$ npm install

# launch server at localhost:5000/api/validation
$ npm start
```

Run project on postman using http://localhost:5000/api/validation.

### The project has two routes:
- **Create A Payment**: http://localhost:5000/api/validation.
The create a payment route is a POST requests that takes five required parameters (Email: String, Card Number: Number, Expiration Date: Date (format: MM/DD/YYY), CVV: Number, Name: String)

- **Get All Payments**: http://localhost:5000/api/validation. The Get all payments is a get requests that gets all the created payments.

## Database: 
The project is connected to a NoSQL database, Mongodb. Mongoose was used in the project
