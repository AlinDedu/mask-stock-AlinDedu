# Mask Stock

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Installation](#installation)

## Project Description

The project is a web application that allows users to manage hospital data. It provides features for user authentication, hospital order management, and a user-friendly interface for viewing and interacting with hospitals.

The main purpose of the project is to provide a platform for users to securely log in, create, update, and delete hospital records. It leverages React and React hooks for building the user interface, and uses a RESTful API for server-side interactions.

## Features

- User Authentication: Users can sign up and log in to access the hospital management functionality.

- Hospital Management: Users can view a list of hospitals, add new hospitals, update existing hospital records, and delete hospitals.

- Context API: The project utilizes the Context API from React to manage global state related to authentication and hospitals.

- Custom Hooks: Custom hooks are implemented to handle login, signup, and logout functionality, as well as accessing the authenticated user and hospital data.

- RESTful API Integration: The application communicates with a backend server through RESTful API endpoints to perform CRUD operations on hospital records.

This project aims to provide a foundation for building a hospital management system and can be extended with additional features such as search, filtering, and more. The code demonstrates best practices for structuring a React application and managing global state using the Context API.

## Backend Installation

### Prerequisites

- Node.js: Make sure you have Node.js installed on your machine. You can download it from [Node.js website](https://nodejs.org).

### Installation

1. Navigate to the backend directory.
   `cd backend `

2. Install backend dependencies using npm(Node Package Manager).
   `npm install`

3. Configure the backend server.

- Make sure you have a MongoDB database set up and running.
- Update the .env.sample file and rename it to .env

### Running the Backend Server

1. Start the backend server.
   `npm start`

2. The backend server should now be running on the port specified in .env file

Congratulations! You have successfully installed and set up the backend server. It is now ready to handle API requests from the frontend application.

## Frontend Installation

### Prerequisites

- Node.js: Make sure you have Node.js installed on your machine. You can download it from [Node.js website](https://nodejs.org).

### Installation

1. Navigate to the frontend directory
   `cd frontend`

2. Install frontend dependencies using npm(Node Package Manager).
   `npm install`

### Running the Frontend Application

1. Start the development server
   `npm start`

2. The frontend application should now be running on `http://localhost:3000`. Open your web browser and visit this URL to access the application.

Congratulations! You have successfully installed and set up the frontend application. You can now explore the hospital management system by interacting with the user interface and managing hospitals through the provided features.

Remember to ensure that the backend server is properly set up and running before using the frontend application.
