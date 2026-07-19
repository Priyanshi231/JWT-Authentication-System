# 🔐 Authentication System

A secure authentication system built with **Node.js**, **Express.js**, and **MongoDB** using **JWT Authentication**, **Refresh Token Rotation**, **Session Management**, and **OTP-based Email Verification**.

## ✨ Features
- User Registration & Login
- JWT Access & Refresh Tokens
- Refresh Token Rotation
- Session Management
- OTP Email Verification (Nodemailer + Gmail OAuth2)
- Protected Routes
- Logout & Logout from All Devices
- Secure Password & OTP Hashing
- HTTP-only Cookies

## 🛠️ Tech Stack
Node.js • Express.js • MongoDB • Mongoose • JWT • Nodemailer • Gmail OAuth2 • Crypto • Cookie Parser

## 🚀 Setup

```bash
git clone https://github.com/Priyanshi231/Authentication-System.git
cd Authentication-System
npm install
npm run dev
```

## ⚙️ Environment Variables

Create a `.env` file in the project root and add:

```env
PORT=3000

MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret
GOOGLE_REFRESH_TOKEN=your_google_refresh_token
GOOGLE_USER=your_email@gmail.com
```

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/register` | Register user |
| POST | `/verify-email` | Verify email with OTP |
| POST | `/login` | Login user |
| GET | `/me` | Get authenticated user |
| GET | `/refresh-token` | Refresh access token |
| GET | `/logout` | Logout current session |
| GET | `/logout-all` | Logout all sessions |

## 🔒 Security
- JWT Authentication
- Refresh Token Rotation
- Session Tracking
- HTTP-only Cookies
- Password & OTP Hashing
- Email Verification

## 👩‍💻 Author

**Priyanshi Jain**

- GitHub: https://github.com/Priyanshi231
- LinkedIn: https://linkedin.com/in/priyanshi-jain-4a91b1271
