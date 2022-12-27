# React Note Taking App

## About

Uses Bootstrap for styling and React Router for pathing to pages.

If creating from scratch, use `npm i react-bootstrap bootstrap react-router-dom`

To bring in Bootstrap and React Router, import them like so in any TSX files

```js
import 'bootstrap/dist/css/bootstrap.min.css';
import { Routes, Route, Navigate } from 'react-router-dom';
```

Uses **Local Storage** in the browser so if you visit this project on another browser all the notes will be gone since they depend on the original browser in which they were created.

Each note will be stored as JSON within the browser's local storage.

## Steps

1. clone the project from https://github.com/WebDevSimplified/react-note-taking-app

2. cd into the directory and type `npm i` to get the node modules

Side note: to start with the boilerplate (no need if just cloning the repo), type `npm create vite` and follow through the prompts (select react and then typescript)

3. that's it, since the repo is finished, just run `npm run dev` to get it going.
