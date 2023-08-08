# Example-1

Example number 1 from Chapter 3 of [Bootstrapping Microservices](https://www.bootstrapping-microservices.com).

Chapter 3 of Bootstrapping Microservices gives instructions on how to package and publish this example using Docker and a private Docker registry.

You need Node.js installed to run this.

Before running install dependencies:

    npm install

Set the PORT number (on MacOS/Linux):
    export PORT=3000

Set the PORT number (on Windows):
    set PORT=3000

To start the microservice:

    node index.js

Or 

    npm start

Then point your browser at http://localhost:3000/video