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

```bash
# Start DB
cd infra
docker compose up -d

# Run API
cd api/budgetwise-js-api
npm install
node src/index.js

# Run Web
cd budgetwise-web
npm install
npm run dev
```

<img width="1713" height="662" alt="Screenshot 2026-04-09 162359" src="https://github.com/user-attachments/assets/55c96a50-2935-4dbd-b892-6fea0756b211" />

<img width="1542" height="693" alt="Screenshot 2026-04-09 162556" src="https://github.com/user-attachments/assets/f2133285-1172-4111-993a-48ad92609d10" />
<img width="1435" height="146" alt="Screenshot 2026-04-09 162751" src="https://github.com/user-attachments/assets/7505aa82-ad32-4f03-b08a-106fb1a97733" />
<img width="1486" height="567" alt="Screenshot 2026-04-09 163929" src="https://github.com/user-attachments/assets/7d2c0e68-2a32-4f9d-af55-744bdf7794c8" />

<img width="1333" height="509" alt="Screenshot 2026-04-09 162729" src="https://github.com/user-attachments/assets/47f8e8e1-d102-4d2b-bece-2184ca46af71" />

<img width="1412" height="273" alt="Screenshot 2026-04-09 162439" src="https://github.com/user-attachments/assets/1351327f-4339-4f7c-9a4f-ce89647e295c" />
<img width="1536" height="617" alt="Screenshot 2026-04-09 162421" src="https://github.com/user-attachments/assets/d3f87d80-9784-4d5d-bf38-6e1127d30f59" />




