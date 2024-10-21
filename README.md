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
    git clone https://github.com/ZmnRobin/docusign-clone.git
    ```

2. **Install Dependencies:**

    Navigate to the project directory:

    ```bash
    cd docusign
    ```
    ```bash
    cd client
    ```
    ```bash
    cd server
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

## Collaborating on Features

**Working on Your Feature:**

- Make changes to the codebase within either the `client` or `server` directory, depending on your specific contribution.

**Committing Changes:**

- Use `git add` to stage your changes.
- Use `git commit` to create a meaningful commit message that explains the changes you've made.

**Pushing Changes:**

Once you're ready to share your work, push your feature branch to the remote repository:

```bash
git push origin your-feature-branch
```

**Creating a Pull Request:**

- Visit the repository on GitHub and create a new pull request from your feature branch to the `dev` branch.
- Provide a detailed description of the changes you've made and any relevant information for reviewers.

**Reviewing Changes:**

- Team members can review your pull request, provide feedback, and suggest changes.
- Make any necessary modifications to your code based on the feedback received.

**Merging Your Feature:**

- Once your pull request has been approved, you can merge your feature branch into the `dev` branch.
- Make sure to resolve any merge conflicts that may arise during the merge process.
