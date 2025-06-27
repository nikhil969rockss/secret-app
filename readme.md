# 🔐 Secret App

A secure, minimal web application where users can **anonymously submit and store secrets**. Built with Express.js and EJS on the frontend, this project demonstrates robust session-based authentication, secure password storage, and Google OAuth login using Passport.js.

---

## ✨ Features

- ⚙️ **Backend**: Node.js + Express.js
- 🖥️ **Frontend**: EJS Templating
- 🔐 **Authentication**:
  - Local (email & password)
  - Google Sign-In (OAuth 2.0 via Passport.js)
- 🔒 **Password Security**:
  - Passwords are hashed using `bcrypt`
  - Sessions handled via `express-session`
- 🧠 **Database**: PostgreSQL (stores user data and secrets)

---

## 🛠 Tech Stack

| Layer        | Technology                          |
|--------------|--------------------------------------|
| Backend      | Node.js, Express.js                 |
| Frontend     | EJS                                 |
| Auth         | Passport.js (Local + Google OAuth) |
| Security     | bcrypt, express-session             |
| Database     | PostgreSQL                          |
| Hosting      | *(self-hosted or platform of choice)* |

---

## 📦 Installation & Setup

### Step 1: Clone the Repository

```bash
git clone git@github.com:nikhil969rockss/secret-app.git
cd secret-app
```
### Step 2: Install dependencies

```
npm install
```

### Step 3: Start the server

```
npm start
```




