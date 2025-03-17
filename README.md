# Full-stack-blog-application

## 📝 Overview
This is a full-stack blog application built using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It allows users to create, read, update, and delete blog posts with authentication and authorization features.

## ✨ Features
- User authentication (Sign Up, Login, Logout) using JWT
- Create, edit, delete, and view blog posts
- Rich text editor for writing blogs
- Image upload for blog posts
- User profiles with bio and avatar
- Like and comment functionality
- Responsive UI with modern design

## 🛠️ Tech Stack
### Frontend:
- React.js (Vite for fast development)
- Tailwind CSS for styling
- React Router for navigation
- Axios for API requests

### Backend:
- Node.js & Express.js
- MongoDB with Mongoose for database management
- JSON Web Token (JWT) for authentication
- Multer for image uploads
- bcrypt.js for password hashing

## 🎯 Installation & Setup
### Prerequisites
Make sure you have installed the following:
- Node.js (LTS version)
- MongoDB (Local or Atlas)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/swatiiyadawar/BlogApplication.git
cd blog-app-mern
```

### 2️⃣ Backend Setup
```bash
cd backend
npm install
```

#### Configure Environment Variables
Create a `.env` file in the `backend` directory and add:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

#### Start Backend Server
```bash
npm run dev
```

### 3️⃣ Frontend Setup
```bash
cd ../frontend
npm install
```

#### Start Frontend
```bash
npm run dev
```

## 🚀 Usage
1. Register or log in with an account.
2. Create new blog posts with images and rich text.
3. Like, comment, and interact with other blogs.
4. Edit or delete your own blog posts.

## 📂 Folder Structure
```
blog-app-mern/
│-- backend/  # Express.js backend
│   │-- models/  # Mongoose models
│   │-- routes/  # API routes
│   │-- controllers/  # Business logic
│   │-- middleware/  # Authentication & error handling
│-- frontend/  # React frontend
│   │-- src/components/  # UI components
│   │-- src/pages/  # Page views
│   │-- src/context/  # Global state management
│   │-- src/utils/  # Utility functions
```

## 📌 Future Enhancements
- Implement pagination for blog listing
- Add social media sharing
- Implement categories and tags for blogs
- Enhance UI/UX with animations

## 🛡️ License
This project is licensed under the MIT License.

## 🤝 Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## 💡 Contact
For any queries, reach out to me at swatiyadawar29@gmail.com.



