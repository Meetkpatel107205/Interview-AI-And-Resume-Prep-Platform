# 🤖 Interview AI — AI-Powered Interview Preparation & Resume Optimization

A full-stack **Generative AI platform** that helps job seekers prepare for specific roles by analyzing their resume against a target job description, identifying skill gaps, generating personalized interview preparation material, and creating an ATS-friendly tailored resume.

## ✨ Features

- 📄 Resume and job description analysis
- 🧠 AI-powered contextual skill gap analysis
- 🎯 Identification of overlapping and missing skills
- 💻 Role-specific technical interview questions
- 🗣️ Personalized behavioral interview questions
- 📚 AI-generated interview preparation plans
- 📝 ATS-friendly resume tailoring
- 📥 AI-generated resume PDF download
- 🔐 Secure user authentication
- 🔑 bcrypt password hashing
- 🍪 JWT-based authentication using HTTP cookies
- 🚪 JWT token blacklisting for secure logout
- ✅ Structured and validated Generative AI outputs
- ⚡ REST API integration between frontend and backend
- 🧪 API and authentication testing with Postman

## 🛠️ Tech Stack

### Frontend
- **React.js**
- **JavaScript**
- **HTML5**
- **CSS3**
- **REST API Integration**

### Backend
- **Node.js**
- **Express.js**
- **MongoDB Atlas**
- **Mongoose**

### Generative AI
- **Generative AI API**
- Prompt engineering
- Structured AI outputs
- AI response validation
- Resume and interview content generation

### Authentication & Security
- **bcrypt** — password hashing
- **JWT** — authentication and session management
- **HTTP Cookies** — secure token storage
- **Token Blacklisting** — logout and token invalidation

### Testing & Tools
- **Postman**
- **Git & GitHub**
- **npm**

## 🔄 How It Works

```text
👤 User
   ↓
📄 Upload / Provide Resume
   ↓
💼 Enter Target Job Description
   ↓
⚙️ Backend Validation
   ↓
🧠 Generative AI Analysis
   ↓
┌───────────────────────────────┐
│ Skill & Requirement Analysis  │
│ Skill Gap Identification      │
│ Role Alignment Analysis       │
└───────────────────────────────┘
   ↓
📚 Personalized Interview Prep
   ↓
💻 Technical Questions
🗣️ Behavioral Questions
📋 Preparation Plan
   ↓
📝 ATS-Friendly Resume
   ↓
📥 Generate & Download PDF
