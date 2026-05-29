# QuizAT - Android Quiz App

## Overview

QuizAT is a role-based Android Quiz Management System developed using Kotlin and Firebase Realtime Database as part of an undergraduate degree project.

The application was designed to streamline quiz creation, scheduling, evaluation, feedback management, and performance tracking within an academic environment.

The system provides dedicated interfaces and functionalities for three user roles:

- Admin
- Examiner
- Student

Using Firebase as the backend, QuizAT offers real-time data synchronization, secure user authentication, role-based access control, and centralized quiz management.


## Academic Project

This application was developed as part of my Bachelor of Computer Applications (BCA) degree project.

The system was independently conceptualized, designed, implemented, tested, and documented as an academic submission.


## Key Features

### Admin Module

- Create and assign quizzes to examiners
- Manage students and examiners
- Edit and delete quizzes
- Generate examiner-wise reports
- Generate semester and annual reports
- View examiner performance statistics

### Examiner Module

- Create question papers
- Edit existing question papers
- Schedule quizzes
- Review student attempts
- Provide feedback to students
- Monitor quiz and student performance

### Student Module

- Attempt scheduled quizzes
- View quiz history
- Access detailed answer analysis
- Track academic performance
- View upcoming scheduled quizzes


## Technology Stack

### Frontend

- Kotlin
- Android Studio
- Material Design Components

### Backend

- Firebase Realtime Database
- Firebase Authentication

### Backend Features

- Real-time data synchronization
- Secure authentication
- Role-based access control
- Cloud-hosted database management


## Application Architecture

```text
Admin
├── Create Quiz
├── Manage Quiz
├── Manage Users
└── Generate Reports

Examiner
├── Create Question Paper
├── Edit Question Paper
├── Schedule Quiz
├── Provide Feedback
└── Review Performance

Student
├── Attempt Quiz
├── View Quiz History
├── Performance Report
└── Scheduled Quizzes
```


## User Interface

### Welcome Screen

![Welcome Screen](screenshots/welcome_screen.png)

### Admin Dashboard

![Admin Dashboard](screenshots/admin_dashboard.png)

### Create Quiz

![Create Quiz](screenshots/create_quiz.png)

### Examiner Dashboard

![Examiner Dashboard](screenshots/examiner_dashboard.png)

### Create Question Paper

![Create Question Paper](screenshots/create_question_paper.png)

### Schedule Quiz

![Schedule Quiz](screenshots/schedule_quiz.png)

### Student Dashboard

![Student Dashboard](screenshots/student_dashboard.png)

### Quiz Attempt

![Quiz Attempt](screenshots/attempt_quiz.png)

### Performance Report

![Performance Report](screenshots/performance_report.png)


## Future Enhancements

- Push Notifications
- CSV / Word Question Paper Import
- AI-Based Performance Analytics
- Live Quiz Competitions
- Web-Based Admin & Examiner Portal
- Advanced Performance Dashboards

## Author

**Nishka Bhatt**
