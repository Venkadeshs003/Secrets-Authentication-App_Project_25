├── index.js             # Main server file
├── public/              # Static assets (CSS)
│   └── style.css
├── views/               # EJS templates
│   ├── home.ejs
│   ├── login.ejs
│   ├── register.ejs
│   ├── secrets.ejs
│   ├── submit.ejs
│   └── partials/        # Header & Footer
├── .env                 # Environment variables
├── package.json

# 🔑 Secrets Authentication App  

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)  
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)  
![Passport.js](https://img.shields.io/badge/Passport.js-34E27A?style=for-the-badge&logo=passport&logoColor=white)  
![EJS](https://img.shields.io/badge/EJS-8BC34A?style=for-the-badge&logoColor=white)  

A Node.js authentication project that allows users to **register, login, and share secrets anonymously**.  
Supports both **local authentication** (email & password with bcrypt hashing) and **Google OAuth 2.0 authentication**.  

---

## 🚀 Features  

- 🔒 User authentication with **Passport.js**  
- 🗝️ **Local strategy** (email & password with bcrypt hashing)  
- 🌐 **Google OAuth 2.0 authentication**  
- 📝 Users can register, login, and access protected pages (`/secrets`)  
- 📦 Session management using **express-session**  
- 🗃️ PostgreSQL database for storing users  
- 🎨 Frontend built with **EJS templates** + Bootstrap  

---

## 🛠️ Tech Stack  

- **Backend**: Node.js, Express.js  
- **Authentication**: Passport.js (Local + Google Strategy), bcrypt  
- **Database**: PostgreSQL  
- **Frontend**: EJS, Bootstrap, CSS  
- **Session Handling**: express-session  
- **Environment Management**: dotenv  

---

## ⚙️ Installation & Setup  

1. **Clone the repo**  
   ```bash
   git clone https://github.com/your-username/secrets-auth-app.git
   cd secrets-auth-app