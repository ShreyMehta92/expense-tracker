# Expense Tracker

A full-stack expense tracking application built with React, Express, and MongoDB.

## Features

- Add, view, and delete expenses
- Track expenses by category
- View total expenses
- Modern Material-UI interface

## Tech Stack

- Frontend: React, Material-UI
- Backend: Node.js, Express
- Database: MongoDB

## Quick Start

1. Install dependencies:
```bash
npm install
cd client && npm install
```

2. Create `.env` file:
```
PORT=5000
MONGODB_URI=mongodb://127.0.0.1:27017/expense-tracker
```

3. Start the application:
```bash
npm run dev        # Backend
cd client && npm start  # Frontend
```

## MongoDB Setup

1. Install MongoDB Community Server
2. Start MongoDB service
3. Application will connect to `mongodb://127.0.0.1:27017/expense-tracker`

## API Endpoints

- GET `/api/expenses` - List all expenses
- POST `/api/expenses` - Add new expense
- DELETE `/api/expenses/:id` - Remove expense 