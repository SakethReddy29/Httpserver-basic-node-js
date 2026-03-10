# Simple Node.js HTTP Server

This project is a basic HTTP server built using **Node.js**.  
It handles simple routes and logs every request made to the server.

---

## Project Structure

```
project-folder
│
├── index.js      # Main server file
├── log.txt       # Stores request logs
├── package.json  # Project configuration
└── README.md     # Project documentation
```

---

## Features

- Simple HTTP server using Node.js
- Handles multiple routes
- Logs each request with timestamp
- Returns 404 for unknown routes

---

## Routes

| Route | Response |
|------|----------|
| `/` | hello from server |
| `/about` | I AM SAKETH REDDY |
| others | 404 NOT FOUND |

---

## Logging

Each request is logged in **log.txt** with timestamp and URL.

Example:

```
1771363375915:/ New Req Received
1771363398364:/about New Req Received
1771363428210:/Team New Req Received
```

---

## Installation

1. Install **Node.js**
2. Clone the repository

```
git clone <your-repository-link>
```

3. Navigate into the project folder

```
cd httpserver
```

---

## Run the Server

Start the server using:

```
npm start
```

Server will run on:

```
http://localhost:8000
```

---

## Example

Open browser and visit:

```
http://localhost:8000/
```

Output:

```
hello from server
```

Visit:

```
http://localhost:8000/about
```

Output:

```
I AM SAKETH REDDY
```

---

## Technologies Used

- Node.js
- HTTP Module
- File System (fs) Module
