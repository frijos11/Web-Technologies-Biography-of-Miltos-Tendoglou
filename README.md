# 🏅 Miltos Tendoglou - Biography Web Application

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=JSON%20web%20tokens&logoColor=white)

A full-stack responsive biographical web application (in Greek) dedicated to Olympic gold medalist **Miltos Tendoglou**. Developed as part of a **Web Technologies** university course, built with Node.js, Express, and Vanilla JavaScript.

🔗 **[Live Demo on CodeSandbox](https://codesandbox.io/p/devbox/x8kfs4)**

*Note: This application runs on a free CodeSandbox container. Please allow a few seconds for the Node.js server to wake up and the preview window to load.*

---

## 📖 Overview

This project presents a structured and interactive biography of Miltos Tendoglou. Unlike static pages, it utilizes a custom **Node.js & Express backend** to serve the application, authenticate users via **JSON Web Tokens (JWT)**, and dynamically manage content (distinctions and external links) through structured JSON files.

## ✨ Key Features

- **Interactive Biography:** Detailed sections covering his athletic journey, early life, and career milestones.
- **Dynamic Data (JSON):** Distinctions and external links are fetched and managed dynamically from structured JSON files (`Distinctions.json`, `Links.json`).
- **User Authentication (JWT & Cookies):** Role-based login system using `jsonwebtoken` and HTTP cookies to protect authenticated routes.
- **Backend Integration:** Built with Express.js to handle static file serving, API routing, and server-side logic.
- **Responsive Layout:** Designed to adapt smoothly across desktops, tablets, and mobile devices.

## 🔑 Demo Credentials

To test the login functionality in the Live Demo, you can use the following pre-configured accounts:

| Role | Username | Password |
| :--- | :--- | :--- |
| **Admin** | `admin` | `pass` |
| **User** | `user` | `pass` |

---

## 📸 Preview

<img width="100%" alt="Project_ReadMe_1" src="https://github.com/user-attachments/assets/ecf0a853-ac96-48a5-ab52-f5c57d7a00d9" />
<br><br>
<img width="100%" alt="Project_ReadMe_2" src="https://github.com/user-attachments/assets/de20b068-3526-4eef-81fc-55d73f5066f9" />

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, Vanilla JavaScript
- **Backend:** Node.js, Express.js
- **Authentication & Middleware:** JSON Web Tokens (`jsonwebtoken`), `cookie-parser`, `body-parser`
- **Data Storage:** JSON Files (`fs` module)
- **Deployment / Sandbox:** CodeSandbox

---

## 📂 Project Structure

```text
├── www/
│   ├── Images/               # Static image assets
│   ├── JsonFiles/            # Dynamic data storage (Distinctions.json, Links.json)
│   ├── index.html            # Main frontend interface
│   ├── CSS.css               # Application styling and responsive layout
│   └── JAVASCRIPT.js         # Client-side logic & API calls
├── index.js                  # Express server, API routes & JWT authentication
├── package.json              # Project metadata and dependencies
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started (Run Locally)

To run this project locally on your machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/frijos11/Web-Technologies-Biography-of-Miltos-Tendoglou.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Web-Technologies-Biography-of-Miltos-Tendoglou
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the server:
   ```bash
   node index.js
   ```
5. Open your browser and visit: `http://localhost:4000`
