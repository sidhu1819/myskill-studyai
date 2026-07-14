# 📚 StudyAI – Smart AI Study Companion & Quiz Generator

## 🚀 Overview

StudyAI is a full-stack, AI-powered study companion designed to help students transform their study materials into structured and interactive learning resources.

Students can upload PDF files, DOCX documents, or plain text, and StudyAI uses Generative AI to automatically generate summaries, interactive flashcards, practice quizzes, and personalized 7-day study plans.

The platform also analyzes quiz performance to identify weak topics and helps students improve their exam preparation through adaptive learning and performance analytics.

StudyAI integrates the Groq API with the Llama 3.3 70B Versatile model to provide fast and intelligent AI-generated educational content.

The application follows a three-tier architecture consisting of a React.js frontend, Python Flask REST API backend, and Firebase Firestore cloud database. A local JSON storage fallback is also supported when Firebase credentials are unavailable.

## ✨ Key Features

- 📄 Upload study materials in PDF, DOCX, or plain text format
- 🤖 AI-powered structured summary generation
- 🧠 Interactive flashcard generation with difficulty levels
- 📝 AI-generated MCQ, True/False, and Short Answer quizzes
- 📊 Automatic quiz evaluation and weak-topic identification
- 📅 Personalized 7-day adaptive study planner
- 📈 Performance analytics dashboard
- ☁️ Firebase Firestore cloud database integration
- 💾 Automatic local JSON storage fallback
- 📱 Responsive and modern user interface
- 🚀 Full-stack application deployed on Render

## 🛠️ Tech Stack

**Frontend**
- React.js
- JavaScript
- Axios
- Chart.js
- HTML5
- CSS3

**Backend**
- Python
- Flask
- Flask-CORS
- REST APIs

**Generative AI**
- Groq API
- Llama 3.3 70B Versatile
- Prompt Engineering

**Database**
- Firebase Firestore
- Local JSON Storage Fallback

**File Processing**
- PyPDF2
- python-docx

**Deployment & Tools**
- Render
- Git
- GitHub
- Postman
- VS Code

## 🔄 Application Workflow

1. User uploads study material (PDF, DOCX, or Text).

2. Flask backend extracts and processes the document content.

3. The processed content is sent to the Groq API.

4. Llama 3.3 70B generates educational content.

5. Students can generate:

   - AI Summaries
   - Interactive Flashcards
   - Practice Quizzes
   - Personalized Study Plans

6. Quiz results are analyzed to identify weak topics.

7. Weak topics are used to generate adaptive study schedules.

8. Generated content and user data are stored using Firebase Firestore or the local JSON fallback.

## 🎯 Project Objective

The objective of StudyAI is to demonstrate how Generative AI, cloud technologies, and modern full-stack web development can be combined to create an intelligent educational platform.

The project aims to reduce the time students spend manually creating notes, flashcards, quizzes, and study schedules while providing a personalized and interactive learning experience.

## 🔗 Project Links

- **Live Application:** https://studyai-frontend-mdph.onrender.com/
- **Backend API:** https://studyai-ce2q.onrender.com/
- **Demo Video:** https://youtu.be/T30jUnjKP1c
- **GitHub Repository:** https://github.com/sidhu1819/StudyAI

## 👨‍💻 Developer

**Medapati Siddhartha Reddy**

Full-Stack Developer | Generative AI & Data Science Enthusiast

## 📄 Project Context

StudyAI was developed as part of the APSCHE Internship Programme in the domain of Full-Stack Web Development and Generative AI.

The project demonstrates practical experience in REST API development, Generative AI integration, prompt engineering, cloud database management, responsive frontend development, application testing, and full-stack cloud deployment.
