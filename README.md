# 🎬 Vidly – Full Stack Video Sharing Platform

Vidly is a full-stack video sharing platform inspired by YouTube. It allows users to create accounts, upload and watch videos, interact with other users, and manage their own channels.

The project is built using JavaScript, Node.js, Express.js, MongoDB, and a custom frontend.

# Live Demo: https://frontend-7l86.onrender.com 

## 🚀 Features

### 🔐 Authentication & User Management
- User registration and login
- Secure authentication using JWT
- Password hashing using bcrypt
- Update account details and profile images
- Watch history management

### 🎥 Video Management
- Upload videos and thumbnails
- Watch videos
- Search videos
- Pagination and dynamic sorting
- Update and delete videos
- Toggle video publishing status
- Track video views

### 💬 Social Features
- Comment on videos
- Like and unlike videos
- Subscribe and unsubscribe to channels
- View channel profiles and statistics
- Manage playlists
- Create and manage tweets

### ☁️ Media Storage
- Cloudinary integration for video and image uploads

## 🛠️ Tech Stack

**Frontend**
- HTML
- CSS
- JavaScript

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- bcrypt
- Multer

**Other Tools & Services**
- Cloudinary
- Git & GitHub
- Postman

## 📁 Project Structure

```text
Vidly/
│
├── frontend/
│   ├── css/
│   ├── js/
│   ├── config.js
│   ├── index.html
│   ├── server.js
│   └── package.json
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middlewares/
│   │   └── utils/
│   │
│   └── package.json
│
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/AnujKaririya/Vidly.git
```

### 2. Navigate to the project

```bash
cd Vidly
```

### 3. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the backend directory and configure your environment variables.

Example:

```env
PORT=3000
MONGODB_URI=your_mongodb_connection_string
DB_NAME=your_database_name
CORS_ORIGIN=http://localhost:5173

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

Use the exact variable names expected by your backend configuration.

Start the backend server:

```bash
npm run dev
```

### 4. Setup Frontend

Open another terminal:

```bash
cd frontend
npm install
```

Configure the frontend API URL in `config.js` if required.

Start the frontend using the script configured in its `package.json`.

## 🔗 API Endpoints

The backend exposes REST APIs under `/api/v1`.

| Module | Endpoint |
|---|---|
| Users | `/api/v1/users` |
| Videos | `/api/v1/videos` |
| Subscriptions | `/api/v1/subscriptions` |
| Comments | `/api/v1/comments` |
| Likes | `/api/v1/likes` |

Additional modules include playlists and tweets.

## 🔒 Environment Variables

Never upload your `.env` file, API keys, database credentials, or JWT secrets to GitHub.

Add `.env` to your `.gitignore` file.

## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

- Building REST APIs using Express.js
- MongoDB database design and aggregation pipelines
- JWT-based authentication and authorization
- Middleware implementation
- File uploads using Multer
- Cloudinary integration
- API testing using Postman
- Connecting frontend and backend
- Git and GitHub version control

## 👨‍💻 Author

**Anuj Kumar**

- GitHub: [@AnujKaririya](https://github.com/AnujKaririya)

---

⭐ If you find this project interesting, consider giving it a star!
