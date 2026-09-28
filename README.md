# 📚 Full-Stack E-Commerce Learning Guide

A practical, code-focused learning guide created from my Full-Stack E-Commerce project.

This guide is designed as a personal reference for rebuilding a full-stack application from scratch and remembering the actual code and syntax behind each feature.

---

## 🎯 Why I Created This Guide

While building my Full-Stack E-Commerce project, I learned many new concepts and technologies.

I understood what the concepts meant, but I noticed that I would often forget the actual code and syntax when trying to build something again from zero.

So I created this guide as a reusable reference.

Instead of only explaining:

> "What is JWT?"

the guide also shows:

> "What does the JWT authentication code actually look like?"

The goal is not to memorize the code.

The goal is to understand the structure, use the code as a reference, and gradually become able to write it independently.

---

## 📖 What's Inside

### 🔐 Authentication

- User registration
- Password hashing with bcrypt
- User login
- JWT generation
- JWT verification
- Protected routes
- `req.user`
- Authorization headers
- Bearer tokens

### 🛡️ Authorization

- User roles
- Admin roles
- Admin middleware
- Protected admin routes
- Role-based access

### 🗄️ MongoDB & Mongoose

- Schemas
- Models
- ObjectId
- References with `ref`
- Relationships between collections
- Embedded objects
- Arrays of referenced documents

### 🛒 Shopping Cart

- Adding products
- Removing products
- Updating quantities
- Calculating totals
- Managing cart state

### 📦 Orders

- Creating orders
- Connecting orders to users
- Connecting orders to products
- Customer information
- Order status
- Payment status
- Order lifecycle

### 💳 Payment Simulation

- Creating payments
- Connecting payments to users and orders
- Payment status
- Transaction IDs
- Simulated card processing
- Updating the order after successful payment

> The payment system is only a learning simulation. It does not process real money.

### 🌐 Frontend ↔ Backend

- Axios
- API services
- HTTP requests
- Protected requests
- Sending JWT tokens
- Connecting React to Express

### 🔑 Environment Variables

- `.env`
- `VITE_API_URL`
- `MONGO_URI`
- `JWT_SECRET`
- Development vs production configuration

### 🖼️ Images & Uploads

- Express static files
- Upload paths
- Image URLs
- Localhost vs deployed backend URLs
- Environment-based API URLs

### 🚀 Deployment

- GitHub
- Render
- Vercel
- Environment variables in production
- Frontend/backend separation
- Common deployment problems

### 📱 Responsive Design

- Tailwind responsive breakpoints
- Mobile layouts
- Responsive navigation
- Responsive tables
- Responsive forms
- Responsive modals
- Mobile-friendly spacing

### 🐛 Debugging

Examples of real problems encountered during development:

- MongoDB connection problems
- JWT/user ID mismatches
- API URL problems
- Images loading from `localhost` after deployment
- Git mistakes
- Backend/frontend communication errors
- Responsive layout problems

---

## 🏗️ Project Architecture

The guide follows the architecture used in my Full-Stack E-Commerce project:

```text
Frontend
   │
   │ Axios / HTTP
   ▼
Express Routes
   │
   ▼
Middleware
   │
   ▼
Controllers
   │
   ▼
Mongoose Models
   │
   ▼
MongoDB
