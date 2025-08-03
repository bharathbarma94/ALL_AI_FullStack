# 🧠 ALL_AI - Full Stack AI Toolkit

ALL_AI is a full-stack AI-powered web application that offers a suite of creative and productivity tools powered by OpenAI, Google Gemini, and ClipDrop. Users can generate blog content, images, remove backgrounds, review resumes, and more—all from a unified dashboard.

---

## 🚀 Features

- ✍️ **Write Articles** using AI prompts
- 🧠 **Generate Blog Titles** from topic ideas
- 🎨 **Create AI-Generated Images**
- 🧼 **Remove Backgrounds** from images
- ❌ **Remove Objects** from pictures
- 📄 **AI-Powered Resume Review**
- 🌐 **Community Dashboard** of AI creations
- 🔒 **User Authentication** with Clerk

---

## 📦 Tech Stack

### Frontend
- **React.js**
- **Vite** (for faster dev server)
- **Tailwind CSS**
- **Clerk** for authentication
- **Axios** for HTTP requests

### Backend
- **Node.js + Express**
- **OpenAI API**, **Google Gemini API**, **ClipDrop API**
- **Cloudinary** for image uploads
- **Neon PostgreSQL** for data persistence
- **dotenv**, **CORS**, **Multer**

---

## 🛠️ Project Structure

QuickAI-Full-Stack/
├── client/ # React frontend (Vite-based)
│ ├── src/
│ ├── pages/ # Page-level views like Dashboard, BlogTitles, etc.
│ ├── components/ # Reusable UI components
│ └── .env # VITE_BASE_URL
│
├── server/ # Express backend
│ ├── routes/
│ ├── controllers/
│ ├── server.js # Entry point
│ └── .env # API Keys & DB URL
