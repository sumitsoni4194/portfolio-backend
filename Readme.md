# Portfolio Backend API

A simple backend API for a personal portfolio website.  
It handles contact form submissions and stores messages in a database.

## Features
- Contact form API
- Stores user messages in database
- Input validation
- RESTful API design

## Tech Stack
- JavaScript
- Node.js
- Express.js
- MongoDB

## API Endpoints

### POST /api/contact
Submit a contact form message.

**Request Body:**
```json
{
  "name": "John Doe",
  "email": "john@example.com",
  "message": "Hello, I would like to connect."
}
