# How to Run the Project

## Prerequisites
- Node.js installed on your machine
- npm (comes with Node.js)

## Setup Steps

### 1. Backend Setup
1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Initialize the database:
   ```bash
   npm run init-db
   ```

4. Start the backend server:
   ```bash
   npm run dev    # for development with auto-reload
   # or
   npm start     # for production
   ```

The backend server will start on the default port (typically 3000 or as specified in the environment variables).

### 2. Frontend Setup
1. Open a new terminal and navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the frontend development server:
   ```bash
   npm start
   ```

The React development server will start and should automatically open your default browser to the application (typically at http://localhost:3000).

## Technology Stack
- Backend:
  - Express.js
  - SQLite database
  - CORS enabled
  - nodemon for development
- Frontend:
  - React
  - React Router for navigation
  - Axios for API calls

## Notes
- The backend uses nodemon in development mode for automatic server reloading
- SQLite is used as the database, which is file-based and doesn't require a separate database server
- Make sure both backend and frontend servers are running simultaneously for the application to work properly