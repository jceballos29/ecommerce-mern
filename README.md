# ECOMERCE - MERN STACK

## Description

This is a simple e-commerce website built with MERN stack. It is a full stack application that uses React for the front end, Node.js/Express.js for the back end, and MongoDB for the database.

## Features

- User authentication with JWT
- Admin authentication with JWT
- User profile with orders
- Admin product management
- Admin user management
- Admin order details page
- Checkout process (shipping, payment method, place order)
- PayPal / credit card integration
- Product search feature
- Product rating and review
- Product pagination
- Product carousel
- Deploy to Heroku


## Usage

### Env Variables

Create a .env file in then root and add the following

```bash 
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = your paypal client id
```


### Install Dependencies (frontend & backend)

```bash
cd backend
npm install
cd frontend
npm install
```


### Run

```bash
# Run frontend (:3000) & backend (:5000)
cd backend
npm run dev

# Run backend only
cd backend
npm run server
```


### Seed Database

You can use the following commands to seed the database with some sample users and products as well as destroy all data

```bash
# Import data
npm run data:import

# Destroy data
npm run data:destroy
```

### Build & Deploy

```bash
# Create frontend prod build
cd frontend
npm run build
```

This will create a build folder in frontend. You can copy this folder to your backend publ

## License

MIT License

## Author

