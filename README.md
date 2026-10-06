# 🎬 Movie Ticket Booking System

A full-stack **Movie Ticket Booking System** built using the **MERN Stack**. Users can browse movies, select shows and seats, and book tickets securely using Stripe.

## 🚀 Features

### 👤 User Features
- User registration and login
- JWT-based authentication
- Browse available movies
- View movie details
- View available shows
- Select seats
- Book movie tickets
- Secure online payment using Stripe
- View booking history

### 🛠️ Admin Features
- Admin authentication
- Add movies
- Update movie details
- Delete movies
- Create and manage shows
- View bookings
- Manage movie information

## 🧑‍💻 Tech Stack

### Frontend
- React.js
- Vite
- JavaScript
- CSS
- Axios
- React Router

### Backend
- Node.js
- Express.js
- REST APIs
- JWT
- bcrypt
- Stripe

### Database
- MongoDB
- Mongoose

### Payment
- Stripe

## 🏗️ Architecture

```text
                    ┌───────────────┐
                    │     User      │
                    └───────┬───────┘
                            │
                            ▼
                    ┌───────────────┐
                    │    React      │
                    │   Frontend    │
                    └───────┬───────┘
                            │
                         REST API
                            │
                            ▼
                    ┌───────────────┐
                    │ Node + Express│
                    │    Backend    │
                    └───────┬───────┘
                            │
                 ┌──────────┴──────────┐
                 ▼                     ▼
          ┌─────────────┐       ┌─────────────┐
          │   MongoDB   │       │    Stripe   │
          └─────────────┘       └─────────────┘
