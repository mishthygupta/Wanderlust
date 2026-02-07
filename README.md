# Wanderlust – Online Accommodation Booking Platform

Wanderlust is a full-stack web application that allows users to explore, list, and book accommodations. The platform focuses on secure authentication, clean database design, and scalable backend architecture.

---

## Features

- User authentication and authorization (login/signup)
- Create, read, update, and delete accommodation listings
- User reviews and ratings for listings
- RESTful APIs with middleware-based error handling
- Secure session management
- Relational data modeling for users, listings, and reviews

---

## Tech Stack

**Frontend**
- EJS
- HTML, CSS, Bootstrap

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB (Mongoose ODM)

**Other Tools**
- REST APIs
- Middleware
- Git & GitHub

---

## 🧠 System Design Overview

- MVC-based architecture for maintainability
- Modular routing and controllers
- Centralized error handling using middleware
- Database relationships modeled using Mongoose schemas

---

## Project Structure
Wanderlust/  
│── models/ # Mongoose schemas  
│── routes/ # Application routes  
│── controllers/ # Business logic  
│── views/ # EJS templates  
│── public/ # Static assets  
│── middleware/ # Custom middleware  
│── app.js # Main application entry  

---

## ⚙️ Getting Started

## Prerequisites
- Node.js
- MongoDB

## Installation

```bash
git clone https://github.com/mishthygupta/Wanderlust.git
cd Wanderlust
npm install
```

## Run the application

```bash
npm start
```

*The app will run on:*
http://localhost:3000

## Future Enhancements

- Payment gateway integration
- Advanced search and filtering
- Image upload optimization
- Role-based admin dashboard

## Author

 Mishthy Gupta  
 B.Tech CSE (AI & ML)  
 mishthygupta2005@gmail.com

 GitHub: https://github.com/mishthygupta
