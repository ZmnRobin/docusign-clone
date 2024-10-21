# Docusign Clone Thesis Project

This project aims to create a functional Docusign clone, replicating core document signing and management functionalities. The codebase is divided into two distinct sections:

- **client:** This directory houses the frontend application responsible for user interaction, document display, and signing features.
- **server:** This directory contains the backend API that handles document storage, access control, user management, and interaction with the frontend.

## Project Setup

**Prerequisites:**

- Node.js and npm (or yarn) installed on your system. You can download Node.js from [https://nodejs.org/](https://www.google.com/url?sa=E&source=gmail&q=https://nodejs.org/).

**Steps:**

1. **Clone the Repository:**
    Use Git to clone this repository to your local machine:

    ```bash
    git clone [https://github.com/your-username/docusign-clone-thesis.git](https://github.com/your-username/docusign-clone-thesis.git)
    ```

2. **Install Dependencies:**

    Navigate to the project directory:

    ```bash
    cd docusign-clone-thesis
    ```

    Install dependencies for both the client and server sides:

    ```bash
    npm install
    ```

## Running the Project

**Client (Frontend):**

1. **Change Directory:**
    Move into the `client` directory:

    ```bash
    cd client
    ```

2. **Start Development Server:**
    Run the following command to start the development server and launch the frontend application in your web browser (usually at http://localhost:3000):

    ```bash
    npm run dev
    ```

**Server (Backend):**

1. **Change Directory:**
    Move into the `server` directory:

    ```bash
    cd server
    ```

2. **Start Development Server:**
    Run the following command to start the development server for the backend API:

    ```bash
    npm run dev
    ```

## Collaboration with Teammates

**Branching Strategy:**

We recommend using the `git` branching strategy to manage your code effectively:

- **main:** This branch should always contain the latest stable and production-ready version of the codebase.
- **dev:** Use this branch for feature development and bug fixes. Create new feature branches from `dev` to work on specific tasks.