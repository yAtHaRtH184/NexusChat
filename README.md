# NexusChat 💬

![Java](https://img.shields.io/badge/Java-21-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-brightgreen)
![React](https://img.shields.io/badge/React-Vite-61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-336791)
![Docker](https://img.shields.io/badge/Docker-2496ED)
![License](https://img.shields.io/badge/Status-Active-success)

A production-style **real-time chat application** built using **Spring Boot, React (Vite), PostgreSQL, JWT Authentication, WebSockets, and Docker**.

NexusChat enables secure real-time communication through chat rooms with persistent message storage and JWT-based authentication. The project demonstrates full-stack application development, REST API design, WebSocket-based messaging, secure authentication, and containerized deployment using Docker.

---

# 🎯 Project Objective

The objective of NexusChat is to build a scalable real-time messaging platform that demonstrates modern backend development practices including secure authentication, RESTful APIs, WebSocket communication, relational database design, and Docker-based development.

---

# ✨ Key Highlights

- 🔐 JWT-based Authentication & Authorization
- 💬 Real-time messaging using STOMP WebSockets
- 👥 Multi-user chat rooms
- 📜 Persistent message history using PostgreSQL
- 🌐 RESTful APIs built with Spring Boot
- 🐳 Dockerized development environment
- ⚡ Responsive React (Vite) frontend
- 🔒 Secure Spring Security configuration

---

# 🚀 Features

- User Registration & Login
- JWT Authentication
- Create Chat Rooms
- Join Existing Chat Rooms
- Real-time Message Delivery
- Persistent Chat History
- Secure REST APIs
- Dockerized PostgreSQL Database
- Responsive User Interface

---

# 🛠️ Tech Stack

## Backend

- Java
- Spring Boot
- Spring Security
- Spring Data JPA
- JWT Authentication
- STOMP WebSockets
- Maven

## Frontend

- React (Vite)
- JavaScript
- HTML5
- CSS3

## Database

- PostgreSQL

## DevOps & Tools

- Docker
- Docker Compose
- Git
- GitHub
- IntelliJ IDEA

---

# 📂 Project Structure

```text
NexusChat
│
├── backend
│   ├── src
│   ├── pom.xml
│   └── ...
│
├── frontend
│   ├── src
│   ├── package.json
│   └── ...
│
├── docker
│   ├── docker-compose.yml
│   └── init.sql
│
├── .env.example
└── README.md
```

---

# ⚙️ Getting Started

## 1. Clone the Repository

```bash
git clone https://github.com/yAtHaRtH184/NexusChat.git

cd NexusChat
```

---

## 2. Configure Environment Variables

Create a `.env` file in the project root.

```env
POSTGRES_DB=your_database

POSTGRES_USER=your_username

POSTGRES_PASSWORD=your_password

JWT_SECRET=your_secret_key
```

---

## 3. Start PostgreSQL

```bash
cd docker

docker compose up -d
```

---

## 4. Run the Backend

```bash
cd backend

./mvnw spring-boot:run
```

---

## 5. Run the Frontend

```bash
cd frontend

npm install

npm run dev
```

The frontend will be available at

```text
http://localhost:5173
```

---

# 📡 API Overview

## Authentication

- Register User
- Login User

## Chat Rooms

- Create Chat Room
- Join Chat Room
- Fetch Chat History

## Messaging

- Real-time Messaging using STOMP WebSockets

---

# 🔒 Security

- JWT Authentication
- BCrypt Password Encryption
- Spring Security
- Protected REST Endpoints
- Secure CORS Configuration

---

# 🏗️ System Architecture

```text
                 React (Vite)
                      │
            REST API + JWT Authentication
                      │
             Spring Boot Backend
              │               │
     STOMP WebSockets    Spring Data JPA
              │               │
              └────── PostgreSQL ──────┘
```

---

# 📸 Screenshots

## Login Page

<img width="1905" alt="Login" src="YOUR_LOGIN_IMAGE_URL"/>

---

## Registration Page

<img width="1886" alt="Register" src="YOUR_REGISTER_IMAGE_URL"/>

---

## Dashboard

<img width="1913" alt="Dashboard" src="YOUR_DASHBOARD_IMAGE_URL"/>

---

## Chat Room

<img width="1908" alt="Chat" src="YOUR_CHAT_IMAGE_URL"/>

---

# 🚀 Future Enhancements

- Read Receipts
- Typing Indicators
- Online/Offline Presence
- File Sharing
- Push Notifications
- Group Administration
- Message Search
- Voice Messages
- Cloud Deployment (AWS)

---

# 👨‍💻 Author

## Yatharth Kumar Rana

Backend Developer | Java | Spring Boot | React

GitHub: https://github.com/yAtHaRtH184

LinkedIn: https://www.linkedin.com/in/yatharth-rana18/

LeetCode: https://leetcode.com/u/Yatharth_Rana18/

---

# ⭐ Support

If you found this project useful or interesting, please consider giving it a ⭐ on GitHub.

Feel free to fork the repository, raise issues, or contribute improvements.

Happy Coding! 🚀
