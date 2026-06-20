# Client Manager Backend API

REST API backend built with json-server for a React client management system.

This project provides full CRUD operations for client data and is used as a mock backend for frontend integration and deployment practice.

---

## 🚀 Tech Stack

- json-server
- REST API

---

## 📦 Features

- Get all clients
- Get client by ID
- Create new client
- Update client
- Delete client
- Mock backend for frontend development

---

## 🌐 Live API

Base URL:
https://client-manager-tailwind-backend.onrender.com

Example endpoint:
https://client-manager-tailwind-backend.onrender.com/clients


### Endpoints

- GET /clients
- GET /clients/:id
- POST /clients
- PUT /clients/:id
- DELETE /clients/:id

---

## 🔗 Frontend Integration

This API is consumed by the React frontend application deployed on Vercel.

The frontend communicates with this service through environment variables using: VITE_API_URL
