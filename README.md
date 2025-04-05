# How to Run the Project Locally

## Prerequisites
- Node.js installed on your machine
- npm (Node Package Manager)

## Setup Steps

1. First, navigate to the backend directory:
```bash
cd backend
```

2. Install the project dependencies:
```bash
npm install
```

This will install all required dependencies including:
- Express.js
- MongoDB
- Other dependencies listed in package.json

3. Start the development server:

For production mode:
```bash
npm start
```

For development mode with auto-reload:
```bash
npm run dev
```

The server will start on localhost. Check the console output for the exact port number (typically http://localhost:3000 or similar).

## Notes
- The project uses SQLite for database (as seen in config/sqlite.js)
- Make sure all dependencies are properly installed before running the server
- In development mode (npm run dev), the server will automatically restart when you make code changes