# Gourmet Recipe Application

A full-stack web application showcasing a collection of gourmet recipes built with Spring Boot for the backend and React + TypeScript for the frontend.

---

## Overview

This project allows users to explore a variety of gourmet dishes through a visually engaging interface. The homepage features a carousel displaying high-quality images of recipes, each linking to a detailed recipe page with ingredients and preparation steps.

---

## Features

* Recipe listing and detail pages
* Image carousel on the homepage
* Short descriptions for each featured recipe
* Favorites section for saved recipes
* Responsive and user-friendly UI
* Footer with links and social media icons

---

## Tech Stack

* **Frontend:** React, TypeScript, HTML, CSS
* **Backend:** Spring Boot 3.x
* **Database:** MySQL or PostgreSQL
* **Tools:** Node.js, Maven/Gradle, Axios, Git

---

## Setup Instructions

1. Clone the project repository:

   ```bash
   [git clone https://github.com/<username>/gourmet-recipe-app.git](https://github.com/CunninghamLi/gourmetrecipeapp.git)
   ```
2. Navigate to the backend folder and start the server:

   ```bash
   cd backend
   ./mvnw spring-boot:run
   ```
3. Open a new terminal and start the frontend:

   ```bash
   cd frontend
   npm install
   npm start
   ```
4. Access the app in your browser:

   ```
   http://localhost:3000
   ```

---

## How It Works

* The backend serves REST APIs for recipes and favorites.
* The frontend fetches data using Axios and displays it with React components.
* The homepage carousel showcases featured dishes.
* Clicking a dish opens its recipe details.
* Users can mark recipes as favorites for later viewing.

---

## Future Improvements

* Add authentication for user accounts
* Enable recipe uploads from users
* Integrate an external food API
* Add search and filter features by cuisine or difficulty

---

## License

Created for educational purposes — free to use and modify.
