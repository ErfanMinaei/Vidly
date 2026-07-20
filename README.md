# Vidly API

A RESTful movie rental API built with **Node.js**, **Express**, and **MongoDB**. It supports user authentication, movie, genre, customer, and rental management with JWT-based authorization.

## Features

- JWT Authentication & Authorization
- User registration and login
- CRUD operations for Movies, Genres, and Customers
- Rental management
- Input validation with Joi
- Password hashing with bcrypt
- Centralized error handling
- Unit testing with Jest
- Config-based environment management

## Tech Stack

- Node.js
- Express.js
- MongoDB & Mongoose
- JWT
- Joi
- bcrypt
- Winston
- Jest

## Installation

```bash
git clone <your-repo-url>
cd vidly
npm install
```

## Configuration

Create the required configuration files (or update the existing ones) inside the `config/` folder.

Set your MongoDB connection string and JWT private key before running the application.

## Run

```bash
node index.js
```

Or with Nodemon:

```bash
npx nodemon index.js
```

## Testing

```bash
npm test
```

## Project Structure

```
config/
middleware/
models/
routes/
startup/
tests/
index.js
```

## API Modules

- Authentication
- Users
- Movies
- Genres
- Customers
- Rentals

## License

This project is for learning and educational purposes.
