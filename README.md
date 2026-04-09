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

```bash<img width="553" h<img width="1412" height="273" alt="Screenshot 2026-04-09 162439" src="https://github.com/user-attachments/assets/22c434ca-4a69-4384-a768-e92b27941e2f" />
<img width="1536" height="617" alt="Screenshot 2026-04-09 162421" src="https://github.com/user-attachments/assets/29e859e1-26c5-4c49-b706-e34287cde90e" />
<img width="1652" height="909" alt="Screenshot 2026-04-09 162412" src="https://github.com/user-attachments/assets/b7bcbe39-9710-4b70-aeba-0ad5a4559f2e" />
<img width="1713" height="662" alt="Screenshot 2026-04-09 162359" src="https://github.com/user-attachments/assets/4b1ec4d9-14ec-46b8-beeb-8e189ece553c" />
eight="137" alt="Screenshot 2026-04-09 162808" src="https://github.com/user-attachments/assets/eb089d6b-d38e-419a-acaf-165f85022bff" />
<img width="1435" height="146" alt="Screenshot 2026-04-09 162751" src="https://github.com/user-attachments/assets/fa97a01c-0c95-4a7e-91a6-556cac38dd79" />
<img width="1333" height="509" alt="Screenshot 2026-04-09 162729" src="https://github.com/user-attachments/assets/143c2b8e-f6a3-4e26-b9b8-e6e304b3f1ae" />
<img width="1473" height="346" alt="Screenshot 2026-04-09 162646" src="https://github.com/user-attachments/assets/80049c8a-8846-43a8-bec7-e67aa5953800" />
<img width="1542" height="693" alt="Screenshot 2026-04-09 162556" src="https://github.com/user-attachments/assets/53278332-c19c-4bad-9292-44f65f844427" />

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
