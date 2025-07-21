# 🌿 Healthy Habit Tracker

## Introduction
The Healthy Habit Tracker is a single-page web application that allows users to track and build daily healthy habits. Users can log in, add and manage habits under categories like Meditation, Sleep, Fitness, and Hydration. The app displays weekly progress, streaks, and calculates a wellness score to keep users motivated.

## Project Type
Frontend | Firebase Backend

## Deployed App
Frontend: (https://habit-tracker2.netlify.app/)
Backend: [Firebase Console]([https://console.firebase.google.com](https://console.firebase.google.com/u/0/project/tracker-d3ab6/authentication/users))  
Database: Firebase Firestore

## Directory Structure
```
healthy-habit-tracker/
├─ index.html
├─ style.css (Tailwind CDN)
├─ script.js
├─ firebase-config.js
```

## 🎥 Video Walkthrough of the Project
https://youtu.be/PJMq9SGTAsk

## Features
- 🔐 User Authentication (Signup/Login via Firebase)
- 🧘 Habit Categories: Meditation, Sleep, Fitness, Hydration
- ✅ Mark habits as completed
- 🧠 Tracks weekly streaks and calculates a wellness score
- 🗑️ Delete habits
- 📱 Fully responsive layout
- 🌙 Dark mode toggle

## Design Decisions or Assumptions
- Used Firebase for Auth and Firestore for data to avoid backend complexity.
- Focused on mobile-first design using Tailwind CSS.
- Simple calculation model for wellness score to avoid heavy data logic.

## Installation & Getting Started
```bash
# Clone the repository
git clone https://github.com/yourusername/healthy-habit-tracker.git
cd healthy-habit-tracker

# No build tools needed, open directly in browser
Open index.html in your browser
```

## Usage
1. Sign up or log in with email and password.
2. Add habits by selecting category.
3. Mark daily habits as completed.
4. View streaks and wellness score.
5. Delete habits as needed.

*Screenshots or GIFs can be added here.*

## Credentials (Demo)
```
Email: demo@habit.com
Password: 123456
```

## APIs Used
- Firebase Authentication
- Firebase Firestore (No external APIs used)

## API Endpoints (Firebase Firestore)
```
GET habits/       - Retrieve user habits
POST habits/      - Create new habit
PATCH habits/:id  - Update completion
DELETE habits/:id - Remove habit
```

## Technology Stack
- HTML5
- Tailwind CSS (via CDN)
- JavaScript (Vanilla)
- Firebase Authentication
- Firebase Firestore

---
**Author**: [Manisha Pal] | [GitHub](https://github.com/manishapal06)
