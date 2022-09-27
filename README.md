# social

Social Media API

# Description

A REST API for a social media app. Built with Express, Mongoose, and MongoDB. 

Demo video is shown using Insomnia

Video Link: https://drive.google.com/file/d/13bB2Cl28XUZsNVw7PNZk-CK4--HZ--Vm/view

# User Story

As a social media startup, I want an API for my social network that uses a NoSQL database so that my website can handle large amounts of unstructured data.

# Usage

1. Make sure you have MongoDB installed on your machine (if you don't, follow the instructions on the MongoDB Website)
2. Clone the repo
3. Install dependencies with npm -i
4. Run npm start to run the server and make the API live
5. Use your browser or an app like Insomnia to test the REST API.

# Models

1. index.js
2. Reaction.js
3. User.js

# Endpoints

# User:

Delete, Update, Create, Find


# Thought

Delete, Update, Create, Find

# Reaction (used as a subdocument in Thought)

Delete, Post

# Packages

express
mongoose

# Other Prompts

Delete a user: DELETE /api/users/:id
Add a friend: PUT /api/users/:userId/friends/:friendId
Delete a friend: DELETE /api/users/:userId/friends/:friendId

# Thought

Get all thoughts: GET /api/thoughts
Create a thought: POST /api/thoughts
Get thought by ID: GET /api/thoughts/:id
Update a thought: PUT /api/thoughts/:id
Delete a thought: DELETE /api/thoughts/:id

# Reaction (used as a subdocument in Thought)

Add a reaction: PUT /api/thoughts/:id/reactions

# Packages

express
mongoose

# Questions

Justin Morrow
https://github.com/Justin-Morrow/
