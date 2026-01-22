# 🌍 WorldWise (part of the course)

**WorldWise** is a React application for saving and tracking cities that a user has visited.
The application presents visited locations on an interactive map and organizes them into city and country lists.

This project was created as part of a course and also serves as a **portfolio project**.
The main focus of the application is **application logic, routing, global state management, and defensive thinking**, rather than advanced UI design.

---

## 📦 Technologies

* `React`
* `JavaScript`
* `React Router`
* `Context API`
* `CSS Modules`
* `Custom Hooks`
* `Leaflet`
* `Geolocation API`
* `json-server`
* `Vite`

---

## 🦄 Features

Here’s what you can do with **WorldWise**:

* **User Login**
  The user can log in to access the main application.

* **Visited Cities List**
  The user can view a list of cities they have visited.

* **Visited Countries List**
  Cities are grouped by country, allowing the user to view visited countries.

* **Interactive Map**
  Visited cities are displayed on a world map.

* **Geolocation Support**
  The user can use their current location to interact with the map.

---

## 🧭 Application Flow

The application follows a clear and predictable flow:

1. **Start Page**
   When entering the application, the user sees the homepage.

2. **Login**
   After logging in, the user is redirected to the main application.

3. **Main Application (`/app`)**
   The user sees:

   * a sidebar with cities and countries
   * an interactive map

---

## 🛣️ Routing Structure

The application uses **React Router** with protected and nested routes:

* `/` – Homepage
* `/login` – Login page
* `/app` – Protected application layout

  * `/app/cities` – List of visited cities
  * `/app/cities/:id` – Single city view
  * `/app/countries` – List of visited countries

Access to `/app` is restricted using a protected route mechanism.

---

## 🧠 What I Learned

Working on this project helped me strengthen my understanding of React application architecture and logic.

* **React Router**
  Implementing nested routes and protected routes to control access to the application.

* **Context API**
  Managing global state for cities data and authentication across the entire app.

* **CSS Modules**
  Structuring component-level styles to avoid global CSS conflicts.

* **Custom Hooks**
  Extracting reusable logic into custom hooks to improve readability and separation of concerns.

* **Improving useEffect Skills**
  Better handling of dependencies, side effects, and avoiding unnecessary re-renders.

* **useReducer**
  Using reducers to manage more complex state logic in a predictable way.

* **Defensive Application Logic**
  Thinking about possible edge cases and user behavior, such as:

  * preventing access without authentication
  * controlling application flow
  * ensuring the user cannot move into invalid states

---

## 💭 Possible Improvements

* Better mobile responsiveness
* UI animations and transitions
* Dark mode support

---

## 🚦 Running the Project

To run the project locally:

1. Clone the repository
2. Install dependencies:

```bash
npm install
```

3. Start the fake API server:

```bash
npm run server
```

4. Start the development server:

```bash
npm run dev
```

5. Open your browser

---

## 🎥 Video

https://github.com/user-attachments/assets/e474c0bd-c32a-4600-bfa3-c6fe72862fa3

---
