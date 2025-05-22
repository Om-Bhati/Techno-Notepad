<h1 align="center">📝 Techno Notepad ✨</h1>

![Demo App](/frontend/public/image.png)

TechnoNotes is a modern and intuitive note-taking application built with the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to create, edit, and organize their notes efficiently, helping improve productivity and information management.

![Add Note](/frontend/public/addNote.png)
![View Note](/frontend/public/viewNote.png)
---

## 🚀 Features

- 🧱 Full-Stack App Built with the MERN Stack (MongoDB, Express, React, Node)
- ✨ Create, Update, and Delete Notes with Title & Description
- 📁 Organize notes with tags or categories
- 🛠️ Build and Test a Fully Functional REST API
- 🔐 Rate Limitting using upstash
- 🌐 Responsive UI for desktop and mobile
- ☁️ Cloud-ready and easily deployable
- 📦 Deployment

---

## 🛠 Tech Stack

**Frontend:**
- React
- Daisy UI
- Axios
- CSS / Tailwind / Styled Components

**Backend:**
- Node.js
- Express.js
- MongoDB & Mongoose
- Upstash
- dotenv for environment variables

---

### Prerequisites
- Node.js & npm
- MongoDB (local or cloud)


## 🧪 .env Setup

### Backend (`/backend`)

```
MONGO_URI=<your_mongo_uri>

UPSTASH_REDIS_REST_URL=<your_redis_rest_url>
UPSTASH_REDIS_REST_TOKEN=<your_redis_rest_token>

NODE_ENV=development
```

## 🔧 Run the Backend

```
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```
cd frontend
npm install
npm run dev
```