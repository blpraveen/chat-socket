# chat-socket
Chat Application Using Express
## Instructions to run
1. Clone repository
2. Run npm install to install node modules
3. Run npm start to run app
4. configure mongodb databse connection in config/database.js

## Instructions to Build and Run Docker Image
1. Follow instructions 1 & 3 above.
2. To build image, cd into directory and run `docker build -t chat:1.0.0 .t`
3. To run container enter `docker run -p 8042:8042 chat:1.0.0`
