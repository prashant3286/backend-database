### Overview
This task is to create a backend service where it can communicate with three different database according to the versioning. I have used the Dependency Injection Desing pattern to build this service. You can have a look through the Process and run it for your understanding.

### Technologies

Backend Language and Frameworks:
1. Node.js
2. Express.js

Object Relational Mapper(ORM):
1. Sequelize

Databases:
1. SQLite: We used SQLite database for the v1 route
2. MongoDB: We used MongoDB database for the v2 route
3. PostgreSQL: We used PosrgreSQL database for the v3 route


### Installation Process
Step1: To install, please go the root directory and enter the command `npm install`.

Step2: Make sure that MongoDB and PostgreSQL are installed and configured properly.


### Run the project
Step1: when you install all the necessary package, please go to the root directory and enter the command node seed-data.js. 
It will seed the data into the respective databases.

Step2: Now, go to the root directory and enter the command node index.js. It will run our app in 5000 port.

### APIs
Endpoint: `http://localhost:5000/api/v1/users`
This API with v1 will get the data from SQLite database.

Endpoint: `http://localhost:5000/api/v2/users`
This API with v2 will get the data from MongoDB database.

Endpoint: `http://localhost:5000/api/v3/users`
This API with v3 will get the data from PostgreSQL


### Quick Look of Techncal Assesment: