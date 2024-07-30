# Basic Profile Web

This is a basic profile web application built with Node.js, Express.js, MongoDB, EJS, JWT, and cookie-parser. The application allows users to register, log in, and view their profiles.

## Table of Contents

<ul>
  <li><a href="#features">Features</a></li>
  <li><a href="#prerequisites">Tech Stack</a></li>
  <li><a href="#installation">Installation</a></li>
  <li><a href="#usage">Configuration</a></li>
  <li><a href="#Middleware">Contributing</a></li>
  <li><a href="#license">License</a></li>
</ul>

## Features

<ul>
  <li>User registration and login/li>
  <li>User authentication and authorization</li>
  <li>Profile view</li>
  <li>Session management with cookie-parser</li>
  <li>Templating with EJS</li>
</ul>

## Prerequisites

Before you begin, ensure you have met the following requirements:
<ul>
  <li>Node.js and npm installed on your machine</li>
  <li>MongoDB installed and running</li>
</ul>

## Installation

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/amantiwarix/Basic_profile_web.git
    cd Basic_profile_web
    ```

2. **Install dependencies:**
    ```bash
    npm install
    ```

3. **Install Nodemon:**
    ```bash
    npm i nodemon
    ```

4. **Start the development server:**
    ```bash
    nodemon app.js
    or
    npx nodemon app.js
    ```

    The application will be available at `http://localhost:3000`.

## Usage

### Running the Application

<ul>
  <li><strong>Start the MongoDB server</strong> id it's not already running.</li>
  <li><strong>Start the application</strong>
  ```bash
    nodemon app.js
    or
    npx nodemon app.js
    ```</li>
  <li><strong>Open your browser</strong>nd navigate to `http://localhost:3000`.</li>
</ul>

## Middleware

<ul>
  <li><strong>`cookie-parser`</strong> - To parse cookies</li>
  <li><strong>`jsonwebtoken`</strong> - To handle JWT</li>
  <li><strong>`mongoose`</strong> - To interact with MongoDB</li>
  <li><strong>`express`</strong> - To create the server</li>
</ul>


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
