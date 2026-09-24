Postman API Testing Task
Overview

This repository contains the Postman collection created for API testing using the JSONPlaceholder REST API.

The collection demonstrates basic CRUD operations:

GET – Retrieve posts

POST – Create a new post

PUT – Update an existing post

DELETE – Delete a post

API Used

JSONPlaceholder API

Base URL:

https://jsonplaceholder.typicode.com

Test Cases
1. GET Posts

Method: GET

Endpoint:
/posts

Validation:

Verifies that the response status code is 200

Verifies that the response contains the expected post data

2. POST Create Post

Method: POST

Endpoint:
/posts

Request Body:

{
  "title": "Postman CRUD Test",
  "body": "Testing POST request using Postman",
  "userId": 1
}


Validation:

Verifies that the response status code is 201

Verifies that the response contains the expected title

3. PUT Update Post

Method: PUT

Endpoint:
/posts/1

Request Body:

{
  "id": 1,
  "title": "Updated Post",
  "body": "Updated using Postman",
  "userId": 1
}


Validation:

Verifies that the response status code is 200

Verifies that the post title is updated successfully

4. DELETE Post

Method: DELETE

Endpoint:
/posts/1

Validation:

Verifies that the response status code is 200

How to Run

Download the Postman collection JSON file from this repository.

Open Postman.

Import the collection.

Select the required request.

Click Send to execute the request.

Review the response and test results.

Tools Used

Postman

JSONPlaceholder REST API

GitHub

Collection

The exported Postman collection is included in this repository as a .json file.

Author

Submitted as part of the assigned API testing task.
