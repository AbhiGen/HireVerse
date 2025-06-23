# 🧠 HireVerse

> **Your AI-powered mock interview platform** for role-based dynamic preparation with real-time feedback, intelligent assessment, and a personalized dashboard.

---

## 📌 Project Description

HireVerse is an AI-powered mock interview platform that provides tailored interview experiences based on a candidate’s selected role, tech stack, and experience level.  
It integrates 🎤 speech-to-text, 🗣️ text-to-speech, and 🤖 AI-driven dynamic question generation to simulate real interviews.

---

## 🚀 Features

### 🔐 Authentication & User Management
- Secure sign-in/sign-up with Clerk
- Personalized user sessions and data

### 🧑‍💻 AI Mock Interviews
- Role & experience-based dynamic questions
- Covers:
  - ⚙️ DSA (LeetCode-level)
  - 📐 Aptitude
  - 📖 Verbal Reasoning
  - 🏢 Company-specific behavioral rounds

### 🔊 Real-Time Communication
- 🎙️ Text-to-Speech: AI reads out questions
- 🧏‍♂️ Speech-to-Text: Converts spoken answers into text

### 📊 Dashboard & Feedback
- Tracks 🏅 Best, 📉 Average, and 🕓 Recent scores
- Question-wise feedback and overall performance insights

### 📚 Practice & Assessment
- Topic-wise syllabus for:
  - DSA
  - Aptitude
  - Verbal Reasoning
- Company-wise behavioral questions
- ⏱️ Time-bound assessments

### 💰 Pricing & Subscription
- 🧾 Pricing page
- 💎 Premium access with extra features
- 🆓 7-day Free Trial
- 💳 RazorPay (test mode) payment gateway

---

## 📁 Project Structure
```
AI-MOCK-INTERVIEW-BUILDVERSE/
├── backend/
│ ├── config/ # DB & Clerk setup
│ ├── controllers/ # Logic handlers
│ ├── models/ # MongoDB schemas
│ ├── routes/ # API routes
│ ├── .env # Environment vars
│ └── server.js # Backend entry point
│
├── frontend/
│ ├── public/
│ │ └── models/ # face-api.js models
│ └── src/
│ ├── api/ # Axios config
│ ├── assets/ # Icons & images
│ ├── components/ # UI Components
│ ├── pages/ # Page views
│ ├── utils/ # Helper functions
│ ├── App.jsx # App router
│ └── main.jsx # Entry point
│
├── .gitignore
├── LICENSE
├── package.json
└── README.md

yaml
Copy
Edit
```
---

## 📄 Pages Directory
```
pages/
├── AboutUs.jsx / .css
├── AptitudeAndVerbal.jsx / .css
├── BehaviourPage.jsx / .css
├── Dashboard.jsx / .css
├── HowItWorks.jsx / .css
├── HrOrUser.jsx / .css
├── Interview.jsx / .css
├── InterviewQuestions.jsx / .css
├── Profile.jsx / .css
├── Questions.jsx / .css
├── Upgrade.jsx / .css
```

---

## 💻 Tech Stack

### 🔙 Backend
- Node.js & Express.js
- MongoDB
- Clerk (Authentication)
- OpenAI / Gemini API

### 🌐 Frontend
- React.js
- Tailwind CSS
- React Router

### 🧠 AI & Voice
- Text-to-Speech
- Speech-to-Text
- AI-Powered Q&A (OpenAI/Gemini)

### 💳 Payments
- RazorPay (Test Mode)

### 🚀 Deployment
- [Render](https://render.com/) (Frontend + Backend)

---

## 🔧 Future Improvements
- 🎥 Session recording and HR tools
- 📄 Resume analysis
- 🏆 Gamified Leaderboard
- 📱 Mobile app integration
- 🌐 Multi-language support

---

## 👨‍💻 Contributors

**Team HelloWorld:**
- 👨‍💻 Abhiram Bikkina  
- 👨‍💻 Tharun Kumar Reddy  
- 👨‍💻 Dhinesh Veera Bhargav  
- 👨‍💻 Pavan Vignesh  

---

> 💡 *Empower your interview prep with intelligence. Practice smart, interview smarter.*

