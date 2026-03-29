# OPSMIND 🧠

### AI-Powered SOP Intelligence System

OPSMIND is an intelligent document assistant that allows enterprises to upload Standard Operating Procedure (SOP) documents and interact with them using AI. Simply upload a PDF and start asking questions — OPSMIND will find the most relevant answers from your documents instantly.

## 🚀 Features

- 📄 PDF Upload & Processing
- 🤖 AI-Powered Chat Assistant
- 🔍 Intelligent Document Search
- 🔐 JWT Authentication (Login/Logout)
- 💬 Real-time Streaming Responses
- 📱 Clean & Modern UI

## 🛠️ Tech Stack

**Frontend:**

- React.js
- Tailwind CSS
- Framer Motion

**Backend:**

- Node.js
- Express.js
- MongoDB Atlas

**AI:**

- Google Gemini 1.5 Flash

## 📦 Installation & Setup

### Prerequisites

- Node.js installed
- MongoDB Atlas account
- Gemini API Key

### Clone the repository

```bash
git clone https://github.com/Satish397882/OPSMIND.git
cd OPSMIND
```

### Setup Backend

```bash
cd server
npm install
```

Create `.env` file in server folder:

```
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
PORT=5000
```

```bash
npm run dev
```

### Setup Frontend

```bash
cd client
npm install
npm run dev
```

## 🌐 Usage

1. Register/Login to your account
2. Upload a PDF document
3. Ask questions about the document
4. Get AI-powered answers instantly
