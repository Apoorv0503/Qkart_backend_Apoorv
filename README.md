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
# API Documentation

## User APIs

### GET /v1/users

- **Description**: Retrieves user data.
- **Authentication**: Requires JWT token.

## Shopping Cart APIs

### GET /v1/cart

- **Description**: Retrieves the user's shopping cart.
- **Authentication**: Requires JWT token.

### POST /v1/cart

- **Description**: Adds an item to the user's shopping cart.
- **Authentication**: Requires JWT token.

### PUT /v1/cart

- **Description**: Updates an item in the user's shopping cart.
- **Authentication**: Requires JWT token.

## Testing

### Test-Driven Development

- **Checkout Logic**: Developed with rigorous unit and integration testing.
- **Jest Framework**: Ensured seamless integration with Jest for robust testing.

# Deployment

## MongoDB Atlas

Setup MongoDB Atlas for cloud data storage to ensure scalability and reliability.

## Render

Deployed QKart backend on Render for robust and scalable deployment.

# Contributing

We welcome contributions to QKart Backend! Please follow these steps to contribute:

1. **Fork the repository.**
2. **Create a new branch:**
   ```bash
   git checkout -b feature-branch
   ```
3. **Make your changes and commit them**
   ```bash
   git commit -m 'Add new feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature-branch
   ```
5. **Create a Pull Request.**

