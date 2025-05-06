# Hello World Node.js Server

A simple HTTP server built with Node.js that responds with "Hello, World".

## Description

This project demonstrates a basic HTTP server implementation using Node.js built-in `http` module. The server responds with a plain text "Hello, World" message for all incoming requests.

## Prerequisites

- Node.js installed on your machine

## Running the Server

1. Clone or download this repository
2. Navigate to the project directory
3. Run the server:

```
node server.js
```

4. Visit `http://localhost:3000` in your browser or use a tool like curl:

```
curl http://localhost:3000
```

## Code Explanation

The `server.js` file contains:
- HTTP server creation using Node.js built-in http module
- A request handler that responds with "Hello, World"
- Server configuration to listen on port 3000
- Console output to indicate when the server is running 