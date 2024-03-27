## mernProjectEcommerce - E-Commerce Clone

This is a MERN stack e-commerce clone application, featuring both a user-friendly frontend and a robust backend for managing products, orders, users, and more.

**Technologies:**

* **Frontend:** React.js
* **Backend:** Node.js with Express
* **Database:** Likely MongoDB (based on the presence of `database.js` in the backend configuration)
* **State Management:** Redux

**Project Structure:**

The project is well-organized, separating the frontend (`frontend`) and backend (`backend`) codebases. Here's a high-level overview:

* **backend**
    * Contains server-side logic and API endpoints.
    * Includes folders for configuration (`config`), controllers (`controllers`), models (`models`), routes (`routes`), middleware (`middleware`), and utility functions (`utils`).
* **frontend**
    * Houses the React components and application logic.
    * Structured with folders for public assets (`public`), React components (`src`), constants (`constants`), reducers (`reducers`), and images (`images`).

**Getting Started**

1. **Prerequisites:** Ensure you have Node.js and npm (or yarn) installed.
2. **Clone the Repository:** Use `git clone https://github.com/RajaBabu15/eCommerceClone.git` to clone this repository.
3. **Install Dependencies:**
    * Navigate to the project directory.
    * Run `npm install` (or `yarn install`) in the project root to install frontend dependencies.
    * Navigate to the `backend` directory and run `npm install` (or `yarn install`) to install backend dependencies.
4. **Database Setup:** Configure your database connection details in the `backend/config/database.js` file.
5. **Run the Application:**
    * Start the backend server using `node backend/server.js` (or `npm start` if using a start script).
    * Typically, the backend server runs on port 5000 (adjust if necessary).
    * Start the frontend development server using `npm start` (or `yarn start`) in the `frontend` directory. This usually serves the frontend application on port 3000 (adjust if necessary).

**Additional Notes**

* The project utilizes Redux for state management.
* The frontend components are organized by feature areas like Admin, Cart, Home, etc.
* Refer to the code itself and any additional documentation within the project for further details.
