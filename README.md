# DSA-CONTEST-PROJECT 🚀

This is a Batman-themed coding sanctuary where developers train like the League of Shadows. Built for the **ChaiCode LeetLab Challenge**, this platform combines the intensity of Gotham with cutting-edge web technologies to deliver an immersive coding experience.

As a passionate Batman fan, I wanted to create something unique that goes beyond conventional coding platforms. Every component was crafted from scratch, backgrounds designed in Figma, and animations carefully implemented with Framer Motion to create a truly immersive experience.

---

## ✨ Key Features

### 🏗️ Core Platform

- **Real-time Collaborative Editing** – Code together with fellow vigilantes using Liveblocks  
- **Self-hosted Judge0** – Execute code in multiple languages on Azure VM infrastructure  
- **Custom Code Editor** – Monaco-based editor with syntax highlighting and dark/light themes  
- **Dynamic Problem Creation** – AI-powered problem generation with multiple test cases  

### 🤖 AI Integration

- **Alfred AI Assistant** – Contextual coding help using Groq API  
- **Intelligent Hints** – Get guidance without spoiling the solution  
- **Code Review** – AI-powered code analysis and optimization suggestions  
- **Problem Generation** – Create custom DSA problems with AI assistance  

### 👤 User Experience

- **JWT Authentication** – Secure login/signup with refresh token rotation  
- **Progress Tracking** – Contribution graphs, streaks, and detailed statistics  
- **Problem Organization** – Create and manage DSA playlists  
- **Revision System** – Mark problems for later review  
- **Submission History** – Track all attempts with performance metrics  

### 🎨 UI/UX Excellence

- **Batman-themed Design** – Immersive dark aesthetic with Gotham vibes  
- **Custom Components** – Built from scratch without external UI libraries  
- **Smooth Animations** – Framer Motion powered interactions  
- **Dark/Light Mode** – Seamless theme switching  

---

## 🛠️ Tech Stack

### Frontend

- **React**
- **Tailwind CSS**
- **Framer Motion**
- **Monaco Editor**
- **Liveblocks**
- **React Hook Form + Zod**
- **Zustand**

### Backend

- **Node.js + Express**
- **PostgreSQL**
- **Prisma ORM**
- **Judge0 API**
- **Groq API**
- **JWT**

### DevOps & Infrastructure

- **Docker**
- **NGINX**
- **PM2**
- **Azure VM**

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- PostgreSQL 14+
- Docker (optional)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/AtharvNarale07/DSA-Contest-Project.git
   cd DSA-Contest-Project/backend
   npm install


# Setup environment variables
cp .env.sample .env
# Edit .env with your database and API credentials

# Run database migrations
npx prisma migrate dev
npx prisma generate

# Start the server
npm run dev
cd frontend
npm install

# Start the development server
npm run dev
DATABASE_URL="postgresql://username:password@localhost:5432/prakashdeshmuk"
JWT_SECRET="your-super-secret-jwt-key"
JWT_REFRESH_SECRET="your-refresh-token-secret"
GROQ_API_KEY="your-groq-api-key"
JUDGE0_API_URL="your-judge0-instance-url"
LIVEBLOCKS_SECRET_KEY="your-liveblocks-secret"


prakashdeshmuk/
├── frontend/                 # React frontend application
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Page components
│   │   ├── store/           # Zustand state management
│   │   ├── styles/          # CSS and styling
│   │   └── libs/            # Utility functions
│   └── public/              # Static assets
├── backend/                 # Node.js backend API
│   ├── src/
│   │   ├── controllers/     # API route handlers
│   │   ├── middleware/      # Express middleware
│   │   ├── routes/          # API routes
│   │   ├── libs/            # Utility libraries
│   │   └── prisma/          # Database schema
