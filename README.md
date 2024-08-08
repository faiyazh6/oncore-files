# Oncore Files

Welcome to the GitHub repository for **Oncore Health**, an AI-enabled workflow automation platform dedicated to enhancing oncology care. This repository contains the frontend and server components of our platform, aimed at reducing administrative burdens in oncology care settings.

## Repository Structure

This project includes two main components:
1. **[Oncore Frontend](https://github.com/faiyazh6/oncore-frontend)** - Manages the user interface and client-side interactions.
2. **[Oncore Server Public](https://github.com/faiyazh6/oncore-server-public)** - Handles backend logic, server operations, and data management.

### Oncore Frontend

The frontend repository hosts the user interface components developed using JavaScript, primarily focusing on React for rendering and managing state. Key files and their functions include:

- `cerner_auth.js` and `epic_auth.js`: Authentication scripts for integration with Cerner and Epic systems respectively.
- `src/`: Contains all React components and the main application logic.
- `public/`: Hosts static files like HTML, CSS, and images.
- `package.json`: Defines project metadata and dependencies.

#### Setup and Running

To set up and run the frontend locally:
cd oncore-frontend
npm install
npm start

This will start the development server, usually accessible at http://localhost:3000.

### Oncore Server Public

The server component is built with Node.js and Express, providing RESTful APIs and managing communication with databases and external services. Key directories and files include:

- `controllers/`: Contains files that define functions to handle requests.
- `models/`: Defines data models for database interactions.
- `routes/`: Sets up routes for incoming HTTP requests.
- `server.js`: The main server file that configures and starts the server.
- `config/`: Includes configuration files, potentially for different environments.

#### Setup and Running

To run the server component:
cd oncore-server-public
npm install
node server.js

Ensure that all necessary environment variables are set before starting the server, typically found in config/.

## Cloning the Repositories
To clone this parent repository along with its submodules, run:
git clone --recurse-submodules https://github.com/faiyazh6/oncore-files.git
