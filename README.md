# BudgetWise

**BudgetWise** is a full-stack budget management app.  
Track your income and expenses, set monthly budgets, import bank statements, and view analytics with clean dashboards.

## Features
- User authentication (JWT)
- Manage categories (Income / Expense)
- Record transactions with notes
- Import transactions from Excel/CSV bank statements
- Define monthly budgets per category
- Dashboard with monthly summaries & category breakdowns
- View recent transactions and delete them
- Recurring transactions support
- AI-powered parsing and insights (OpenAI integration)
- Export monthly transactions to Excel
- Built with **Node.js + PostgreSQL + React (Vite, TypeScript, Tailwind)**

## Tech Stack
- **Backend**: Node.js (Express), Sequelize ORM, JWT Authentication
- **Database**: PostgreSQL (Docker)
- **Frontend**: React, Vite, TypeScript, Tailwind CSS
- **Infra**: Docker Compose, GitHub Actions (CI/CD)
- **AI**: OpenAI GPT (optional, for parsing and insights)

## Run locally


# Start DB
cd infra
docker compose up -d<img width="289" height="527" alt="Screenshot 2026-04-09 162815" src="https://github.com/user-attachments/assets/0228cb51-143f-4d4d-9753-418457a99f8f" />


# Run API
cd api/budgetwise-js-api
npm install
node src/index.js

# Run Web
cd budgetwise-web
npm install
npm run dev
