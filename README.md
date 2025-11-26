## Task Tracker — Fullstack Application (React + Node.js + MySQL)

A complete task-tracking application with user authentication, task management, and a fully structured backend connected to a MySQL database. Users can create tasks, mark them as completed or uncompleted, delete them, and manage their account through a simple and intuitive interface.

---

## 📋 Project Overview

The Task Tracker application allows users to:

Add new tasks with a description

Mark tasks as completed or uncompleted

Automatically move completed tasks to the bottom of the list

Display completed tasks with a strikethrough style

Delete tasks

Maintain user sessions through authentication

Persist data in a MySQL database

This project includes both frontend (React + Vite) and backend (Node.js + Express + MySQL).

---

## 🎨 Frontend

The frontend is built with:

React

TypeScript

Vite

Wouter or React Router DOM (depending on your routes)

Frontend Features

Interactive task list

Dynamic UI updating based on task state

Authentication flows (login, register, logout)

API communication with backend

Clean and minimal interface

---

## 🛠 Backend (Node.js + Express + MySQL)

The backend uses the following dependencies:

Express

MySQL2

bcrypt (password hashing)

jsonwebtoken (JWT auth)

cookie-parser (session cookies)

CORS (custom middleware)

dotenv

uuid (ID generation)

---

## 🔐 Authentication System

The backend implements:

User registration with hashed password (bcrypt)

Login with JWT generation

Session storage via HTTP cookies

Token validation middleware (if implemented in your routes)

Logout endpoint

---

## 🗄 Database

MySQL is used as the main database

Backend connects through mysql2

---

<img src="./frontend-task/src/assets/login.png" alt="Task Tracker Preview" width="50%" />

---

<img src="./frontend-task/src/assets/notas.png" alt="Task Tracker Preview" width="50%" />
