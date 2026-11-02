# 🔐 MERN Authentication System

A secure, full-stack user authentication and authorization system built with the MERN stack (MongoDB, Express.js, React, Node.js). 

---

## 🚀 Features

* **User Registration & Login:** Secure signup and signin flows with password hashing.
* **JWT Authentication:** JSON Web Tokens stored securely via HTTP-only cookies for session management.
* **Protected Routes:** Frontend and backend route protection to restrict access to authenticated users.
* **Email Verification / Notifications:** Integrated transactional email services (Nodemailer / Brevo) for verification and alerts.
* **Responsive Design:** Clean, modern UI styled for optimal user experience across devices.

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
