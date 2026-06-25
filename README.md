# 🎓 StudyNotion

A full-stack **Learning Management System (LMS)** built using the **MERN Stack** that enables instructors to create and manage courses while allowing students to enroll, learn through video lectures, track their progress, and interact with course content through ratings and reviews.

---

## 📖 Project Overview

StudyNotion is a scalable EdTech platform designed to provide a seamless online learning experience for **Students**, **Instructors**, and **Admins**. The platform offers secure authentication, role-based authorization, course management, progress tracking, and a responsive user interface.

During the development of this project, I designed and implemented a complete full-stack architecture using **MongoDB, Express.js, React.js, and Node.js**. I built secure **JWT-based authentication** with **bcrypt** password hashing and implemented **role-based access control** to ensure controlled access for different user roles.

The backend exposes RESTful APIs for user authentication, course creation and management, section and lecture management, student enrollment, progress tracking, and course ratings. On the frontend, I developed a modern and responsive user interface using **React.js**, **Redux Toolkit**, and **Tailwind CSS**, following a modular component-based architecture. The project also integrates **Cloudinary** for media storage and utilizes efficient MongoDB schema design for managing users, courses, lectures, and student progress.

---

## ✨ Features

### 👨‍🎓 Student
- User Registration & Login
- Browse and Search Courses
- Enroll in Courses
- Watch Video Lectures
- Track Learning Progress
- Rate & Review Courses
- Update User Profile

### 👨‍🏫 Instructor
- Create, Update & Delete Courses
- Manage Sections and Lectures
- Upload Course Content
- View Student Enrollments
- Instructor Dashboard

### 🔐 Authentication & Security
- JWT Authentication
- Password Hashing using bcrypt
- Protected Routes
- Role-Based Authorization

### 📱 User Experience
- Fully Responsive Design
- Modern UI with Tailwind CSS
- Reusable React Components
- Fast and Interactive User Experience

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Redux Toolkit
- React Router
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js

### Database
- MongoDB
- Mongoose

### Authentication
- JWT (JSON Web Tokens)
- bcrypt

### Cloud & Utilities
- Cloudinary
- Nodemailer

---

## 📂 Project Structure

```
StudyNotion
│
├── client
│   ├── public
│   ├── src
│   └── package.json
│
├── server
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   └── package.json
│
└── README.md
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/StudyNotion.git
```

### Navigate to the Project

```bash
cd StudyNotion
```

### Install Dependencies

Frontend

```bash
cd client
npm install
```

Backend

```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file inside the **server** directory and configure the following variables:

```env
PORT=

MONGODB_URL=

JWT_SECRET=

MAIL_HOST=
MAIL_USER=
MAIL_PASS=

CLOUD_NAME=
API_KEY=
API_SECRET=

FOLDER_NAME=
```

> **Note:** Never commit your `.env` file or any sensitive credentials to GitHub.

---

## ▶️ Running the Project

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

---

## 📸 Screenshots

Add screenshots of the following pages:

- Home Page
- Login Page
- Student Dashboard
- Instructor Dashboard
- Course Details Page
- Course Creation Page

---

## 🎯 Key Highlights

- Full-Stack MERN Application
- RESTful API Architecture
- Secure JWT Authentication
- Role-Based Authorization
- Responsive User Interface
- Cloudinary Media Integration
- Course & Lecture Management
- Student Progress Tracking
- Modular & Scalable Codebase
- Clean Folder Structure

---

## 🔮 Future Enhancements

The platform can be extended with several advanced features, including:

- 💳 Payment Gateway Integration (Stripe/Razorpay)
- 📹 Live Classes using WebRTC or Zoom API
- 💬 Real-Time Chat & Discussion Forums
- 🤖 AI-Powered Course Recommendations
- 📊 Instructor Analytics Dashboard
- 📜 Course Completion Certificates
- 📝 Online Quizzes & Assessments
- 🔔 Push & Email Notifications
- 🌍 Multi-language Support
- 📱 Progressive Web App (PWA)
- 📥 Downloadable Course Resources
- 🌙 Dark Mode
- 🔍 Advanced Search & Filtering

---

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Building scalable full-stack MERN applications
- Designing RESTful APIs following industry best practices
- Implementing secure authentication and authorization using JWT
- Managing application state with Redux Toolkit
- Designing efficient MongoDB schemas and relationships
- Integrating third-party cloud services like Cloudinary
- Building reusable React components
- Creating responsive user interfaces using Tailwind CSS
- Organizing production-ready backend architecture
- Using Git and GitHub for version control and collaboration

---

## 🤝 Contributing

Contributions, suggestions, and feature requests are welcome. Feel free to fork the repository, create a new branch, and submit a pull request.

---

## 📄 License

This project is developed for educational and portfolio purposes.

---

## 👨‍💻 Author

**Chandra Kanth**

- GitHub: https://github.com/chandrakanth109
- LinkedIn: https://www.linkedin.com/in/chandra-kanth-0079

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!
