# AI Expense Tracker

A full-stack expense tracking application with AI-powered insights, built using the PERN stack (PostgreSQL, Express, React, Node.js).

## 🔗 Live Demo

- **Frontend:** [https://ai-expense-tracker-4wsf.vercel.app/](https://ai-expense-tracker-4wsf.vercel.app/)



- **Backend API:** [https://aiexpense-tracker-production.up.railway.app/](https://aiexpense-tracker-production.up.railway.app/)

## ✨ Features

- User authentication (Register/Login) with JWT
- Add, view, update, and delete expenses
- AI-powered expense categorization/insights using Google Gemini API
- Responsive UI built with React
- RESTful API backend with PostgreSQL database

## 🛠️ Tech Stack

**Frontend:**
- React.js (Vite)
- Axios
- CSS

**Backend:**
- Node.js
- Express.js
- PostgreSQL
- JWT for authentication
- Google Gemini API (@google/genai) for AI features

**Deployment:**
- Frontend: Vercel
- Backend: Railway

## 📡 API Endpoints

| Method | Endpoint              | Description           |
|--------|-----------------------|------------------------|
| POST   | `/api/auth/register`  | Register a new user   |
| POST   | `/api/auth/login`     | Login existing user    |
| GET    | `/api/expenses`       | Get all expenses       |
| POST   | `/api/expenses`       | Add a new expense       |
| PUT    | `/api/expenses/:id`   | Update an expense       |
| DELETE | `/api/expenses/:id`   | Delete an expense       |

## ⚙️ Setup & Installation

### Backend

```bash
cd backend
npm install
```

Create a `.env` file in the `backend` folder:

```
PORT=8000
DATABASE_URL=your_postgresql_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
```

Run the server:

```bash
npm run dev
```

### Frontend

```bash
cd frontend
npm install
```

Create a `.env` file in the `frontend` folder:

```
VITE_API_URL=http://localhost:8000/api
```

Run the app:

```bash
npm run dev
```

## 📸 Screenshots

*(Add screenshots of your app here)*

## 🚀 Future Improvements

- Add expense analytics/charts
- Export expenses to CSV/PDF
- Multi-currency support

## 👤 Author

**Brahamjeet Anand**
GitHub: [@impulsiveblast](https://github.com/impulsiveblast)

---
