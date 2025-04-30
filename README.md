# The Wonderer's Pen

A MERN stack-based platform where users can explore, create, and share insightful blog posts that spark curiosity and self-expression.

![Image](client/public/Screenshot%202025-04-29%20210314.png)
![Image](client/public/Screenshot%202025-04-29%20210350.png)
![Image](client/public/Screenshot%202025-04-29%20210608.png)
![Image](client/public/Screenshot%202025-04-29%20210648.png)
![Image](client/public/Screenshot%202025-04-29%20210800.png)
![Image](client/public/Screenshot%202025-04-29%20211011.png)
![Image](client/public/Screenshot%202025-04-29%20211030.png)





## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies](#technologies)
- [Schema Diagram](#schema-diagram)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [License](#license)

## Project Overview

The Wonderer's Pen is a full-stack MERN application designed as a dynamic blogging platform where users can create, edit, and explore blog posts in a community-driven environment. With secure user authentication, rich-text post creation, and a clean, responsive UI, the platform encourages writers and readers to connect through thoughtful content. It supports seamless CRUD operations, features like personalized dashboards, and is deployed with MongoDB Atlas, Render, and Netlify for a modern and scalable web experience.

### User Roles

There are two distinct user roles within the system:

1. Author -  The Author role is granted once the user registers and logs in. Authors can create new posts & edit, manage their own content on the platform. This role is meant for content creators who want to share their thoughts, ideas, or articles on the platform. Authors are responsible for the posts they publish and can update them as needed after they go live.
2. Guest - Guests do not need to register or log in to access the platform. They can freely browse and view public posts without restrictions. The Guest role is designed for users who wish to read content without needing an account. This makes it easier for users to explore the platform before deciding to register and become an Author.



## Features

- [x] User Authentication & Authorization
- [x] Blog CRUD Operations
- [x] Minimalist, Aesthetic & Consistent Design
- [x] Security through password encryption
- [x] Mobile Responsiveness
- [x] Remote Accesibility 
  


## Technologies

- React.js
- Node.js
- Express.js
- MongoDB Cloud Atlas
- HTML
- CSS
- Javascript
- JWT Authentication
- Netlify
- Render


## File Structure

Client
```
└── 📁client
    └── .gitignore
    └── package-lock.json
    └── package.json
    └── 📁public
        └── _redirects
        └── folder-structure.md
        └── index.html
        └── manifest.json
        └── robots.txt
        └── The Wonderer's Pen.png
        └── The Wonderer's Pen2.png
    └── 📁src
        └── App.js
        └── 📁css
            └── App.css
            └── contact.css
            └── forms.css
            └── home.css
            └── index.css
        └── index.js
        └── 📁pages
            └── BlogsPage.js
            └── Contact.jsx
            └── CreatePost.js
            └── EditPost.js
            └── IndexPage.jsx
            └── LoginPage.js
            └── PostPage.js
            └── RegisterPage.js
        └── 📁partials
            └── Footer.js
            └── Layout.js
            └── NavBar.js
            └── Post.js
        └── 📁utils
            └── Editor.js
            └── UserContext.js
```

Server
```
└── 📁server
    └── .gitignore
    └── folder-structure2.md
    └── package.json
    └── package-lock.json
    └── index.js
    └── 📁models
        └── Contact.js
        └── Post.js
        └── User.js
```




## Getting Started

### Prerequisites

Before running the application, make sure you have the following installed:

- Node.js
- MongoDB or MongoDB Atlas account

### Installation

1. Clone the repository

```bash
git clone https://github.com/divyanshuthakur14/theWonderersPen.git
```
2. Go to the project directory and install dependencies for both the client and server

```bash
cd client
npm install
```

```bash
cd server
npm install
```

3. If wanna use for personal work - Create a `.env` file in both the `client` and `server` directories and add the environment variables like mongodb_uri , jwt_secret but that may require making render and netlify projects and deploy server and client folders respectively there. If wanna use as it is just skip to 4th step (meaning the mongodb, render and netlify links belonging to me will function).
4. Start the server

```bash
cd server
npm start
```

5. Start the client

```bash
cd client
npm start
```
6. Or the website can be visited here - https://verdant-entremet-80d954.netlify.app/

#### `.env` Variables

```bash
MONGO_URI=
JWT_SECRET=
PORT=
```
