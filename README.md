# Todo List Application

A full-stack todo list application built with React, Node.js, Express, and MongoDB.

## Features

- Create, read, update, and delete tasks
- Mark tasks as complete/incomplete
- Modern and responsive UI
- Real-time feedback with notifications
- Secure MongoDB Atlas integration

## Project Structure

```
todolist/
├── frontend/         # React frontend
├── backend/          # Node.js backend
└── README.md        # This file
```

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Update the `.env` file with your MongoDB connection string and other configurations

5. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Update the `.env` file with your backend API URL if different from default

5. Start the frontend development server:
   ```bash
   npm run dev
   ```

## Environment Variables

### Backend (.env)
- `MONGODB_URI`: Your MongoDB connection string
- `PORT`: Server port (default: 5000)
- `NODE_ENV`: Node environment (development/production)

### Frontend (.env)
- `VITE_API_URL`: Backend API URL (default: http://localhost:5000)

## Technologies Used

- **Frontend**:
  - React
  - Material-UI
  - Axios
  - Vite

- **Backend**:
  - Node.js
  - Express
  - MongoDB
  - Mongoose

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
