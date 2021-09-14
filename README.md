# node-backend
Node rest api for dead-crumb-trail webapp 

## Setup
Once you clone the repo, follow the below process to run/test/build:

1) Pull Dependencies
    npm install

2) Create database
    - Install mongo https://docs.mongodb.com/guides/server/install/
    - Create a db named starter https://www.mongodb.com/basics/create-database

2) Running locally
    npm run dev

3) Running unit test cases
    npm run test:unit

4) Runiing end to end test case locally
    npm run test:e2e:local
    
5) Running end to end test case on docker container
    npm run test:e2e