# Auth API – Node.js, Express & MongoDB

A secure and production-ready authentication API built using **Node.js**, **Express**, **MongoDB**, and **JWT**.  
This project implements user registration, login, and protected routes using token-based authentication.

---

## 🚀 Features

- User registration with **hashed passwords** (bcrypt)
- User login with **JWT authentication**
- Protected routes using **custom middleware**
- MongoDB Atlas integration using **Mongoose**
- Environment-based configuration using **dotenv**
- Clean project structure with routes, models, and middleware
- Proper HTTP status codes and error handling

---

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB Atlas**
- **Mongoose**
- **JWT (jsonwebtoken)**
- **bcryptjs**
- **dotenv**
- **nodemon**

---

## 📂 Project Structure
auth-api/
├── src/
│   ├── config/
│   │   └── db.js
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── auth.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   └── server.js
├── .gitignore
├── package.json
├── package-lock.json
└── README.md
---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/singhpratham19/auth-api-nodejs.git
cd auth-api-nodejs
npm install
3️⃣ Create Environment Variables

Create a .env file in the root directory:
PORT=5001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
 Run the Server
npx nodemon src/server.js
🔐 API Endpoints

➤ Register User

POST /api/auth/register
{
  "name": "Test User",
  "email": "test@example.com",
  "password": "123456"
}
➤ Login User

POST /api/auth/login
{
  "email": "test@example.com",
  "password": "123456"
}

⸻

✅ Security Highlights
	•	Passwords are never stored in plain text
	•	JWT tokens are verified on protected routes
	•	Sensitive data excluded from API responses
	•	Environment variables used for secrets

⸻

📌 Use Case

This project is ideal as:
	•	A backend authentication service
	•	A base for MERN stack applications
	•	A portfolio project for backend/full-stack internships

⸻

👤 Author

Pratham Singh
GitHub: https://github.com/singhpratham19

⸻

⸻

✅ Security Highlights
	•	Passwords are never stored in plain text
	•	JWT tokens are verified on protected routes
	•	Sensitive data excluded from API responses
	•	Environment variables used for secrets

⸻

📌 Use Case

This project is ideal as:
	•	A backend authentication service
	•	A base for MERN stack applications
	•	A portfolio project for backend/full-stack internships

⸻

👤 Author

Pratham Singh
GitHub: https://github.com/singhpratham19

⸻

⸻

✅ Security Highlights
	•	Passwords are never stored in plain text
	•	JWT tokens are verified on protected routes
	•	Sensitive data excluded from API responses
	•	Environment variables used for secrets

⸻

📌 Use Case

This project is ideal as:
	•	A backend authentication service
	•	A base for MERN stack applications
	•	A portfolio project for backend/full-stack internships

⸻

👤 Author

Pratham Singh
GitHub: https://github.com/singhpratham19

⸻
📄 License

This project is open-source and available for learning and portfolio use.
---


