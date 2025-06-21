# Memories App 📸

Memories App is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that allows users to create, share, and manage memorable moments. Users can post memories with images, titles, messages, tags, and interact with posts through likes and deletion. The project demonstrates modern web development practices, modular code structure, and seamless integration between frontend and backend.

## ✨ Features

- 📝 Create, edit, and delete memory posts with images, tags, and messages
- 📋 View all memories in a responsive, card-based layout
- 👍 Like and interact with posts in real-time
- 🔍 Filter and organize posts using tags
- ⚡ Fast and responsive UI built with React and Material-UI
- 🔗 RESTful API backend with Express.js and MongoDB
- 🗂️ Modular Redux state management for scalable frontend logic

## 🏆 Achievements

- 🚀 Built a fully functional CRUD application using the MERN stack
- 🧩 Designed a modular codebase with clear separation of concerns between client and server
- 🎨 Implemented a responsive and visually appealing UI with Material-UI
- 🔄 Enabled real-time updates and smooth user experience with Redux and React hooks
- 🛠️ Applied best practices in API design, error handling, and state management
- 📦 Deployed and tested the app in a production-like environment

## 🗂️ Project Structure

- **client/**: React frontend with Material-UI, Redux, and modular components
  - `src/components/Posts/`: Display and manage all posts
  - `src/components/Form/`: Create and edit memory posts
  - `src/actions/`, `src/reducers/`: Redux logic for state management
  - `src/api/`: Axios API calls to backend
- **server/**: Node.js/Express backend with MongoDB
  - `routes/posts.js`: API endpoints for posts
  - `controllers/posts.js`: Business logic for CRUD operations
  - `models/postMessage.js`: Mongoose schema for posts

## 🚀 Getting Started

1. Clone the repository and install dependencies for both client and server:
   ```bash
   git clone https://github.com/your-username/Memories-App-master.git
   cd Memories-App-master
   cd server && npm install
   cd ../client && npm install
   ```
2. Start the backend server:
   ```bash
   cd ../server
   npm start
   ```
3. Start the frontend React app:
   ```bash
   cd ../client
   npm start
   ```
4. Open [http://localhost:3000](http://localhost:3000) to use the app.

---

Whether you're learning the MERN stack or looking for a reference implementation of a modern CRUD app, Memories App provides a practical, real-world example of full-stack development. Happy coding!
