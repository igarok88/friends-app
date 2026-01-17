# Friends App 👥

A simple and user-friendly web application for viewing, searching, and filtering a list of users. This project was created for educational purposes to practice DOM manipulation, asynchronous requests, and data array handling using vanilla JavaScript.

🔗 **[View Live Demo on GitHub Pages](https://igarok88.github.io/friends-app/)**

## 📋 Description

The application loads a list of 5000 random users using the [Random User Generator API](https://randomuser.me/). Users can interact with the data through a sidebar settings panel: search for specific people, sort them by various criteria, and filter the results.

## ✨ Features

- **Data Fetching:** Asynchronous user loading from an external API.
  - _Fault Tolerance:_ If the external API is unavailable, the app offers to load a local database (`db.json`).
- **Search:** "Live" search by first and last name.
- **Sorting:**
  - Alphabetical (A-Z, Z-A).
  - By Age (Ascending and Descending).
- **Filtering:**
  - **By Age:** Implemented with a custom dual-range slider (Min/Max).
  - **By Gender:** Category filtering (All / Male / Female).
- **Pagination:** Splits the list into pages (20 cards per page) with navigation controls.
- **User Card:** Displays avatar, name, age, and clickable links for email, phone number, and geolocation (Google Maps).
- **Visualization:** Color coding of cards based on the user's gender.

## 🛠 Tech Stack

- **HTML5**
- **CSS3** (Flexbox, custom input styling, loading animation)
- **JavaScript (ES6+)**
  - `async/await` & `fetch` API
  - Array methods (`map`, `filter`, `sort`, `slice`)
  - DOM Manipulation

## 🚀 How to Run

1.  Clone the repository:
    ```bash
    git clone [https://github.com/igarok88/friends-app.git](https://github.com/igarok88/friends-app.git)
    ```
2.  Open the `index.html` file in any modern browser.

## 📂 Project Structure

- `index.html` — Page structure.
- `style.css` — Component styling.
- `script.js` — Application logic (data fetching, event handlers, rendering).
- `db.json` — Backup database (fallback).

---

_Created for educational purposes._
