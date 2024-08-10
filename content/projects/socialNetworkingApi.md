---
title: "Social Networking REST API"
date: "2023-03-16"
description: "Social Networking REST API using MongoDB, Nodejs, Express"
toc: true
readTime: true
autonumber: false
math: true
tags: ['backend','nodejs','express','mongodb']
showTags: false
hideBackToTop: false
---

Built this as an internship task using MongoDB, Nodejs, Express

### [Code][1]

## Overview
Task is to design and implement a RESTful API for a basic social networking application using Node.js and MongoDB. The application will support user profiles, posts (text-based), and the ability to follow other users. Focus on backend development, emphasizing MongoDB for data storage, efficient data retrieval, and data relationship management.


## Requirements

### User Profiles:
* Implement endpoints to create, update, view, and delete user profiles. Include details like username, bio, and profile picture URL, use uuid for user-ids.

### Authentication:
* Implement JWT-based authentication to secure the API. Ensure users can sign up, log in, and perform actions on behalf of their profiles.

### Posts:
* Allow users to create, view, update, and delete their posts. A post should include text content, a timestamp, and the ID of the user who created it.
* Implement an endpoint to view the latest posts from users that a given user follows.

### Following Mechanism:
* Enable users to follow and unfollow other users. Ensure there's an endpoint to retrieve the list of users a given user is following and who is following them.

### Efficient Data Retrieval:
* Use MongoDB's aggregation framework to implement efficient queries for the social feed, where users can see posts from people they follow, sorted by the most recent.

### Data Modeling:
* Design MongoDB schemas for users, posts, and follows. Consider the use of references or embedded documents for optimal performance and query efficiency.

### Security and Validation:
* Ensure input validation to prevent injection attacks and other common security vulnerabilities.
* Implement rate limiting to protect against brute force attacks.

### Testing:
* Write integration tests for your API endpoints to ensure they work as expected and handle errors gracefully.

### Documentation:
* Provide comprehensive API documentation that includes endpoint descriptions, request/response formats, and example use cases.


## Deliverables
* Source code for the API, including all models, routes, and controllers.
* MongoDB schema designs.
* A collection of integration tests.
* API documentation.
* A README file with setup instructions, including any environment variables needed and steps to get the application running.

[1]: https://github.com/0ju1c3/Nodejs-intern-assignment-3-submission
