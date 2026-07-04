# NexusChat 💬

A production-style real-time chat application built using **Spring Boot, React, PostgreSQL, JWT Authentication, WebSockets, and Docker**.

The application enables secure real-time communication through chat rooms with persistent message storage and JWT-based authentication.

---

## 🚀 Features

- Secure user authentication using JWT
- Real-time messaging using STOMP WebSockets
- Multi-user chat rooms
- Persistent chat history with PostgreSQL
- REST APIs for authentication and chatroom management
- Dockerized backend and database
- Responsive React frontend

---

## 🛠️ Tech Stack

### Backend
- Spring Boot
- Spring Security
- JWT Authentication
- Spring Data JPA
- WebSockets (STOMP)

### Frontend
- React (Vite)
- JavaScript
- HTML
- CSS

### Database
- PostgreSQL

### DevOps & Tools
- Docker
- Maven
- Git
- IntelliJ IDEA

---

## 📂 Project Structure

```
NexusChat
├── backend
├── frontend
├── docker
├── README.md
└── .env.example
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/<your-username>/NexusChat.git
cd NexusChat
```

### Configure Environment Variables

Create a `.env` file:

```env
POSTGRES_DB=your_db
POSTGRES_USER=your_user
POSTGRES_PASSWORD=your_password
JWT_SECRET=your_secret
```

### Start PostgreSQL

```bash
cd docker
docker-compose up -d
```

### Run Backend

```bash
cd backend
./mvnw spring-boot:run
```

### Run Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 📸 Screenshots

> Add screenshots of:

- Login Page
- Registration Page
- Chat Dashboard
- Chat Room
- Messaging Screen

---

## 📡 API Highlights

- User Registration
- User Login
- Create Chat Room
- Join Chat Room
- Fetch Chat History
- Real-Time Messaging (WebSocket)

---

## 🔒 Security

- JWT Authentication
- Password Encryption
- Protected REST APIs
- CORS Configuration

---

## 🚀 Future Improvements

- Read Receipts
- File Sharing
- Typing Indicators
- Push Notifications
- Online Presence
- Cloud Deployment (AWS)

---

## 👨‍💻 Author

**Yatharth Kumar Rana**

