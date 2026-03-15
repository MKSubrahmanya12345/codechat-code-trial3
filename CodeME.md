# Project Name: Antigravity - The Gamified Study Tracker with AI Adaptive Paths

## Overview
Antigravity is a revolutionary MERN stack application designed to transform the way students study by integrating gamification, real-time collaboration, and cutting-edge AI-powered adaptive learning. It aims to make studying engaging, effective, and collaborative.

## Key Features

### 1. Gamified Study Tracking
*   **Subject Management:** Organize study materials by subject, semester, and academic year.
*   **Objective-Based Progress:** Set specific study goals and track progress with visual indicators.
*   **Streak Tracking:** Motivate users with daily/weekly study streaks and progressive rewards.
*   **Achievement Badges:** Unlock virtual badges for milestones, consistent effort, and mastering topics.
*   **Gamified UI:** An intuitive, mobile-optimized interface designed to feel like a game, not a chore.

### 2. Robust Calendar & Reminders
*   **Interactive Calendar:** Visualize deadlines, study sessions, and important academic dates.
*   **Deadline Reminders:** Automated email notifications via Nodemailer for upcoming assignments, exams, and study goals.

### 3. Code Upload & Analysis
*   **Code Submission:** Users can upload code snippets, their output, and algorithm descriptions for programming assignments.
*   **Automated Feedback (Basic):** Initial validation/syntax checking (can be enhanced post-hackathon).
*   **Progress Tracking:** Link code submissions to specific objectives for comprehensive progress monitoring.

### 4. Real-time Collaborative Study Rooms
*   **Live Chat:** Instant messaging within study groups using Socket.io.
*   **Shared Notes:** Collaborative real-time document editing for shared study materials.
*   **Leaderboards:** Foster healthy competition among study group members based on progress, streaks, and achievements.
*   **Session Management:** Create, join, and manage private/public study rooms.

### 5. AI-Powered Adaptive Study Paths (Killer Feature)
*   **Weakness Identification:** Analyze user progress, quiz results, and code submission patterns to identify knowledge gaps.
*   **Personalized Challenges:** Dynamically generate tailored study recommendations, practice problems, and mini-quizzes within collaborative rooms based on identified weak areas.
*   **Resource Suggestion:** Recommend relevant external resources (articles, videos) to reinforce learning.
*   **Feedback Loop:** Continuously adapt study paths as users improve, ensuring efficient and targeted learning.

## Technical Stack
*   **Frontend:** React.js with Vite for a blazing fast development experience and modern UI.
*   **Backend:** Node.js with Express.js for a scalable and efficient API server.
*   **Database:** MongoDB Atlas for flexible, cloud-hosted NoSQL data storage.
*   **Real-time:** Socket.io for seamless, bi-directional communication in collaborative rooms.
*   **Email Services:** Nodemailer for reliable email notifications and reminders.
*   **Caching/Session Management:** Redis for high-performance data caching and user session handling.
*   **AI Integration:** Python for developing and deploying adaptive learning models (e.g., using scikit-learn or a simple recommendation engine), exposed via a REST API or integrated directly into the Node.js backend.

## Deployment & Hosting
*   **Frontend:** Vercel
*   **Backend & AI Service:** Railway
*   **Database:** MongoDB Atlas
*   **Redis:** Railway / Upstash

## Getting Started
1.  Clone the repository.
2.  Install dependencies for both `frontend/` and `backend/` directories.
3.  Set up `.env` files with necessary environment variables (DB URI, Nodemailer credentials, etc.).
4.  Run `npm run dev` in `frontend/` and `npm start` in `backend/`.
5.  (Optional) Set up and run the `ai-service/` if implemented as a separate microservice.

Let's build something awesome!