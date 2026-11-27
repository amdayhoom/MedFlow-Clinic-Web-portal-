# MedFlow Clinic Web Portal 🏥

A modern, responsive web portal designed for clinic management. This project provides a clean user interface for patients and staff, featuring dashboards, user authentication, and data visualization.

## 🚀 Features

Based on the current file structure, the portal includes:
*   **User Authentication:** Dedicated login (`login.html`), registration (`register.html`), and password recovery (`forgot-password.html`) pages.
*   **Password Reset Flow:** A dedicated "Forgot Password" page that allows users to securely request a reset link and provides visual confirmation (success state) when the request is submitted.
*   **Dashboard:** A central hub (`dashboard3.js` / `index.html`) featuring data visualization using `Chart.js`.
*   **User Profiles:** A dedicated page for users to view and manage their information (`profile.html`).
*   **Data Lists:** Viewable lists for clinic data (e.g., appointments, patients) via `list.html`.
*   **Responsive Design:** Fully styled using Bootstrap (`bootstrap.bundle.min.js`) and custom CSS for mobile and desktop compatibility.
*   **Icons:** Integrated FontAwesome icons (`fa-solid-900.woff2`).

## 🛠️ Tech Stack

*   **HTML5:** Semantic structuring of web pages.
*   **CSS3:** Custom styling (`all.min.css`, `adminlite.min.css`).
*   **JavaScript (ES6):** Interactive elements and logic (`adminlite.min.js`, `dashboard3.js`).
*   **Libraries & Frameworks:**
    *   [Bootstrap](https://getbootstrap.com/) (Layout & UI components)
    *   [Chart.js](https://www.chartjs.org/) (Dashboard data visualization)
    *   [jQuery](https://jquery.com/) (DOM manipulation)
    *   [FontAwesome](https://fontawesome.com/) (Icons)

## 📁 Project Structure

```text
├── index.html            # Main landing page
├── login.html            # User login page
├── register.html         # User registration page
├── forgot-password.html  # Password reset request page
├── dashboard3.js         # Main dashboard logic and charts
├── profile.html          # User profile page
├── list.html             # Data listing page (e.g., appointments)
├── add.html              # Form to add new records
├── css/                  # (Implied) Stylesheets (adminlite, all.min)
├── js/                   # (Implied) Scripts (jquery, chart, adminlite)
└── README.md             # Project documentation
