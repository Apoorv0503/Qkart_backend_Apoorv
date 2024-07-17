### Live hosted URL:
https://qkart-backend-experss.onrender.com/

# QKart Backend

Welcome to the QKart Backend repository! This project is close to my heart, and I'm thrilled to share the highlights of our journey. Here’s an extensive overview of what we've accomplished:

## Overview

QKart Backend is a robust and scalable set of REST APIs designed to power the QKart application. It follows industry best practices to ensure high performance, security, and maintainability.

## Table of Contents

- [Features](#features)
- [Architecture](#architecture)
- [Setup and Installation](#setup-and-installation)
- [API Documentation](#api-documentation)
- [Testing](#testing)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Features

- **REST APIs**: Built a robust set of REST APIs adhering to industry best practices.
- **Layered Architecture**: Implemented a layered architecture for seamless maintenance and scalability.
- **MongoDB**: Leveraged MongoDB NoSQL database for efficient data storage.
- **Authentication**: Incorporated multiple authentication schemes ensuring top-notch security.
- **Testing**: Rigorously tested the implementation with unit and integration tests.

## Architecture

### QKart Layered Architecture

- **API Implementation**: Implemented GET /v1/users API for seamless user data retrieval.
- **Database Interaction**: Employed Mongoose for smooth interaction with MongoDB.
- **Request Validation**: Ensured client request validation with JOI schema.
- **Middleware**: Streamlined codebase using middlewares for better structure and readability.

### Request-Response Cycle in QKart

- **Authentication**: Strengthened API endpoints with JWT token authentication.
- **User Registration/Login**: Facilitated user registration and login with password authentication.
- **Security**: Ensured secure access to user data throughout the application.

### Implementing Shopping Cart APIs

- **Endpoints**: Crafted GET/POST/PUT endpoints for user's shopping cart.
- **User Experience**: Enhanced user experience with filtered API queries for efficient shopping cart management.

## Setup and Installation

### Prerequisites

- Node.js (>=14.x)
- MongoDB (local or MongoDB Atlas for cloud)
- npm (>=6.x)

### Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/qkart-backend.git
   cd qkart-backend
