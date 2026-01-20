 

Make sure you have installed:
Node.js (v18 or later)
npm
Groq API Key (Free)

 # Go to backend folder
 cd backend
# Install dependencies
npm install
# Create .env file
Create a file named .env inside backend/ and add:
GROQ_API_KEY=your_groq_api_key_here
# Start backend server
node server.js / npm start
Backend will run at:
(http://localhost:3000)

# Go to frontend folder
cd frontend
# Install dependencies
npm install
# Start frontend
npm run dev
# Frontend will run at:
http://localhost:5173

# Connect Frontend to Backend
const API_URL = "http://localhost:3000";
