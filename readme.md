# Mohammad Arkan — Backend Developer 👨‍💻

## ⭐ Featured Projects

### [DeshCode — LeetCode clone / online judge](https://github.com/mdarkanurl/DeshCode)
**Tech Stack:** TypeScript, Node.js, Express.js, PostgreSQL + Prisma, Redis, RabbitMQ, Debezium, Docker (execution workers)
**Highlights:**
- Secure code execution: user submissions run inside isolated Docker worker containers.
- Contest system with real-time leaderboards and rank updates.
- Background job processing via RabbitMQ; caching and fast lookups with Redis.
- Secure Auth and OAuth system using JWT token and Google, GitHub OAuth.
- CDC (Debezium) for syncing/streaming DB events where needed.
- Clean OOP design, error handling, and test coverage for core flows.

### [MedHub — Medical Management System](https://github.com/mdarkanurl/MedHub)
**Tech Stack:** Node.js, TypeScript, PostgreSQL (Prisma), RabbitMQ, JWT, Resend, Zod
**Highlights:**
- Microservices: Users (auth), Admin, Email.
- JWT auth with account verification, password recovery, and token refresh.
- Async email & notifications via RabbitMQ → Email Service (Resend).
- Prisma + Zod for type-safe DB access and runtime validation.

### [Blog API — Blog Management API](https://github.com/mdarkanurl/Personal-Blogging-Platform-API)
**Tech Stack:** Express.js, JWT, MySQL, bcrypt.js, Joi
**Highlights:**
- JWT auth: signup, login, logout with secure password hashing (bcrypt).
- Users can create / update / delete their own posts; role-based access restricts edits/deletes to owners and admins.
- Request validation and schemas powered by Joi for reliable input handling.
- Protected routes and auth middleware for clean, secure endpoint control.

### [Authentication System — Passport & JWT Auth](https://github.com/mdarkanurl/authentication)
**Tech Stack:** Node.js, Express, Passport.js, JWT, bcrypt.js, MongoDB (Mongoose)
**Highlights:**
- User registration & login with secure password hashing using bcrypt.
- Passport.js handles authentication strategies; JWT used for stateless session management.
- Middleware for protected routes and role-based access control.
- Clean separation of auth flows (signup, login, refresh tokens, logout) for easy integration.

---

## 📂 Other notable work
- Worker systems and background processing examples (Dockerized).
- Fully Dockerized microservices Backend applications examples (DeshCode).
- Integrations for email & notifications.
- Several small utilities and boilerplates demonstrating robust error handling and testing patterns.
- Building Backend app with microservices architecture.

---

## 🧩 Architecture & Engineering Choices
- Modular design: Separation of concerns via services, controllers, repositories.
- Reliable messaging: RabbitMQ/Kafka for eventual consistency and decoupled processing.
- Performance: Redis for caching leaderboards, sessions, and hot lookups.
- Observability: Structured logging, error handling, and monitoring hooks.
- Testing: Unit and integration tests for critical paths using Jest and Supertest with Testcontainers.
- Separation of concerns: Microservices and worker processes where workloads need isolation (e.g., code execution).

---

## 📈 What I focus on in projects
- Clean, testable code with clear boundaries.
- Properly handled async flows and retries for message processing.
- Secure auth and safe handling of sensitive operations.
- Developer experience: good READMEs, .env.example, scripts, and minimal setup friction.

---

## 🤝 Want to collaborate or hire me?
- Email: **mdarkanurl@gmail.com**
- LinkedIn: [https://www.linkedin.com/in/thearkan](https://www.linkedin.com/in/thearkan)

---
