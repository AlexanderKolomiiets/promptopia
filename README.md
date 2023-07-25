# Promptopia - Share Your Thoughts with the World!

[DEMO LINK](https://promptopia-mauve-theta.vercel.app/)

Welcome to Promptopia, a tool where you can sign up and share your thoughts with the world! This project is built using React, Next.js, and MongoDB, providing a seamless and user-friendly experience for both writers and readers.

## Table of Contents

- [Getting Started](#getting-started)
  - [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Technologies](#technologies)
- [CRUD Operations](#crud-operations)

## Getting Started

Follow the steps below to set up Promptopia on your local machine.

### Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/AlexanderKolomiiets/promptopia.git
cd promptopia
```

2. Install the dependencies:

```
npm install
```

3. Create a `.env` file in the root directory of the project and provide the MongoDB connection string. For example:

```
GOOGLE_ID=your-google-id
GOOGLE_CLIENT_SECRET=your-google-secret
MONGODB_URI=your-mongodb-connection-string
```

## Usage

To start the development server, run the following command:

```
npm run dev
```

Visit `http://localhost:3000` in your web browser to access Promptopia.

## Features

Promptopia offers the following features:

- User Sign Up: Create an account using your Google mail.
- Post Creation: Share your thoughts and ideas with the world by creating posts.
- Public Visibility: All posts are saved in MongoDB and are visible to everyone visiting the platform.
- Seamless UI: The React and Next.js stack provides a smooth and responsive user interface.
- Authentication: Only registered users can create and publish posts.
- CRUD Operations: Users can Create, Read, Update, and Delete their own posts.

## Technologies

Promptopia is built using the following technologies:

- React: A popular JavaScript library for building user interfaces.
- Next.js: A framework for server-rendered React applications.
- MongoDB: A NoSQL database for storing user information and posts.

## CRUD Operations

Promptopia provides full CRUD functionality for user posts:

- Create: Users can create new posts by filling out a simple form and clicking the "Create" button.
- Read: All published posts are visible to users on the main page.
- Update: Users can edit their own posts by clicking on the "Edit" button on their profile page. This allows them to modify the content of the post.
- Delete: If a user decides to remove one of their posts, they can do so by clicking the "Delete" button on the profile page.

