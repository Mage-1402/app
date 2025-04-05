# Frontend and Backend Connection Guide

The frontend and backend of this project are now connected. Here's how it works:

1. **Backend Server**
   - Running on port 3001 (configured in `backend/server.js`)
   - CORS is enabled to allow frontend requests
   - API routes are set up for `/api/products`, `/api/cart`, and `/api/auth`

2. **Frontend Configuration**
   - Using axios for API requests
   - API base URL configured in `frontend/src/config/api.js`
   - Environment variable `REACT_APP_API_URL` set in `.env` file

3. **How to Start the Application**
   1. Start the backend server:
      ```bash
      cd backend
      npm install
      npm start
      ```
   2. Start the frontend development server:
      ```bash
      cd frontend
      npm install
      npm start
      ```

4. **Testing the Connection**
   - The Products component will automatically fetch data from the backend
   - Check the browser console for any potential connection errors
   - The backend welcomes you at http://localhost:3001
   - The frontend runs at http://localhost:3000

5. **Verification**
   - Open the browser console
   - Navigate to the Products page
   - You should see products being fetched from the backend API