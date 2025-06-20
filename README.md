# 🐦 Twitter Clone (MERN Stack)

A full-stack Twitter clone built using the MERN stack (MongoDB, Express, React, Node.js). This project mimics Twitter's core functionality including tweeting, liking, following, and user authentication — designed to be responsive and production-grade.

🌐 Live Demo
👉 Check it out here: https://twitter-clone1-nw8v.onrender.com

## 🚀 Features
🔐 Authentication  
User signup/login with JWT  
📝 Tweets  
Post, delete, like, and retweet  
👥 User Profiles  
Follow/unfollow users  
🧵 Feed  
Timeline populated by followed users  

### 🛠 Tech Stack
Frontend	Backend	Database	Misc  
React.js	Node.js	MongoDB	JWT  
### 📂 Project Structure
/client      → React frontend  
/server      → Node + Express API backend  
## ⚙️ Getting Started

### Clone the project
git clone https://github.com/yourusername/twitter-clone-mern.git
cd twitter-clone-mern

### Backend setup
<pre>cd server
npm install
npm run dev </pre>

### Frontend setup
<pre>cd ../client
npm install
npm start</pre>
  
### 🔑 Environment Variables
<pre>.env (server)
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_secret_key
.env (client)
REACT_APP_API_URL=http://localhost:5000</pre>

### 🧪 Future Enhancements
Image uploads in tweets  
Notifications system  
Direct messaging  
Threaded replies  
Better accessibility & error handling   
