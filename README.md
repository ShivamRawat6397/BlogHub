# BlogHub

BlogHub is a modern and scalable blogging platform built with a robust backend, a shared common package for input validation, and an interactive frontend. This project leverages various technologies to deliver a seamless user experience for blogging.

## Table of Contents
- [Project Structure](#project-structure)
- [Backend](#backend)
- [Common](#common)
- [Frontend](#frontend)
- [Screenshots](#screenshots)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

The project is organized into three main directories:

- **backend**: Contains the server-side code for BlogHub.
- **common**: Includes shared code such as input validation schemas.
- **frontend**: Houses the client-side code for BlogHub.

## Backend

The backend of BlogHub is built using Hono, a lightweight web framework. It handles user authentication, blog creation, and other RESTful API functionalities. The backend uses Prisma with the Accelerate extension for efficient database operations.

### Key Features:
- User authentication with JWT.
- Blog management (create, update, delete).
- CORS support for secure cross-origin requests.

### Main Dependencies:
- `hono`
- `prisma/client`
- `prisma/extension-accelerate`
- `hono/jwt`
- `@shivam6397/common-app1`

## Common

The common package includes shared validation schemas and types, ensuring consistent data handling across the application. It is published as an npm package `@shivam6397/common-app1`.

### Key Features:
- Input validation with Zod.
- Shared types and interfaces for user and blog inputs.

### Main Dependencies:
- `zod`

## Frontend

The frontend of BlogHub is built with React and React Router for a dynamic and responsive user interface. It allows users to sign up, sign in, read blogs, and publish their own content.

### Key Features:
- User authentication and session management.
- Blog browsing and reading.
- Blog creation and editing.

### Main Dependencies:
- `react`
- `react-router-dom`
- `axios`

## Screenshots

### Sign In
![Screenshot (63)](https://github.com/ShivamRawat6397/BlogHub/assets/85786765/9d023cc1-86c7-4e74-be11-96bfb62aa2a7)


### Sign Up
![Screenshot (62)](https://github.com/ShivamRawat6397/BlogHub/assets/85786765/bac6692a-2288-4fe4-88f0-ed7833f478c4)


### Blogs
![Screenshot (67)](https://github.com/ShivamRawat6397/BlogHub/assets/85786765/e3c2892b-4012-48e6-ba31-cd9b9c8fab5c)


### Blog
![Screenshot (66)](https://github.com/ShivamRawat6397/BlogHub/assets/85786765/b46ff6f9-2acc-4aad-84b9-07d4fa83d613)


### Writing Blog
![Screenshot (65)](https://github.com/ShivamRawat6397/BlogHub/assets/85786765/d56f5683-938d-4249-b1b0-99cb7fa592b7)


## Installation

To get started with BlogHub, clone the repository and install the dependencies for each part of the project.

```sh
git clone https://github.com/yourusername/bloghub.git
cd bloghub

# Install backend dependencies
cd backend
npm install

# Install common dependencies
cd ../common
npm install

# Install frontend dependencies
cd ../frontend
npm install

## Usage

### Running the Backend

Navigate to the backend directory and start the server.

Copy code
cd backend
npm run dev

### Running the Frontend
cd frontend
npm i or npm install
npm run dev

## Environment Variables

Ensure you have the necessary environment variables set up for both backend and frontend. Refer to `.env.example` files in respective directories for required configurations.

## Contributing

We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch with your feature or bugfix.
3. Commit your changes and push the branch to your fork.
4. Create a pull request with a detailed description of your changes.
