
# SalesFlow

## Description

**SalesFlow** is a full-stack application built to manage products and sales in a clean and structured way.

The project focuses on practicing real-world backend and frontend concepts, including **RESTful APIs, authentication, database modeling**, and **frontend API consumption**, following patterns commonly used in professional software development.

## Tech Stack

### Backend
- Node.js
- Express
- MongoDB
- Mongoose
- JWT (Authentication)
- dotenv

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Axios

## Project Structure

### Backend (/backend)

```text
  src/
   ├─ config/        # Database and environment configurations
   ├─ controllers/   # Request handling and business logic
   ├─ models/        # Database schemas (Mongoose)
   ├─ routes/        # API routes
   ├─ middlewares/   # Auth and validation middlewares
   ├─ services/      # Business rules and reusable logic
   └─ app.js         # Express app setup
```

### Frontend (/frontend)

```text
  src/
   ├─ components/    # Reusable UI components
   ├─ pages/         # Application pages
   ├─ services/      # API communication (Axios)
   ├─ hooks/         # Custom React hooks
   ├─ styles/        # Global styles
   └─ main.tsx       # App entry point
```

## Setup & Installation

### Prerequisites

- Node.js (v18+ recommended)
- MongoDB running locally or MongoDB Atlas
- Git

Clone the repository:

```bash
git clone https://github.com/your-username/salesflow.git
cd salesflow
```

## Environment Variables

Create a `.env` file inside the `backend` folder:

```env
PORT=3333
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Running the Project

> Make sure the backend server is running before starting the frontend.

### Backend

1. Navigate to the backend directory:

```bash
cd backend 
```

2. Install dependencies

```bash
npm install
```
3. Start the development server:

```bash
npm run dev
```

### Frontend

1. Navigate to the frontend directory:

```bash
cd frontend
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

## Application URLs

Once the application is running, you can access it at:

- **Backend API:** http://localhost:3333
- **Frontend App:** http://localhost:5173


## API / Features

### Main Features

- Product CRUD (Create, Read, Update, Delete)
- Stock management
- Sales registration
- JWT authentication
- Protected routes

## Future Improvements

- User roles (admin / seller)
- Sales reports dashboard
- Pagination and filters
- Unit and integration tests
- Docker setup
- Deployment (Render / Railway / Vercel)

## Author

**Pedro Monteiro**
Fullstack Developer

- GitHub: https://github.com/your-username
- LinkedIn: https://linkedin.com/in/your-profile
