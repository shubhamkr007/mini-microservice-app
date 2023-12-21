# Mini Microservices App

## Overview

This repository contains a mini microservices application built with Node.js, Express, Axios, CORS, and React. The application features services for handling posts, comments, events, queries, and moderation. Additionally, content filtering is implemented for comments to enhance user experience.

## Services

### 1. Post Service

Responsible for managing posts. It provides endpoints for creating, and fetching posts.

### 2. Comment Service

Manages comments related to posts. It supports actions like adding, and retrieving comments.

### 3. Event Bus

Facilitates communication between microservices by handling events and broadcasting them to relevant services.

### 4. Query Service

Handles queries and provides data from various services to the frontend. It acts as an intermediary between the frontend and microservices.

### 5. Moderation Service

Performs moderation tasks such as content filtering to ensure user-generated content complies with community standards.

## Technologies Used

- Node.js
- Express
- Axios
- CORS
- React

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/shubhamkr007/mini-microservice-app.git
   cd mini-microservice-app
   ```
2. **Install dependencies for each service:**
   ```bash
   cd <service_name>
   npm install
   ```
3. **Start each service:**
   ```bash
   cd <service_name>
   npm start
   ```
## Notes
- Ensure that the necessary ports are available for each service.
- Modify configuration files as needed for your development environment.
- This application is a basic example and may require additional features and security measures for production use.
