# QuizArena 🎯

QuizArena is a modern, responsive quiz management and testing platform built with **HTML, CSS, and JavaScript**.  
Users can register, take quizzes, view results, track progress, and compete on a leaderboard. Admin users can manage quizzes and questions.

---

## ✨ Features

### 👤 Authentication
- User registration and login
- Role-based access:
  - User
  - Admin
- Demo accounts included

### 📝 Quiz System
- Browse available quizzes
- Multiple categories:
  - Science
  - History
  - Technology
  - General Knowledge
  - Mathematics
- Difficulty levels:
  - Easy
  - Medium
  - Hard
- Timed quiz sessions
- Multiple-choice questions
- Instant answer evaluation

### 📊 Results & Analytics
- Score calculation
- Correct/wrong answer breakdown
- Time tracking
- Answer review after completion
- Quiz history

### 🏆 Leaderboard
- Rank users by performance
- View scores and quiz attempts
- Highlight current user ranking

### 🛠 Admin Panel
Admin users can:
- Create quizzes
- Add questions
- Manage quiz content
- Delete quizzes

### 🎨 UI Features
- Dark modern interface
- Responsive design
- Smooth animations
- Custom cards and dashboards
- Mobile-friendly layout

---

## 🚀 Getting Started

### Requirements

No installation required.

You only need:

- Modern web browser
  - Chrome
  - Edge
  - Firefox
  - Safari

---

## 📂 Project Structure

```
QuizArena/
│
├── index.html        # Main application file
├── README.md         # Project documentation
│
└── (All CSS and JavaScript are included inside index.html)
```

---

## ▶️ Running the Project

1. Download or clone the project.

```bash
git clone <repository-url>
```

2. Open the project folder.

3. Open:

```
index.html
```

in your browser.

The application will start immediately.

---

## 🔐 Demo Accounts

### Admin Account

```
Username: admin
Password: admin123
Role: Admin
```

### User Account

```
Username: alice
Password: pass123
Role: User
```

---

## 🧑‍💻 Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript (ES6)

### Styling

- CSS Variables
- Responsive Grid Layout
- Custom animations
- Google Fonts:
  - Sora
  - DM Mono

---

## 🗄 Data Storage

Currently the application uses an in-memory JavaScript object:

```javascript
const DB = {
   users: [],
   quizzes: [],
   questions: [],
   results: []
};
```

Data will reset when the browser page is refreshed.

---

## 🔮 Future Improvements

Possible upgrades:

- Backend API integration
- Database support (MySQL/MongoDB)
- JWT authentication
- Password encryption
- Admin dashboard improvements
- Question import/export
- Quiz categories management
- User profile customization
- Cloud deployment

---

## 📸 Screens Included

The application contains:

- Login/Register screen
- Dashboard
- Quiz browser
- Quiz attempt screen
- Result analysis
- Leaderboard
- User profile
- Admin quiz manager

---
