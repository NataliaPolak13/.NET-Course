# 📱 Reactivities (.NET 9, React 19 & React Query)

> **This is a learning project based on the Udemy course:  
> _"The Complete Guide to Building an App from Start to Finish using .NET 9.0, React 19 and React Query"_ by Neil Cummings.  
> This repository documents my learning progress and hands-on experience with a modern full-stack tech stack.**

---

## 🧠 Project Purpose

The goal of this project is to build a fully functional social events web application from scratch — similar to platforms like Meetup or Facebook Events — allowing users to create and join activities.

This application is built using modern tools like ASP.NET Core and React with TypeScript, following Clean Architecture and the CQRS + Mediator design pattern. It covers both backend and frontend development and reflects real-world application structure.

---

## ⚙️ Tech Stack

### 🔧 Backend:
- **.NET 9.0 (ASP.NET Core Web API)**
- **Entity Framework Core**
- **CQRS + Mediator Pattern** 
- **AutoMapper**
- **ASP.NET Core Identity** 
- **SignalR** 

### 💻 Frontend:
- **React 19.1.0 + TypeScript**
- **React Query** 
- **React Hook Form + Zod** 
- **Semantic UI React**
- **React Router**
- **MobX** 

---

## 🚀 Getting Started

> Note: This is a multi-project solution — you’ll need to run the backend and frontend separately.

## 🛠️ First-Time Setup (after cloning the repo)

> This section is only needed once, or when setting up on a new machine.

### 1️⃣ Backend 

```bash
cd API
dotnet restore                    
dotnet ef database update          
dotnet run
```                         

### 2️⃣ Frontend
```bash
cd client
npm install                        
npm run dev
```                     

## 🚀 Running the App for daily use

### Backend:

```bash
cd API
dotnet run
```

### Frontend:
```bash
cd client
npm run dev
```
---

## ✍️ Notes

- This project was built step-by-step by following the course content.
- No major custom features have been added yet — this repository focuses on learning and tracking progress.
- I plan to enhance the application with my own ideas in the future, including:
  - **New pages** and navigation structure
  - A **custom visual style and UI redesign** 
  - Additional features and technical improvements
- This repository is public as part of my developer portfolio and demonstrates my skills in working with full-stack technologies, Git and project organization.

---
## 📄 License

This is an educational project created by following a commercial Udemy course by Neil Cummings.  
It is **not intended for production use**.  
This repository serves as a personal learning record and portfolio example only.
