# CareerFit – AI-Powered Resume Builder & Job Matching System

**CareerFit** is an AI-powered career assistance platform designed to help job seekers understand how well their resumes match different job opportunities.

Users can upload their resumes, analyze their skills, identify skill gaps, and discover suitable job opportunities based on their profiles.

The goal of CareerFit is to make the job application process smarter, easier, and more personalized.

## 🚀 Project Overview

Finding the right job is not just about applying to multiple openings. It is about understanding whether your skills and experience match the requirements of a particular role.

CareerFit aims to solve this problem by providing:

- Resume analysis using AI.
- Automated skill extraction.
- Job matching based on resume information.
- Job fit percentage for different opportunities.
- Skill gap identification.
- Personalized resume improvement suggestions.

## ✨ Key Features

### 1. User Authentication
- User registration and login.
- Secure password hashing.
- JWT-based authentication.
- Protected user dashboard.

### 2. Resume Upload
- Upload resumes in PDF and DOCX formats.
- Extract information from uploaded resumes.
- Analyze skills, education, projects, and experience.

### 3. AI-Powered Resume Analysis
- Automatic skill extraction.
- Resume content analysis.
- Identification of relevant qualifications.
- Personalized improvement recommendations.

### 4. Intelligent Job Matching
- Match candidate profiles with job descriptions.
- Calculate job fit percentage.
- Display suitable job opportunities.
- Identify missing skills and qualifications.

### 5. Skill Gap Analysis
- Identify skills already present in the resume.
- Highlight missing skills.
- Suggest areas for improvement.

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| React.js | Frontend development |
| Vite | Frontend build tool |
| CSS | UI styling |
| React Router DOM | Page navigation |
| Lucide React | Icons |
| Axios | API communication |
| Node.js | Backend runtime |
| Express.js | Backend framework |
| MongoDB Atlas | Cloud database |
| Mongoose | Database management |
| JWT | Authentication |
| Bcrypt.js | Password hashing |
| Google Gemini API | AI-powered analysis |
| Multer | Resume file uploads |

## 📂 Project Structure

```text
CareerFit/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   │   ├── Home.jsx
│   │   │   ├── Signup.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── UploadResume.jsx
│   │   │   └── Dashboard.jsx
│   │   │
│   │   ├── services/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── uploads/
│   ├── server.js
│   └── .env
│
├── README.md
└── .gitignore
```

## ⚙️ Installation and Setup

### Prerequisites

Make sure you have installed:

- Node.js
- npm
- MongoDB Atlas account
- Visual Studio Code

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

```bash
cd CareerFit
```

### 2. Frontend Setup

```bash
cd frontend
npm install
```

Start the development server:

```bash
npm run dev
```

Open the application:

```text
http://localhost:5173
```

### 3. Backend Setup

Open another terminal:

```bash
cd backend
npm install
```

Create a `.env` file inside the backend folder:

```env
PORT=5000
MONGO_URI=your_mongodb_atlas_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

Start the backend:

```bash
npm run dev
```

**Note:** Configure your MongoDB Atlas credentials and API keys before running the backend. Never commit your `.env` file to GitHub.

## 🔄 Application Workflow

1. User visits the CareerFit platform.
2. User creates an account or logs in.
3. User uploads their resume.
4. The system extracts relevant information.
5. AI analyzes the candidate's skills and experience.
6. The system compares the candidate profile with job requirements.
7. Users receive job fit scores and skill gap insights.
8. Users get recommendations to improve their resumes.

## 🎯 Project Objectives

- Simplify the job search process.
- Reduce the time spent applying to unsuitable jobs.
- Help candidates understand their strengths and weaknesses.
- Provide personalized career improvement suggestions.
- Make resume analysis and job matching more intelligent.

## 🚧 Development Status

**Project Status: In Progress**

CareerFit is currently under development.

Planned development milestones:

- [x] Initial React + Vite frontend setup
- [x] Landing page UI
- [ ] Signup and Login integration
- [ ] MongoDB Atlas integration
- [ ] Resume upload functionality
- [ ] Resume text extraction
- [ ] Gemini AI integration
- [ ] Job matching algorithm
- [ ] Job fit score calculation
- [ ] Skill gap analysis
- [ ] AI-based resume recommendations
- [ ] Testing and deployment

## 🔮 Future Enhancements

- Personalized job recommendations.
- AI-powered resume optimization.
- Job description analysis.
- Resume scoring and improvement tracking.
- Interview preparation recommendations.
- User profile and application history.

## 👩‍💻 Developed By

**CareerFit – B.Tech Computer Science and Engineering Major Project**

Developed as an initiative to make career planning and job searching more efficient through Artificial Intelligence.

---

⭐ If you find this project interesting, consider giving the repository a star!