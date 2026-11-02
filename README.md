# 🔐 MERN Authentication System

A secure, full-stack user authentication and authorization system built with the MERN stack (MongoDB, Express.js, React, Node.js). 

---

## 🚀 Features

* **User Signup & Registration:** New users can create an account securely.
* **Email Verification System:** Sends a verification email upon signup to confirm user authenticity before granting full access.
* **Secure Login & Authentication:** Users can log in with encrypted credentials, authenticated via JSON Web Tokens (JWT).
* **Logout Functionality:** Clears user session tokens securely on logout.
* **Protected Routes:** Restricts dashboard/home access so only logged-in and verified users can view sensitive data.
* **Cloud Database Storage:** All user accounts, credentials, and verification statuses are stored securely in real-time using **MongoDB Atlas**.
---

## 🛠️ Tech Stack

* **Frontend:** React, React Router, Tailwind CSS / Lucide React
* **Backend:** Node.js, Express.js
* **Database:** MongoDB, Mongoose
* **Security & Auth:** JSON Web Tokens (JWT), Bcrypt.js, Cookie-parser

---

## 📁 Project Structure

```text
MERN-AUTH/
│
├── client/             # Frontend React application
│   ├── src/
│   └── package.json
│
├── server/             # Backend Express application
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
