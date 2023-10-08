# ChatApp

ChatApp is a Full Stack Chatting App.
WebSockets let developers build realtime functionality into their apps by enabling the sending off small chunks of data over a single persistent connection, in both directions. Using WebSockets in the front end is fairly straightforward, as there is a WebSocket API built into all modern browsers.
## Tech Stack

**Client:** React JS

**Server:** Node JS, Express JS

**Database:** Mongo DB
  

## Run Locally

Clone the project

```bash
  git clone https://github.com/iamharshrana/ChatApp
```

Go to the project directory

Install dependencies
```bash
    "dependencies":
    "bcryptjs": "^2.4.3",
    "buffer": "^6.0.3",
    "cookie-parser": "^1.4.6",
    "cors": "^2.8.5",
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "mongoose": "^7.5.3",
    "ws": "^8.14.2"
```
```bash
    create a .env file for a list of key pair values that set specific variables for a container deployment
```
Start the server

```bash
    //open terminal
    cd api
    nodemon index.js
  
```
Start the Client

```bash
  //open now terminal
  cd client
  yarn dev
```
