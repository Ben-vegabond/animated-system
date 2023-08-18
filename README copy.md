
## Description.

The NoSQL Social Network API is a Node.js-based application programming interface (API) designed for performing Create, Read, Update, and Delete (CRUD) operations on data models related to social networking. This API leverages a NoSQL database to manage various data models such as friends, users, thoughts, and reactions. These models can be accessed individually by their respective IDs or collectively. Developed using Node.js and Mongoose, the API offers a streamlined and scalable approach to managing social networking data, eliminating the limitations posed by conventional relational databases.



## Acceptance Criteria:
```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```


## Usage Instructions:

1. Repository: Open documentation run 'npm i' and update '.env'.
2. Create a .env file in the root directory of the project and add the following variables:
3. Once the server is running, use a tool like Insomnia to test the API endpoints. 
4. Use Insomnia to test http://localhost:3001 with the following route end points API GET, POST, PUT, and DELETE routes for categories, products, and tags, ensuring successful creation, updating, and deletion of data in the database.

#### Available Endpoints:

1. GET /api/users - get all users
2. GET /api/users/:userId - get a single user by ID
3. POST /api/users - create a new user
4. PUT /api/users/:userId - update a user by ID
5. DELETE /api/users/:userId - delete a user by ID
6. GET /api/thought - get all thought
7. GET /api/thought/:thoughtId - get a single thought by ID
8. POST /api/thought - create a new thought
9. PUT /api/thought/:thoughtId - update a thought by ID
10. DELETE /api/thought/:thoughtId - delete a thought by ID
11. POST /api/thought/:thoughtId/reactions - add a reaction to a thought
12. DELETE /api/thought/:thoughtId/reactions/:reactionId - remove a reaction from a thought
13. POST /api/users/:userId/friends/:friendId - add a friend to a user's friend list
14. DELETE /api/users/:userId/friends/:friendId - remove a friend from a user's friend list


## Built With:
- Saiyan Pride
- JSON: [JSON](https://www.npmjs.com/package/json)
- Dynamic JavaScript
- Mongoose: [7.0.3](https://www.npmjs.com/package/mongoose)
- Express: [4.18.2](https://www.npmjs.com/package/express)
- Node.js: [16.18.1](https://nodejs.org/en/blog/release/v16.18.1/)
- Insomnia: [by Kong](https://insomnia.rest/)
- MongoDB: [Website](https://www.mongodb.com/)
- Nodemon: [2.0.12](https://www.npmjs.com/package/nodemon/v/2.0.12)
- License Badge: [Shields.io](https://shields.io/)
- Visual Studio Code: [Website](https://code.visualstudio.com/)


## License & Copyright ©
  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [Open Source Initiative Link](https://opensource.org/licenses/MIT)

