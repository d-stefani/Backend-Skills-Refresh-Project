# Backend Skills Refresh Project

A hands-on project designed to sharpen your backend engineering skills using **TypeScript**, **Node.js**, and **MySQL**. Structured as an 8-week curriculum focused on mastery through practical development.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Features](#features)
- [How to Run](#how-to-run)
- [Testing](#testing)
- [Deployment](#deployment)

---

## Project Overview
Build a production-style backend application with authentication, role-based access control, and RESTful API design. Emphasis is placed on best practices, maintainability, and real-world tooling.

## Tech Stack
- **Language:** TypeScript (strict mode)
- **Runtime:** Node.js (ESM)
- **Framework:** Express.js or Fastify
- **Database:** MySQL
- **ORM/Query Builder:** Prisma, Knex, or mysql2
- **Validation:** Zod or class-validator
- **Authentication:** JWT + Refresh Tokens
- **Testing:** Jest or Vitest
- **DevOps:** Docker + GitHub Actions
- **Linting & Formatting:** ESLint, Prettier

---

## Getting Started
1. Clone the repo
2. Install dependencies:
   ```bash
   pnpm install
   # or
   npm install
   ```
3. Copy and update environment config:
   ```bash
   cp .env.example .env
   ```
4. Start MySQL (via Docker or local install)
5. Run database migrations and seeds

---

## Project Structure
```bash
src/
├── controllers/
├── services/
├── models/            # DB models or schema definitions
├── routes/
├── middlewares/
├── utils/
├── config/
└── index.ts
```

---

## Features
- [ ] User Registration & Login
- [ ] JWT Authentication
- [ ] Role-based Authorization (RBAC)
- [ ] RESTful API Design (CRUD)
- [ ] Pagination, Filtering, Sorting
- [ ] Full Test Coverage
- [ ] SQL Migrations & Seeders
- [ ] Linting & Pre-commit Hooks
- [ ] Dockerized App
- [ ] CI/CD via GitHub Actions

---

## How to Run
```bash
# Start dev server
pnpm dev

# Or using nodemon
pnpm nodemon
```

---

## Testing
```bash
# Run all tests
pnpm test

# Test with coverage
pnpm test:coverage
```

---

## Deployment
1. Build and tag Docker image
2. Push to container registry (optional)
3. Deploy to your platform (Render, Railway, ECS, etc.)

---
