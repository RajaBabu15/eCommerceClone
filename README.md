# MERN Shop - E-Commerce Clone

Welcome to the MERN Shop, an e-commerce application built with the MERN stack. This project features a user-friendly frontend and a powerful backend to manage products, orders, users, and more.

## Technologies Used

- **Frontend:** React.js
- **Backend:** Node.js with Express
- **Database:** Likely MongoDB (as suggested by the presence of `database.js` in the backend configuration)
- **State Management:** Redux

## Project Structure

The codebase is neatly divided into frontend and backend segments. Here’s a brief overview:

### Backend

- **Purpose:** Manages server-side logic and API endpoints.
- **Structure:** 
  - Configuration files (`config`)
  - Controllers (`controllers`)
  - Models (`models`)
  - Routes (`routes`)
  - Middleware (`middleware`)
  - Utility functions (`utils`)

### Frontend

- **Purpose:** Contains the React components and application logic.
- **Structure:** 
  - Public assets (`public`)
  - React components (`src`)
  - Constants (`constants`)
  - Reducers (`reducers`)
  - Images (`images`)

## Getting Started

Follow these steps to set up the project on your local machine:

1. **Prerequisites:** Ensure that Node.js and npm (or yarn) are installed on your system.
2. **Clone the Repository:** 
   ```bash
   git clone https://github.com/RajaBabu15/eCommerceClone.git
   ```
3. **Install Dependencies:**
   - Navigate to the project root directory and run:
     ```bash
     npm install
     ```
     (or `yarn install`) to install frontend dependencies.
   - Then, navigate to the `backend` directory and run:
     ```bash
     npm install
     ```
     (or `yarn install`) to install backend dependencies.
4. **Database Configuration:** Update the database connection details in `backend/config/database.js`.
5. **Running the Application:**
   - Start the backend server with:
     ```bash
     node backend/server.js
     ```
     (or `npm start` if using a start script). The server typically runs on port 5000.
   - Start the frontend development server by navigating to the `frontend` directory and running:
     ```bash
     npm start
     ```
     (or `yarn start`). The frontend application usually runs on port 3000.

## Additional Information

- **State Management:** Redux is used for managing the state.
- **Component Organization:** The frontend components are organized by feature areas such as Admin, Cart, Home, etc.
- **Further Details:** For more information, refer to the codebase and any additional documentation within the project.

Enjoy building and extending the MERN Shop!
