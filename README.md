# Airbnb Clone

A robust, full-stack booking platform inspired by Airbnb. This project demonstrates scalable backend architecture, secure APIs, relational database design, and modern DevOps practices. 
It is built with Django, MySQL, and GraphQL, following industry standards for clean, maintainable, and deployable code.

## 🔧 Tech Stack

- **Backend Framework:** Django (Python)
- **Database:** MySQL
- **API Layer:** REST & GraphQL
- **DevOps:** Docker, GitHub Actions
- **Version Control:** Git & GitHub

## 📦 Features

- User registration, login, and authentication (JWT)
- Host property listings (CRUD operations)
- Search and filter properties
- Booking and availability management
- Reviews and ratings system
- Admin dashboard for property and user management
- CI/CD pipeline with automated testing and deployment

## 🧠 Architecture Overview

This project follows a modular and layered architecture:

- **API Layer:** Cleanly separated GraphQL and REST endpoints
- **Business Logic Layer:** Reusable services and serializers
- **Data Layer:** Django ORM integrated with a relational MySQL schema
- **DevOps Layer:** Dockerized app with GitHub Actions for CI/CD

---


## 🧩 Database Schema (Simplified)

- **User**: id, name, email, role (guest/host), password
- **Property**: id, title, location, price, host_id (FK)
- **Booking**: id, property_id, guest_id, check_in, check_out
- **Review**: id, booking_id, rating, comment

All relationships follow proper foreign key constraints and indexing strategies for performance.

## 📌 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/airbnb-clone.git
   cd airbnb-clone
