# Request Header Parser Microservice

A simple API microservice that extracts and returns client information from HTTP request headers.

## Project Background

This project is part of the freeCodeCamp "Back End Development and APIs" certification. It builds on skills acquired in previous sections:

* Managing Packages with NPM (✓ COMPLETED)
* Basic Node and Express (✓ COMPLETED)
* MongoDB and Mongoose (✓ COMPLETED)
* Backend APIs and Microservices Projects (⏳ IN PROGRESS)

## Features

This microservice provides a single endpoint:

- `GET /api/whoami` - Returns a JSON object with the following properties:
  - `ipaddress`: The client's IP address
  - `language`: The client's preferred language (from the Accept-Language header)
  - `software`: Information about the client's browser and operating system (from the User-Agent header)

## Example Response

```json
{
  "ipaddress": "159.20.14.100",
  "language": "en-US,en;q=0.5",
  "software": "Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:50.0) Gecko/20100101 Firefox/50.0"
}
```

## Technologies Used

- Node.js
- Express.js

## Setup and Installation

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   ```
3. Start the server:
   ```
   npm start
   ```
4. Visit `http://localhost:3000/api/whoami` in your browser

## Project Structure

- `index.js` - The main application file with the server configuration and route handling

## Skills Acquired

* HTTP Request Headers processing
* API Endpoint creation
* Express middleware usage
* Environment variable configuration with dotenv
* Response formatting with JSON
* IP address handling
* Cross-Origin Resource Sharing (CORS) configuration
* Node.js deployment

This project demonstrates my systematic approach to learning backend technologies as I build toward my ultimate goal of becoming an AI engineer. Understanding APIs and microservices is crucial for developing and deploying robust AI applications.
