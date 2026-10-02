# LinCo LMS

**LinCo LMS** is a comprehensive Learning Management System built with Flutter, designed to provide organizations and learners with a complete platform for managing courses, lessons, assessments, live sessions, departments, and employee training.

The application supports both learning and management workflows, allowing users to consume educational content while giving organizations tools to manage their training programs and monitor learner progress.

---

## ✨ Features

###  Authentication & User Management

* Email and Google authentication
* JWT-based authentication with access/refresh tokens
* Email verification
* Password reset and change
* Two-factor authentication (2FA)
* Secure token storage
* User profile management

###  Courses & Learning

* Browse and manage courses
* Course creation and publishing
* Course sections and lessons
* Video-based lessons
* Course attachments and downloadable resources
* Course FAQs
* Course enrollment and payment
* Course progress tracking

###  Quizzes & Assessments

* Create and manage exams
* Question banks
* Exam attempts
* Answer submission
* Automatic exam generation
* Assessment history

###  Departments & Employee Training

* Department management
* Department members
* Training roadmaps
* Department courses
* Leaderboards
* Department communication and chat

###  Demo & Training Management

The platform includes a dedicated **Demo** system for organizations to provide training experiences and evaluate employees.

Demo owners can:

* Create and manage training demos
* Invite users to demos
* Assign courses and training content
* Manage demo members
* Monitor employee training activity
* View training reports and statistics

Reports can provide information about:

* Overall training performance
* Employees
* Courses
* Departments
* Individual training results

###  Communication

* Q&A discussions
* Questions and answers between learners
* Department chat
* Real-time communication using Socket.IO

###  Live Learning

* Live streaming sessions
* Jitsi-based video meetings
* Live course interaction

###  Notifications

* Firebase Cloud Messaging (FCM)
* Push notifications
* Local notifications
* Device token registration

###  AI Features

The application includes an AI-powered **RAG (Retrieval-Augmented Generation)** module that allows users to:

* Ask questions
* Generate quizzes from topics
* Generate random quiz questions

###  Certifications

* View earned certifications
* Access certification details

---

##  Architecture

The project follows a **Feature-Based Clean Architecture** approach.

Each feature is separated into:

```text
feature/
├── data/
│   ├── data_sources/
│   ├── models/
│   └── repositories/
│
├── domain/
│   ├── entities/
│   ├── repositories/
│   └── use_cases/
│
└── presentation/
    ├── cubit/
    ├── pages/
    └── widgets/
```

This structure keeps business logic independent from the UI and data sources, making the application easier to maintain and scale.

---

## 🛠️ Tech Stack

### Frontend

* **Flutter**
* **Dart**

### State Management

* **Flutter BLoC / Cubit**

### Architecture & Dependency Management

* Clean Architecture
* Feature-Based Architecture
* **GetIt** for Dependency Injection
* **Dartz** for functional error handling

### Networking

* **Dio**
* REST API integration
* JWT authentication
* Automatic token refresh

### Real-Time Communication

* **Socket.IO**

### Media & Live Sessions

* Better Player
* Jitsi Meet
* Video streaming and playback

### Authentication & Security

* JWT
* Google Sign-In
* Two-Factor Authentication
* Flutter Secure Storage

### Notifications

* Firebase Cloud Messaging
* Flutter Local Notifications

### Other Integrations

* PDF generation and printing
* File picking and uploading
* Deep linking
* In-app WebView
* Draw.io integration

---

## 📂 Project Structure

```text
lib/
├── config/
├── core/
│
├── features/
│   ├── auth/
│   ├── course/
│   ├── lesson/
│   ├── quiz/
│   ├── questions_bank/
│   ├── department/
│   ├── department_chat/
│   ├── demo/
│   ├── live_stream/
│   ├── notifications/
│   ├── certification/
│   ├── attachment/
│   ├── Q&A/
│   ├── faq/
│   ├── profile/
│   ├── rag/
│   └── integrations/
│
└── main.dart
```

---
##  Project

**LinCo LMS**

A full-featured Flutter Learning Management System combining online learning, employee training, assessments, communication, live sessions, notifications, and AI-powered learning tools.

---

👨‍💻 Authors

Zain Nhlawy

Loulia Alshaar

Information Engineering Students & Flutter Developers
