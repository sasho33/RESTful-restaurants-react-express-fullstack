# RESTful Restaurants API

## Project Overview

Welcome to the RESTful Restaurants API project! This project is an off-platform endeavor where I have developed a REST API to bridge the front-end and back-end of a restaurant review site. This comprehensive site enables users to view, add, star, and comment on various restaurants. While the front-end and some API routes were pre-built, my primary focus was on integrating the functionality for handling starred restaurants and comments.

### Key Features

- **REST API Endpoints**: Creation of RESTful API endpoints using Express.js.
- **Front-End and Back-End Integration**: Implementation of communication between the website's front-end and back-end.
- **Local Development**: All development was done locally on my computer.
- **Command-Line Proficiency**: Utilized terminal commands to navigate and manage the project directory.

### Development Environment

This project was developed using a local text editor, Visual Studio Code (VSCode), recommended for its robust features and support for web development.

## Installation and Setup

### 1. Download the Starting Code

First, download the folder containing the starting code for the project. The project structure is divided into two main directories: `frontend` and `backend`.

- **Frontend Directory**: Contains all the front-end code of the application, including API calls (in the `api` folder) and React components (in the `components` folder).
- **Backend Directory**: Houses all the back-end code. The `routes` folder includes all routes for API calls from the front-end.

### 2. Setting up the Back-End

Navigate to the `backend` folder and install all the necessary dependencies to set up the back-end.

### 3. Setting up the Front-End

Similarly, set up the front-end by navigating to the `frontend` folder and installing the required dependencies.

### 4. Running the Application

To run the application locally:

- Start the back-end server first.
- Then, launch the front-end server.
- Use `npm start` in both the front-end and back-end directories to start the project.

_Note: The back-end server uses `nodemon` for automatic restarts upon file changes._

## Building the API Endpoints

The following REST endpoints were developed:

- Get a specific starred restaurant.
- Add a restaurant to the list of starred restaurants.
- Delete a restaurant from the starred list.
- Update comments on a starred restaurant.

All endpoints were created within the `starredRestaurants.js` file in the `backend/routes` directory.

## Review and Expansion

Upon completion, the REST API featured four new endpoints, expanding the functionality of the existing codebase. For further exploration, the Express.js documentation offers extensive insights into advanced routing and response methods.
