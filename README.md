# Real-Time Chat Application

The **Real-Time Chat Application** is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides users with a seamless and secure platform for real-time communication. The application supports instant messaging, user authentication, and message history, making it ideal for both personal and professional use.

---

## Features

### **User Features**
- **Instant Messaging:** Send and receive messages in real time with WebSockets.
- **User Authentication:** Secure login and registration using JWT.
- **Message History:** View previously exchanged messages with each user.
- **User Status:** Displays online/offline status of users.
- **Responsive Design:** Fully functional on desktops, tablets, and mobile devices.

### **General Features**
- **Search Functionality:** Find users or chats easily using a search bar.
- **Real-Time Notifications:** Get notified about new messages instantly.
- **Secure Communication:** Messages are transmitted securely.

---

## Technologies Used

### **Frontend**
- **React.js:** For building a dynamic and responsive user interface.
- **CSS/TailwindCSS:** For styling and ensuring a clean, modern design.

### **Backend**
- **Node.js & Express.js:** For handling server-side logic and APIs.
- **MongoDB:** For storing user data and chat history.
- **Mongoose:** For database modeling and interaction.
- **WebSockets (Socket.IO):** For real-time communication between users.

### **Additional Tools**
- **JWT (JSON Web Token):** For secure user authentication.
- **Postman:** For API testing and documentation.
- **Git/GitHub:** For version control and collaboration.

---

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- MongoDB (local or cloud-based, e.g., MongoDB Atlas)
- Git

### Steps


# 1. Navigate to the project directory
cd RealTimeChatApp

# 2. Install dependencies for both the frontend and backend
cd client
npm install
cd ../server
npm install

# 3. Configure environment variables
# Create a .env file in the server folder and add the following:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

# 4. Start the application
# Run the backend server
cd server
npm start

# Run the frontend
cd client
npm start

# 5. Access the application
# Open your browser and go to:
http://localhost:3000
