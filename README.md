This is my personal portfolio website
<br>
author - Gaurav Singh Negi
=======
# Portfolio

This is my personal portfolio website with a contact form that saves messages to a MongoDB database.
<br>
author - Gaurav Singh Negi

## Features

- Responsive portfolio website built with HTML, CSS, and JavaScript
- Contact form that saves messages to MongoDB database
- Express.js backend server
- Modern UI with Tailwind CSS

## Setup Instructions

1. **Install Dependencies:**
   ```bash
   npm install
   ```

2. **Install MongoDB:**
   - Download and install MongoDB from [mongodb.com](https://www.mongodb.com/try/download/community)
   - Start MongoDB service (usually runs on localhost:27017)

3. **Run the Application:**
   ```bash
   npm run dev
   ```

4. **Access the Website:**
   - Open your browser and go to `http://localhost:3000`

## Database Configuration

The application connects to MongoDB at `mongodb://localhost:27017/portfolio`. You can change this in `server.js` if needed.

## API Endpoints

- `POST /api/contact` - Submit contact form data
- `GET /api/contacts` - Retrieve all contact messages (for admin purposes)

## Technologies Used

- Frontend: HTML, CSS (Tailwind), JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB with Mongoose
