# Mwangaza: A Learning Management System (LMS)

"Lighting the path to a better life, one skill at a time."

## Project Overview

Mwangaza is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application designed to empower underserved adults by offering practical, gamified learning experiences in communication, math, wellness, and life skills.

## Project Structure

```
mwangaza/
├── client/             # React frontend application
│   ├── public/
│   ├── src/
│   │   ├── assets/         # Images, icons, etc.
│   │   ├── components/     # Reusable UI components (e.g., Button, Modal)
│   │   ├── contexts/       # React Context for state management
│   │   ├── hooks/          # Custom React hooks
│   │   ├── pages/          # Top-level components for different routes
│   │   ├── utils/          # Utility functions
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
├── server/             # Node.js/Express.js backend API
│   ├── config/         # Database connection, environment variables
│   ├── controllers/    # Request handlers
│   ├── middleware/     # Express middleware (auth, error handling)
│   ├── models/         # Mongoose schemas and models
│   ├── routes/         # API routes
│   ├── utils/          # Utility functions (e.g., JWT)
│   ├── server.js
│   └── ...
├── .env                # Environment variables
├── .gitignore
├── package.json
├── README.md
└── todo.md
```

## Core Components and Interactions

### Frontend (React.js)

- **Authentication Components**: Login, Register, Logout, Protected Routes.
- **Navigation**: Sidebar, Navbar for different user roles (Learner, Counselor, Admin).
- **Learning Modules**: CourseViewer, LessonCard, QuizCard to display and interact with learning content.
- **Gamification**: Progress bars, Badge/XP display.
- **Counseling System**: MessageBoard for communication with counselors.
- **Admin Panel**: User management, course management interfaces.
- **Styling**: Tailwind CSS and DaisyUI for responsive and uplifting design.
- **State Management**: React Context or Zustand for global state.
- **API Calls**: Axios for interacting with the backend.

### Backend (Node.js/Express.js)

- **Authentication**: JWT-based authentication for secure access.
- **User Management**: APIs for user registration, login, and profile management.
- **Course Management**: APIs for creating, reading, updating, and deleting courses, modules, and lessons.
- **Quiz Management**: APIs for handling quizzes, questions, and answers.
- **Progress Tracking**: APIs for recording and retrieving learner progress and XP.
- **Counseling**: APIs for message exchange between learners and counselors.
- **Database**: MongoDB (via Mongoose) for data storage.
- **Middleware**: For authentication, logging, and error handling.
- **Real-time Communication (Optional)**: Socket.io for real-time chat between learners and counselors.

### Database (MongoDB)

- **User Model**: Stores user details, roles, XP, and learning progress.
- **Course Model**: Defines the structure of courses.
- **Module Model**: Defines modules within courses.
- **Lesson Model**: Defines lessons within modules, including content (text, audio, images) and mini-quizzes.
- **Quiz Model**: Stores quiz questions, choices, and correct answers.
- **Progress Model**: Tracks learner progress through lessons and quizzes.
- **Message Model**: Stores messages exchanged in the counseling system.

## API Endpoints (RESTful)

- `/api/auth`: User authentication (register, login, logout).
- `/api/courses`: CRUD operations for courses, modules, and lessons.
- `/api/quizzes`: CRUD operations for quizzes and questions.
- `/api/progress`: Track and retrieve learner progress.
- `/api/counseling`: Manage messages and counseling resources.

## Deployment

- **Frontend**: Vercel
- **Backend**: Render

This `README.md` will be updated as the project progresses.

