# Microblogging Web Application

[![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?style=flat&logo=node.js&logoColor=white)](https://nodejs.org/)
[![Express.js](https://img.shields.io/badge/Express.js-Framework-000000?style=flat&logo=express&logoColor=white)](https://expressjs.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/)

## 📌 Project Overview
A lightweight, responsive **Microblogging Application** providing a Twitter/Threads-style social feed. Built with an **Express.js** backend and modular client-side JavaScript, it supports post authoring, feed updates, and session simulation.

---

## 🎯 Problem Statement & Objectives
- **Understanding Real-Time Social Feeds:** Building core architectural foundations for short-form post publishing, user attribution, and client-side feed rendering.
- **Objectives:**
  1. Build a clean asynchronous REST API for authoring and retrieving status posts.
  2. Maintain lightweight JSON data persistence (`data.json`).
  3. Implement responsive user authentication and feed interfaces in pure JavaScript.

---

## 🛠️ Technologies Used
- **Backend:** Node.js, Express.js, Body-Parser
- **Storage:** JSON File Store (`data.json`)
- **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6 Modules)

---

## 🚀 Key Features
- **Post Authoring:** Create short-form text posts with timestamps and author handles.
- **Dynamic Feed Loading:** Asynchronous content loading without requiring full page reloads.
- **Authentication Screens:** Dedicated login and registration flows.

---

## 📂 Project Folder Structure
```
microblogging-app/
├── .gitignore
├── README.md
├── data.json              # Data store for posts and user accounts
├── docs/                  # Client-side web assets
│   ├── home.html
│   ├── home.js
│   ├── index.html
│   ├── login.js
│   └── style.css
├── package.json
└── server.js              # Express routing and file persistence
```

---

## 💻 Installation & Execution Instructions

```bash
git clone https://github.com/Dhanusheyap755/microblogging-app.git
cd microblogging-app
npm install
node server.js
```
*Open `http://localhost:3000` in your browser.*
