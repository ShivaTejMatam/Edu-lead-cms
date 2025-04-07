# EduCMS

A basic CMS (Content Management System) built with Node.js, PostgreSQL, and Prisma, tailored for educational platforms. This backend handles course management, user registration, lead tracking, and remark management.

## Features
This CMS includes:

📦 PostgreSQL database setup
🚀 Node.js application with Express
🛠️ Prisma ORM for database interaction
🐳 Docker & Docker Compose support for containerized development
🔄 Database migration and seeding scripts

## Architecture

[Screenshot 2025-03-30 201454](https://github.com/user-attachments/assets/afde4f60-3287-4f54-8d65-bad1235c7a9c)

## Installation & Usage
▶️ Run with Docker
```bash
  docker-compose up --build
```
## Create a top-level .env file with the following:

```bash
DATABASE_URL="your_databse_url"
PORT=3000
```
Install dependencies and start the server:

```bash
npm i
npm run prisma:generate
npm run prisma:migrate
npm run seed
npm start
```
