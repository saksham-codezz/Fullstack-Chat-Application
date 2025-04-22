# 💬 Fullstack Chat Application

A secure, real-time one-to-one chat app built with the MERN stack. Features include instant messaging, user authentication, profile customization, and image sharing — all with a modern, responsive UI.

## 🚀 Features

- **User Authentication**: Sign up and log in with hashed passwords using **bcryptjs** and secure JWT-based sessions.
- **One-to-One Messaging**: Real-time private chat powered by **Socket.IO**.
- **Profile Pictures**: Upload avatars with **Cloudinary**.
- **Image Sharing**: Share images directly in chat messages (Cloudinary-backed).
- **Responsive UI**: Sleek interface built with **Tailwind CSS** and **DaisyUI**.
- **Online Presence**: See who’s online in real time.

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS, DaisyUI
- **Backend**: Node.js, Express.js
- **Database**: MongoDB + Mongoose
- **Authentication**: JWT + bcryptjs
- **Real-Time**: Socket.IO
- **Media Uploads**: Cloudinary

## Setup .env file

Create a `.env` file in the backend directory and add the following variables:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
