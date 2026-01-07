
<p align="center">
  <img src="https://img.shields.io/badge/Frontend-React-blue?logo=react" />
  <img src="https://img.shields.io/badge/Backend-Django%20REST-success?logo=django" />
  <img src="https://img.shields.io/badge/API-RESTful-orange" />
  <img src="https://img.shields.io/badge/Deployment-PythonAnywhere-purple" />
</p>

<h1 align="center">
🚀 Fullstack CRUD App <br/>
React + Django REST Framework
</h1>

<p align="center">
End-to-end CRUD application showcasing real-world React ↔ Django REST API integration.
</p>


<div align="center">
  <h3>
    <a href="https://umit8098.github.io/React-Project-Tutorial-FullStack/">
      🖥️ Live Demo
    </a>
     | 
    <a href="https://github.com/Umit8098/React-Project-Tutorial-FullStack.git">
      📂 Repository
    </a>
  </h3>
</div>

![tutorial gif](tutorial.gif)

## Navigation

- [Overview](#overview)
- [Description](#description)
- [Features](#features)
- [API](#api)
- [Application Architecture](#application-architecture)
- [Project Skeleton](#project-skeleton)
- [Built With](#built-with)
- [How To Use](#how-to-use)
- [About This Project](#about-this-project)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)


## Overview

A fullstack CRUD application that demonstrates how a React frontend
communicates with a Django REST Framework backend via a RESTful API.

The application allows users to create, update, delete, and list tutorials
with real-time UI updates, showcasing end-to-end data flow from frontend to backend.

**Tech Stack:** React + Axios (Frontend) · Django REST Framework (Backend)  
**Backend Hosting:** PythonAnywhere


## Description

This project is a basic CRUD application where users can manage tutorials.  
It demonstrates how to integrate React with a REST API using `axios` for data fetching and modification.  
The backend is hosted on [PythonAnywhere](https://www.pythonanywhere.com/).  


## Features
- 📌 Fetch tutorials from REST API
- ➕ Create new tutorials via POST requests
- ✏️ Update existing tutorials using PUT requests
- ❌ Delete tutorials with DELETE requests
- 🔄 Real-time UI updates without page reload
- 🖼️ Modal-based edit form for better UX
  

## API

The project communicates with a REST API hosted on **PythonAnywhere**.
**Base URL:**

The backend is built with **Django REST Framework** and exposes a RESTful API
consumed by the React frontend using Axios.

```bash
https://umit8101.pythonanywhere.com/todo/
```

**Endpoints:**

* `GET /todo/` → Fetch all tutorials
* `POST /todo/` → Create a new tutorial
* `PUT /todo/:id/` → Update a tutorial
* `DELETE /todo/:id/` → Delete a tutorial


## Application Architecture

- React handles the user interface and state management
- Axios is used for HTTP communication
- Django REST Framework provides the RESTful API
- PythonAnywhere hosts the backend service

**Data Flow:**
React UI → Axios → Django REST API → Database → Response → UI Update


## Project Skeleton

```
Full Stack - Tutorial App
|
|----readme.md   
SOLUTION
├── public
│     └── index.html
│  
├── src
│    ├── components
│    │       ├── AddTutorial.jsx
│    │       ├── EditTutorial.jsx
│    │       └── TutorialList.jsx 
│    │            
│    ├── pages
│    │       └── Home.jsx
│    │
│    ├── App.js
│    ├── App.scss
│    ├── index.js
│    └── index.css
├── package.json
└── yarn.lock
```


## Built With

* [React](https://react.dev/)
* [Axios](https://axios-http.com/)
* [Bootstrap 5](https://getbootstrap.com/)
* [React Icons](https://react-icons.github.io/react-icons/)
* [Django REST Framework (API)](https://www.django-rest-framework.org/)



## How To Use

To clone and run this application, you'll need [Git](https://git-scm.com/), [Node.js](https://nodejs.org/), and a package manager (`yarn` or `npm`) installed on your computer.

```bash
# Clone this repository
$ git clone https://github.com/Umit8098/React-Project-Tutorial-FullStack.git

# Navigate into the project folder
$ cd React-Project-Tutorial-FullStack

# Install dependencies
$ yarn  
$ yarn start

# or using npm
$ npm install
$ npm start
```


## About This Project

This project focuses on demonstrating a complete frontend-to-backend workflow
using modern React practices and a RESTful backend built with Django.

It highlights API integration, state updates, and clean component structure
in a real-world fullstack scenario.


## Acknowledgements
- [Clarusway](https://clarusway.com/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [Bootstrap](https://getbootstrap.com/)


## Contact

<!-- - Website [your-website.com](https://{your-web-site-link}) -->
- GitHub [@Umit8098](https://github.com/Umit8098)

- Linkedin [@umit-arat](https://linkedin.com/in/umit-arat/)
<!-- - Twitter [@your-twitter](https://{twitter.com/your-username}) -->
