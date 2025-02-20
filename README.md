# Social Network API

## Description
A backend API for a social network web application where users can share thoughts, react to thoughts, and manage a friend list. Built using **MongoDB**, **Express.js**, and **Mongoose**.

## Installation
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/social-network-api.git
   cd social-network-api

2. Install Dependencies:
      - npm install

3. Start Server
      - npm run dev
      - The API will run on http://localhost:3001.

## API Routes

Users
	•	GET /api/users - Get all users
	•	GET /api/users/:userId - Get a single user
	•	POST /api/users - Create a user
	•	PUT /api/users/:userId - Update a user
	•	DELETE /api/users/:userId - Delete a user

Thoughts
	•	GET /api/thoughts - Get all thoughts
	•	GET /api/thoughts/:thoughtId - Get a single thought
	•	POST /api/thoughts - Create a thought
	•	PUT /api/thoughts/:thoughtId - Update a thought
	•	DELETE /api/thoughts/:thoughtId - Delete a thought

Reactions
	•	POST /api/thoughts/:thoughtId/reactions - Add a reaction
	•	DELETE /api/thoughts/:thoughtId/reactions/:reactionId - Remove a reaction

Friends
	•	POST /api/users/:userId/friends/:friendId - Add a friend
	•	DELETE /api/users/:userId/friends/:friendId - Remove a friend

License

This project is licensed under the MIT License.
