# FinanceCalc: Mutual Fund Investment Calculator

**Duration:** Sep 2024 – Jan 2025  
**Company:** Associated with Goldman Sachs  
**Collaborators:** Mentors Kush and Aaron, plus a talented development team

FinanceCalc is a mutual fund investment calculator designed to estimate future returns based on stock beta calculations. The project combines a robust Spring Boot backend with a dynamic Next.js frontend to provide users with accurate and interactive investment projections.

## Features

* **Spring Boot Backend:** Built with Java & Maven, the backend handles data retrieval and calculations by connecting to external APIs and MongoDB.
* **User Input:** Users can input a mutual fund, investment amount, and time horizon to generate projections.
* **Financial APIs:** Real-time stock beta values and market return rates are fetched using the St. Louis Fed & Newton Analytics APIs.
* **Custom CAPM Calculation:** A dynamic Capital Asset Pricing Model (CAPM) adjusts return rates and applies compound interest to compute future value and annualized returns.
* **Next.js Frontend:** Interactive graphs and a trending mutual funds feature, with live data sourced from MongoDB.

## Tech Stack

* **Backend:** Java, Spring Boot, Maven, MongoDB
* **Frontend:** Next.js, React, Tailwind CSS
* **APIs:** St. Louis Fed, Newton Analytics

## How It Works

1. User selects a mutual fund and enters investment details.
2. Backend fetches real-time financial data and calculates projected returns using CAPM.
3. Frontend displays results in interactive graphs and highlights trending mutual funds.

## Demo

[Watch Demo on YouTube](https://www.youtube.com/watch?v=ufmDbWNErTE)

## Getting Started

### Frontend

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

### Backend

```bash
cd python-backend
python -m venv venv

# On macOS/Linux
source venv/bin/activate

# On Windows
venv\Scripts\activate

pip install -r requirements.txt
python app.py
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

---

*Built with ❤️ by the FinanceCalc team*