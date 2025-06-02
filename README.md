# Git-Actions 🚀

A full-stack application with a complete CI/CD pipeline using **GitHub Actions**, **Cypress testing**, and **Render deployment**. This project demonstrates automated testing on Pull Requests and seamless production deployment on branch merges — all with a connected **MongoDB Atlas** database.

---

## 📌 Table of Contents

- [Description](#description)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [CI/CD Workflow](#cicd-workflow)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [Screenshots](#screenshots)
- [License](#license)

---

## 📖 Description

This project implements a modern development workflow where:

- New features are added via **feature branches**
- Pull Requests into `develop` run **Cypress component tests**
- Merges from `develop` to `main` trigger **automatic deployment to Render**
- A **MongoDB Atlas** database is used for persistent storage

---

## ✨ Features

- ✅ GitHub Actions CI/CD setup
- ✅ Cypress component tests
- ✅ Deployment to Render using deploy hooks
- ✅ Full TypeScript support
- ✅ MongoDB Atlas integration

---

## 🛠 Tech Stack

- **Frontend**: Vite + React + TypeScript
- **Backend**: Express.js + Node.js + TypeScript
- **Database**: MongoDB Atlas (via Mongoose)
- **CI/CD**: GitHub Actions
- **Testing**: Cypress
- **Hosting**: Render

---

## 🔁 CI/CD Workflow

### 🧪 On Pull Request to `develop`
- Runs Cypress component tests via GitHub Actions

### 🚀 On Push to `main`
- Triggers a **deploy hook** to Render
- Starts a production deployment

---
render link : 
https://git-actions.onrender.com/

## 🚀 Getting Started (Locally)

```bash
# Clone the repo
git clone https://github.com/Geek-N/Git-Actions.git
cd Git-Actions/Develop

# Install dependencies
npm install

# Start the app (dev mode)
npm run dev