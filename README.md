

Movie App 

## Description

Project aims to create a Movie App.

## Problem Statement

- We are adding a new project to our portfolios. So you and your colleagues have started to work on the project.

## Project Skeleton

```
----Movie App (folder)
|
|----readme.md         
SOLUTION
├── public
│     └── index.html
├── src
|    ├── assets
|    |     └── icons
│    ├── auth
│    │     └── firebase.js
│    ├── components
│    │     ├── MovieCard.jsx
│    │     ├── Navbar.jsx
|    |     ├── Switch.jsx
|    |     └── VideoSection.jsx
│    ├── context
│    │     └── AuthContext.jsx
│    ├── pages
│    │     ├── Login.jsx
│    │     ├── Register.jsx
│    │     ├── Main.jsx
│    │     └── MovieDetail.jsx
|    |  
|    ├── helpers
|    |     └── ToastNotify.js
|    |
│    ├── router
│    │     ├── Router.jsx
|    |     └── PrivateRouter.jsx
│    ├── App.js
│    ├── App.css
│    ├── index.js
│    └── index.css
├── package.json
├── .env
└── yarn.lock
```

## Expected Outcome

![Project 008 Snapshot](movie-app.gif)

## Objective

Build a Movie App using ReactJS.

### At the end of the project, following topics are to be covered;

- HTML

- CSS

- JS

- ReactJS

### At the end of the project, students will be able to;

- improve coding skills within HTML & CSS & JS & ReactJS.

- use git commands (push, pull, commit, add etc.) and Github as Version Control System.

## Steps to Solution

- Step 1 : Create React App using `npx create-react-app movie-app`

- Step 2 : Signup `https://firebase.google.com/` and create new app in firebase.

- Step 3 : Use `https://firebase.google.com/docs/auth/web/start` and create `Authentication` operations.

- Step 4 : Signup `https://www.themoviedb.org/documentation/api` and get API key for getting data from `https://api.themoviedb.org/3/discover/movie?api_key=${API_KEY}`, for searching movies `https://api.themoviedb.org/3/search/movie?api_key=${API_KEY}&query=` and for movie details `https://api.themoviedb.org/3/movie/${id}?api_key=${API_KEY}`.

- Step 5: You can use css frameworks like Bootstrap, Semantic UI, Material UI.

- Step 6: Add project gif to your project and README.md file.

## Notes

- You can add additional functionalities to your app.

**<p align="center">&#9786; Happy Coding &#9997;</p>**
