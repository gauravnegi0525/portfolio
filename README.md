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

### For Local Development:

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

### For Hosting/Production:

1. **Set up MongoDB Atlas:**
   - Go to [MongoDB Atlas](https://www.mongodb.com/atlas)
   - Create a free account and cluster
   - Get your connection string

2. **Update Environment Variables:**
   - Set `MONGODB_URI` environment variable with your Atlas connection string
   - Or replace the placeholder in `server.js` with your actual connection string

3. **Deploy to hosting service:**
   - Upload all files to your hosting provider
   - Make sure Node.js is supported
   - Set environment variables if needed

## Database Configuration

- **Local Development**: Uses in-memory MongoDB (temporary)
- **Production**: Connects to MongoDB Atlas (persistent cloud database)
- Update the `MONGODB_URI` in `server.js` with your actual MongoDB connection string

## API Endpoints

- `POST /api/contact` - Submit contact form data
- `GET /api/contacts` - Retrieve all contact messages (for admin purposes)

## Technologies Used

- Frontend: HTML, CSS (Tailwind), JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB with Mongoose
