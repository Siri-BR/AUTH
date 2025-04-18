# 🔐 Authentication System – OAuth & Email-Based Login

This is a full-featured authentication setup for full-stack web applications. It provides both social login and classic email/password methods. Key highlights include:

- **🔗 Social Sign-In with Google, Facebook, and a simulated Apple login**
- **✉️ Traditional Registration & Login using email and password**
- **🛡️ JWT-Based Authentication for secure, stateless sessions**
- **📄 Separate Interfaces for login and signup for better UX**
- **🧑‍💼 User Dashboard accessible after successful login**
- **🗃️ MongoDB + Mongoose used for storing and managing user information**


---

## 🛠 Tech Stack

**Frontend**: React  
**Backend**: Node.js, Express.js  
**Database**: MongoDB Compass (via Mongoose)  
**Authentication**: Passport.js (Google, Facebook, Apple [Mock]), JWT  
**Environment Variables**: `.env` used for API credentials & MongoDB URI


---

## ✨ Features

- ✅ Google, Facebook, Apple (mock) OAuth login
- ✅ Manual Signup/Login using email and password
- ✅ JWT authentication with token validation
- ✅ Separate routes for login and signup
- ✅ User data saved in MongoDB
- ✅ Redirection to Dashboard after login
- ✅ Secure Passport strategy setup

---

## 📌 Note:

- Apple OAuth is **mocked** using dummy strategy for testing.
- Easily extendable for real Apple login when Developer Account is available.
- Uses JWTs to secure frontend/backend communication.
