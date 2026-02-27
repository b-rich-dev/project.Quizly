# Quizly - Interactive Quiz Application

![Quizzy Logo](/assets/icons/logoheader.png)

## Project Overview

Quizly is an interactive quiz application that allows users to create, take, and manage quizzes. The application features a modern UI with a dark theme and green accents, providing an engaging user experience.

### School Project - Developer Akademie

**Note:** This project was created as part of training at Developer Akademie. The **frontend** was provided by Developer Akademie. The **backend** was independently developed as part of the submission project.

- **Project Type:** Backend Development Project
- **Status:** School Project / Demonstration Purpose
- **Purpose:** Demonstration of backend development skills (REST API, JWT Authentication, Database Integration)

## Features

- **User Authentication**: Register, login, and logout functionality
- **Quiz Generation**: Create quizzes from Youtube-URLs
- **Quiz Taking**: Interactive quiz interface with multiple-choice questions
- **Results Review**: View quiz results with correct/incorrect answers
- **Quiz Management**: View, edit, and delete quizzes

## Requirements

- The backend must support **JWT authentication** with **HttpOnly cookies**. This means:
    - The login response must set the JWT access token as an HttpOnly cookie.
    - Requests to protected routes must be authenticated via this cookie.
    - The frontend must not have direct access to the token (e.g., no localStorage or Authorization header).
    - Make sure your backend correctly allows cross-origin requests (CORS) for the local frontend.
---

## Project Structure

```
Quizzy_frontend/
├── assets/               # Static assets
│   ├── fonts/            # Font files
│   ├── icons/            # Icon images
│   └── img/              # Other images
├── pages/                # HTML pages
│   ├── legalnotice.html  # Legal notice page
│   ├── library.html      # Quiz library page
│   ├── login.html        # Login page
│   ├── privacy.html      # Privacy policy page
│   ├── quiz.html         # Quiz taking page
│   ├── quizoverview.html # Quiz overview page
│   └── registration.html # Registration page
├── shared/               # Shared resources
│   ├── css/              # CSS stylesheets
│   │   ├── auth.css      # Authentication styles
│   │   ├── fonts.css     # Font definitions
│   │   ├── library.css   # Library page styles
│   │   ├── policy.css    # Policy pages styles
│   │   ├── quiz.css      # Quiz page styles
│   │   ├── quizoverview.css # Quiz overview styles
│   │   ├── standart.css  # Base styles
│   │   ├── toastmsg.css  # Toast message styles
│   │   └── variables.css # CSS variables
│   └── js/               # JavaScript files
│       ├── api.js        # API interaction functions
│       ├── auth.js       # Authentication functions
│       ├── config.js     # Configuration constants
│       ├── header.js     # Header component
│       ├── helper.js     # Helper functions
│       ├── library.js    # Library page functions
│       ├── quiz.js       # Quiz functionality
│       ├── quizoverview.js # Quiz overview functions
│       └── template.js   # HTML templates
├── index.html            # Main entry point
└── styles.css            # Global styles
```

## Setup and Installation

### Frontend Setup

1. Clone the repository
2. Open the project in a web server (e.g., Live Server in VS Code)
3. Navigate to the index.html file to start the application

### Backend Setup

The backend must be developed and configured separately with the following requirements:

1. Backend server must run on `http://127.0.0.1:8000`
2. Implement JWT authentication with HttpOnly cookies
3. Configure CORS correctly for cross-origin requests from the frontend
4. REST API endpoints for quiz management, user authentication, and results

### Important Notice

This project serves exclusively for **learning and demonstration purposes** as part of training at Developer Akademie.

## Technology Stack

### Frontend (provided)
- HTML5
- CSS3 (with CSS Custom Properties)
- Vanilla JavaScript (ES6+)

### Backend (to be developed)
- Python/Django, Node.js/Express, or other suitable technology
- JWT Authentication
- Database (e.g., PostgreSQL, MySQL, MongoDB)
- RESTful API

## Legal Information

- **Legal Notice:** See [pages/legalnotice.html](pages/legalnotice.html)
- **Privacy Policy:** See [pages/privacy.html](pages/privacy.html)

This project was created as part of training at Developer Akademie. The frontend was provided by Developer Akademie, the backend is part of the independent project work.

