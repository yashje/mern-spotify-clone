
<h1 align="center">🎵 MERN Spotify Clone ✨</h1>

<p align="center">
A Spotify-inspired music streaming app built with the <strong>MERN stack</strong>, <strong>TypeScript</strong>, <strong>Clerk</strong> for authentication, and <strong>Cloudinary</strong> for media storage.
</p>

---

## 🚀 Features

- 🎸 Listen to music with next & previous controls  
- 🔈 Adjust volume with a smooth slider  
- 🎧 Admin dashboard to create and manage albums & songs  
- 💬 Real-time chat integrated into the app  
- 👥 See what other users are listening to in real-time  
- 👨🏼‍💼 Online/offline status indicators  
- 📊 Analytics dashboard with aggregated data  
- 🌟 And more to come...

---

## 🛠️ Tech Stack

- **Frontend**: React + Vite + TypeScript + TailwindCSS
- **Backend**: Node.js + Express + MongoDB
- **Authentication**: Clerk
- **Media Storage**: Cloudinary
- **Real-time**: WebSockets (or similar)

---

## 🔑 Environment Setup

### 📂 Backend `.env`
Create a `.env` file in the **backend** folder with the following variables:
```bash
PORT=your_port_here
MONGODB_URI=your_mongodb_connection_string
ADMIN_EMAIL=admin_email@example.com
NODE_ENV=development

CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
````

---

### 📂 Frontend `.env`

Create a `.env` file in the **frontend** folder with:

```bash
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

## 📦 Getting Started

1️⃣ Clone the repo:

```bash
git clone <repo-url>
cd mern-spotify-clone
```

2️⃣ Install dependencies:

```bash
cd backend && npm install
cd ../frontend && npm install
```

3️⃣ Setup your `.env` files as shown above.

4️⃣ Run the backend:

```bash
cd backend
npm run dev
```

5️⃣ Run the frontend:

```bash
cd frontend
npm run dev
```

---

## 📃 License

This project is open source and free to use.

---

> ✨ Built with passion by Yash.


