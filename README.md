# 🎬 Movie Application

## 🎯 Objective
The objective of this project is to develop a full-stack application for managing movies. The application allows users to browse, search, and manage movies. Users can view details of each movie, add new movies, update existing movies, and delete movies. This project serves as a demonstration of building a full-stack web application using Spring Boot, MongoDB, and React.

## 📋 Project Overview
The Movie Application should implement the following functionalities:

- Display a list of movies.
- Allow users to search for movies by title, genre, release year, etc.
- Show detailed information about each movie.
- Enable users to add new movies to the database.
- Allow users to update existing movie details.
- Provide the option to delete movies from the database.

## 📝 User Cases
1. As a movie enthusiast, I want to browse a collection of movies so that I can discover new films to watch.
2. As a user, I want to search for movies based on different criteria (e.g., title, genre) to find specific movies easily.
3. As a user, I want to view detailed information about a movie, including its plot, cast, and release date.
4. As an administrator, I want to add new movies to the database to keep the collection up-to-date.
5. As an administrator, I want to update existing movie details (e.g., title, genre) in case of any changes.
6. As an administrator, I want to remove outdated or irrelevant movies from the database.

## 🚀 REST API Endpoints
The backend of this application exposes the following REST API endpoints:

1. GET /api/movies - Retrieve a list of all movies.
2. GET /api/movies/{id} - Retrieve details of a specific movie by its ID.
3. POST /api/movies - Add a new movie to the database.
4. PUT /api/movies/{id} - Update details of an existing movie.
5. DELETE /api/movies/{id} - Delete a movie from the database.

## 📊 Entities
The entities of the project include:

- Movie: Represents a movie entity with attributes such as title, genre, release year, plot, etc.

## 🛠️ Technologies Implemented
The technologies implemented in this project are as follows:

- **Backend:**
  - Spring Boot: Framework for building Java-based applications.
  - MongoDB: NoSQL database for storing movie data.
  - Spring Data MongoDB: Integration for using MongoDB with Spring applications.
  - Spring Web: Module for creating RESTful web services.
  
- **Frontend:**
  - React: JavaScript library for building user interfaces.
  - React Router: Library for declarative routing in React applications.
  - Axios: Promise-based HTTP client for making requests to the backend API.
  - Bootstrap: Front-end framework for designing responsive and mobile-first websites.

## 🤝 Contribution Guidelines
Contributions are welcome! Please follow the [contribution guidelines](CONTRIBUTING.md) before making any pull requests.

## 📄 License
This project is licensed under the [MIT License](LICENSE).
