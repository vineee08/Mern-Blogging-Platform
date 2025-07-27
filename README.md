# Mern-Blogging-Platform
A full-stack blog application that allows users to write, edit, and delete blogs using a rich text editor. Users can like and comment on posts, manage their profiles, and explore content through search and filters. Admins have access to manage blogs and user activity.

---

## 🚀 Features

- 🧑‍💻 **User Authentication (JWT-based)**
- ✍️ **Create / Edit / Delete Blogs**
- 🖋️ **Rich Text Editor with React Quill**
- 💬 **Comments and Like System**
- 🔍 **Search and Category Filter**
- 👤 **User Profile Management**
- 🛠️ **Admin Dashboard for Monitoring**
- 📱 **Fully Responsive UI with Tailwind CSS**

---

## 🛠️ Tech Stack

### 🔹 Frontend
- React.js
- React Quill
- Tailwind CSS
- React Router DOM
- Axios

### 🔹 Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (Authentication)
- Multer / Cloudinary (for image uploads)

---

## 📁 Project Structure

```

mern-blog-app/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.js
│   │   └── index.js

````

---

## ⚙️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/mern-blog-app.git
````

### 2. Backend Setup

```bash
cd backend
npm install
# Add your MongoDB URI and JWT_SECRET in .env
npm start
```

### 3. Frontend Setup

```bash
cd frontend
npm install
npm start
```

### 4. Visit App

```
Frontend: http://localhost:3000
Backend:  http://localhost:5000
```

---

## ✨ Future Enhancements

* 📂 File/image uploads in blog content
* 🧠 AI-assisted blog writing suggestions
* 🔔 Notifications for likes/comments
* 📊 Analytics dashboard for authors/admins

---
