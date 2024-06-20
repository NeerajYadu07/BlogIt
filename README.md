- Name: Neeraj Yadu
- Company: CODTECH IT SOLUTIONS
- ID: CT08PD736
- Duration: 20th MAY 2024 to 20th JUNE 2024
- Mentor: Sravani Gouni

# Project Overview
# BLOGIT

Welcome to BLOGIT, a comprehensive blogging platform designed for ease of use and powerful functionality. Whether you're a seasoned blogger or just starting, BLOGIT provides the tools you need to create, manage, and share your content effortlessly.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
  - [Authentication](#authentication)
  - [Admin Panel](#admin-panel)
  - [Creating a Blog](#creating-a-blog)
  - [Reading a Blog](#reading-a-blog)
  - [Updating a Blog](#updating-a-blog)
  - [Deleting a Blog](#deleting-a-blog)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Create, Read, Update, Delete (CRUD) Blogs**: Manage your blog posts with ease.
- **Category Management**: Organize your blogs into various categories for better navigation and search.
- **Admin Panel**: An intuitive admin panel for managing users and content.
- **Authentication System**: Secure authentication using Firebase for user management and session control.
- **Responsive Design**: Optimized for all devices to ensure a seamless user experience.

## Technologies Used

- **Frontend**: Next.js
- **Backend**: Firebase (Authentication, Firestore)
- **Styling**: Tailwind CSS

## Getting Started

### Prerequisites

- Node.js (>= 14.x)
- Firebase Account
- Git

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/blogit.git
   cd blogit
2.  **Install Dependencies**:
    
    ```bash   
    npm install
    
3.  **Firebase Setup**:
    
    -   Create a new project on Firebase Console.
    -   Set up Firebase Authentication and Firestore.
    -   Obtain your Firebase configuration and replace the placeholder in the `.env.local` file.

### Running the Application

1.  **Start the Development Server**:
    
    ```bash
    npm run dev
    
2.  **Open Your Browser**: Navigate to `http://localhost:3000` to see the application in action.
    

## Usage

### Authentication

-   **Sign Up**: Create a new account using google.
-   **Sign In**: Log in with your existing account.
-   **Sign Out**: Log out from the application.

### Admin Panel

-   Access the admin panel from the navigation menu if you have admin privileges.
-   Manage users, approve or reject blog posts, and perform other administrative tasks.

### Creating a Blog

1.  Navigate to the "Create Blog" section.
2.  Fill in the title, content, and select a category.
3.  Publish the blog post.

### Reading a Blog

-   Browse through the categories or use the search feature to find blogs.
-   Click on a blog title to read the full content.

### Updating a Blog

1.  Go to "My Blogs" to view your posts.
2.  Select the blog you want to edit.
3.  Update the necessary fields and save changes.

### Deleting a Blog

1.  Go to "My Blogs" to view your posts.
2.  Select the blog you want to delete.
3.  Confirm the deletion.

## Contributing

We welcome contributions from the community. Please follow these steps to contribute:

1.  Fork the repository.
2.  Create a new branch.
3.  Make your changes and commit them.
4.  Push your changes to your fork.
5.  Open a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

Thank you for using BLOGIT! Happy blogging!
