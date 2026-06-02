# 📸 Instagram Clone

A full-stack Instagram Clone built to replicate the core features of Instagram, including user authentication, post creation, likes, comments, user profiles, and real-time interactions.

## 🚀 Features

### Authentication

* User registration and login
* Secure password hashing
* JWT-based authentication
* Protected routes

### User Profiles

* Create and update profile information
* Upload profile pictures
* View user posts
* Follow and unfollow users

### Posts

* Create posts with images and captions
* Edit and delete posts
* View feed from followed users
* Responsive image gallery

### Social Interactions

* Like and unlike posts
* Add and delete comments
* Follow and unfollow users
* Real-time updates

### Search

* Search users by username
* Discover new accounts

### Responsive Design

* Mobile-friendly interface
* Tablet and desktop support
* Modern Instagram-inspired UI

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Redux / Context API
* React Router
* Axios
* CSS / Tailwind CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* Bcrypt

### Storage & Deployment

* Cloudinary (Image Storage)
* Vercel / Netlify (Frontend)
* Render / Railway (Backend)
* MongoDB Atlas (Database)

---

## 📂 Project Structure

```bash
instagram-clone/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   ├── context/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── config/
│   └── server.js
│
├── .env
├── README.md
└── package.json
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/instagram-clone.git
cd instagram-clone
```

### 2. Install Dependencies

#### Frontend

```bash
cd client
npm install
```

#### Backend

```bash
cd ../server
npm install
```

### 3. Configure Environment Variables

Create a `.env` file inside the server directory:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4. Run the Application

#### Start Backend

```bash
npm run server
```

#### Start Frontend

```bash
npm start
```

The application will be available at:

```bash
Frontend: http://localhost:3000
Backend:  http://localhost:5000
```

---

## 📸 Screenshots

Add screenshots of your application here:

* Login Page
* Home Feed
* User Profile
* Create Post
* Comments Section

---

## 🔐 API Endpoints

### Auth

```http
POST /api/auth/register
POST /api/auth/login
GET  /api/auth/user
```

### Users

```http
GET    /api/users/:id
PUT    /api/users/update
POST   /api/users/follow/:id
DELETE /api/users/unfollow/:id
```

### Posts

```http
POST   /api/posts
GET    /api/posts/feed
GET    /api/posts/:id
PUT    /api/posts/:id
DELETE /api/posts/:id
```

### Comments

```http
POST   /api/comments/:postId
DELETE /api/comments/:commentId
```

---

## 🧪 Future Improvements

* Stories feature
* Direct messaging
* Notifications
* Reels support
* Real-time chat with WebSockets
* Dark mode
* Push notifications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgements

* Inspired by Instagram
* Built for learning full-stack web development
* Thanks to the open-source community
