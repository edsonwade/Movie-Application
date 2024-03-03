# 🎬 Movie Application

## 🎯 Objective
The objective of this project is to develop a full-stack microservice application for managing movies. The application, inspired by platforms like Netflix, aims to provide users with a seamless movie browsing and management experience. This project serves as a demonstration of building a scalable, resilient, and feature-rich movie application using microservices architecture, Spring Boot, MongoDB, React, and other technologies.

## 📝 Project Overview
The Movie Application should implement the following functionalities:

- Display a vast collection of movies categorized by genres, release year, popularity, etc.
- Allow users to search for movies by title, actors, directors, or keywords.
- Show detailed information about each movie, including synopsis, cast, ratings, and reviews.
- Enable users to stream movies seamlessly with adaptive bitrate streaming.
- Provide personalized recommendations based on user preferences and viewing history.
- Support user authentication and authorization for managing profiles, watchlists, and viewing history.
- Allow users to rate and review movies, as well as share their recommendations with others.
- Implement a robust content management system for administrators to add, update, or remove movies and metadata.

## 📋 User Cases
1. As a movie enthusiast, I want to explore a vast collection of movies across various genres and categories.
2. As a user, I want to easily search and discover movies based on my preferences, including genre, actors, directors, and keywords.
3. As a user, I want to view comprehensive details about a movie, including its synopsis, cast, ratings, and reviews.
4. As a subscriber, I want to stream movies seamlessly without buffering, with support for adaptive bitrate streaming.
5. As a user, I want to receive personalized recommendations based on my viewing history and preferences.
6. As a registered user, I want to manage my profile, including watchlists, viewing history, and preferences.
7. As a movie enthusiast, I want to rate and review movies to share my opinions with others.
8. As an administrator, I want to manage the movie catalog, including adding, updating, and removing movies and metadata.

## 🚀 Microservices Architecture
The Movie Application is designed using a microservices architecture, with each microservice responsible for a specific domain or functionality. The microservices include:
- Movie Catalog Service
- User Service
- Authentication Service
- Recommendation Service
- Streaming Service
- Content Management Service

## 🔀 Kafka Integration
Kafka is used for asynchronous communication between microservices, enabling event-driven architecture. Events such as user actions, movie updates, and recommendations are published to Kafka topics, allowing other services to react accordingly.

## 🌐 AWS Lambda Integration
AWS Lambda functions are utilized for serverless processing of background tasks, such as generating personalized recommendations, processing user actions, and handling notifications.

## 🐳 Docker Compose
To easily set up and run the Movie Application, you can use Docker Compose. Run the following command in the root directory of the project:

```bash
docker-compose up
```

## 📊 Entities
The entities of the project include:

- Movie: Represents a movie entity with attributes such as title, genre, release year, synopsis, cast, ratings, and reviews.
- User: Represents a user entity with attributes such as username, email, password, preferences, watchlists, and viewing history.

## 🛠️ Technologies Implemented
The technologies implemented in this project are as follows:

- **Backend:**
  - Spring Boot: Framework for building microservices in Java.
  - Spring Cloud: Provides tools for building microservices architecture, including service discovery, configuration management, and distributed tracing.
  - Netflix Eureka: Service discovery server for locating microservices.
  - MongoDB: NoSQL database for storing movie data and user profiles.
  - Spring Security: Provides authentication and authorization for user access.
  - Kafka: Distributed event streaming platform for asynchronous communication.
  - AWS Lambda: Serverless computing service for executing code in response to events.
  
- **Frontend:**
  - React: JavaScript library for building user interfaces.
  - Redux: State management library for managing application state.
  - Axios: Promise-based HTTP client for making requests to the backend API.
  - Material-UI: React components library for designing user interfaces.
  - React Router: Library for declarative routing in React applications.

## 🤝 Contribution Guidelines
Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) before making any pull requests.

## 📄 License
This project is licensed under the [MIT License](LICENSE).


