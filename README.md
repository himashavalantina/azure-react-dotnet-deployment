# 🚀 Azure React + .NET Full-Stack Deployment

## 📌 Project Overview

This project demonstrates how to build and deploy a full-stack web application using:

* ⚛️ React.js (Frontend)
* ⚙️ .NET Web API (Backend)
* ☁️ Microsoft Azure (Cloud Hosting)

The frontend is deployed using **Azure Static Web Apps**, and the backend is hosted on **Azure App Service**, with CI/CD enabled via GitHub Actions.

---

## 🎯 Objectives

* Deploy a React application to Azure Static Web Apps
* Deploy a .NET Web API to Azure App Service
* Integrate frontend and backend services
* Understand cloud deployment and CI/CD pipelines

---

## 🏗️ Project Structure

```
/my-frontend   → React.js application
/MyBackend     → .NET Web API
```

---

## ⚙️ Technologies Used

* React.js
* .NET 8 / .NET 9 Web API
* Microsoft Azure
* GitHub Actions (CI/CD)
* Git & GitHub

---

## 🚀 Local Setup Instructions

### 🔹 Frontend (React)

```bash
cd my-frontend
npm install
npm start
```

Runs on: http://localhost:3000/

---

### 🔹 Backend (.NET API)

```bash
cd MyBackend
dotnet restore
dotnet run
```

Runs on: https://localhost:5001/

---

## ☁️ Azure Deployment

### 🌐 Frontend Deployment

* Service: Azure Static Web Apps
* Auto-deployed via GitHub Actions
* Build output: `build/`

### 🔧 Backend Deployment

* Service: Azure App Service
* Runtime: .NET
* CI/CD enabled via GitHub Actions

---

## 🔗 Live URLs

* 🌐 Frontend: https://<your-frontend-url>.azurestaticapps.net
* 🔧 Backend API: https://<your-api-url>.azurewebsites.net

---

## 🔄 API Integration

The React frontend communicates with the .NET backend using REST API calls.

Example:

```javascript
fetch("https://<your-api-url>.azurewebsites.net/weatherforecast")
```

---

## 🔐 CORS Configuration

CORS is enabled in the backend to allow requests from the frontend domain.

--

## 📚 Learning Outcomes Achieved

✔ Deployed React app to Azure
✔ Deployed .NET API to Azure
✔ Integrated frontend with backend
✔ Used GitHub Actions for CI/CD
