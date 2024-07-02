# 📚 Microservices Blog App

This project is a microservices-based blog application where users can create posts and add comments. The application is built with a React frontend and multiple backend services to handle different aspects of the system. The architecture ensures scalability and separation of concerns.

## ✨ About

This Microservices Blog App allows users to create posts and add comments. It uses a React frontend and multiple backend microservices for posts, comments, moderation, and querying, all coordinated by an event bus. This architecture ensures scalability and easy maintenance.

## 🗂 Project Structure

- **client**: The frontend application built with React.
- **comments**: Microservice responsible for handling comments on posts.
- **event-bus**: Centralized service to manage and propagate events between other microservices.
- **moderation**: Service to moderate content, ensuring comments and posts adhere to community guidelines.
- **posts**: Microservice responsible for creating and managing posts.
- **query**: Service to aggregate and serve data for efficient querying.

## 🌟 Features

- **Posts**: Users can create new posts with titles.
- **Comments**: Users can comment on existing posts.
- **Moderation**: Comments are moderated to ensure they meet community standards.
- **Event Bus**: Manages communication between services to maintain data consistency.

## 🚀 Getting Started

### ✅ Prerequisites

- Node.js
- Docker (optional, for containerized deployment)

### 🔧 Installation

1. Clone the repository:

```bash
git clone https://github.com/animeshkumar7717/Microservices.git
cd Microservices
