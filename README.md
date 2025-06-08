# feedback-app
A full-stack feedback app using React, Node.js, Express, and MongoDB. Users submit validated feedback with star ratings via a responsive, accessible UI. It features a REST API, real-time validation, and secure data handling. Perfect for collecting and managing user feedback efficiently. 

Features
Responsive UI with React and Bootstrap

Star rating component with keyboard accessibility

Real-time validation of inputs (email, rating, required fields)

RESTful API for submitting and retrieving feedback

MongoDB database integration with Mongoose

Secure CORS handling and environment variable configuration

Easy deployment with environment-aware API endpoints


Setup environment variables:

Create a .env file inside the server folder with:
PORT=5000
MONGO_URI=your_mongodb_connection_string

Create a .env file inside the client folder with:
REACT_APP_API_URL=http://localhost:5000/api/feedback


Usage
Run the backend:
cd server
npm start
Run the frontend:
cd client
npm start



API Endpoints
POST /api/feedback — Submit feedback

GET /api/feedback — Retrieve all feedbacks


Deployment
Deploy backend on services like Render cloud provider.

Deploy frontend on Vercel hosting platform.

Update REACT_APP_API_URL in client .env to point to the live backend URL.
