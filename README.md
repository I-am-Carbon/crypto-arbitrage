# 🔁 Crypto Arbitrage Tracker

A Real-Time Cryptocurrency Arbitrage Tracker built with FastAPI that fetches live prices from Coinbase, Kraken, and Binance, and calculates the best arbitrage opportunities based on price differences across exchanges.

This project focuses on arbitrage detection and analysis, not automated trading.

---

## 🚀 Overview

The Crypto Arbitrage Tracker continuously collects cryptocurrency price data from three major exchanges — Coinbase, Kraken, and Binance. It compares prices in real time and determines the most profitable arbitrage opportunities by evaluating cross-exchange spreads.

This project demonstrates real-time financial data handling, cross-exchange price comparison, and FastAPI-based backend development.

---

## ✨ Features

- Live crypto price fetching from Coinbase, Kraken, and Binance  
- Cross-exchange price comparison  
- Best arbitrage opportunity calculation  
- Near real-time updates  
- Simple UI to visualize arbitrage spreads  
- SQLite database for storing price and opportunity data  

---

## 🛠 Tech Stack

**Backend**
- FastAPI (Python)
- REST APIs / WebSockets
- SQLite
- Uvicorn

**Frontend**
- Next.js
- TypeScript
- React
- Tailwind CSS

---

## 📂 Project Structure
```
  crypto-arbitrage/
  ├── app/ # FastAPI backend
  ├── frontend/ # Next.js frontend
  ├── crypto_arb.db # SQLite database
  ├── requirements.txt # Python dependencies
  └── package.json # Frontend dependencies

---
```
## 🚀 Getting Started

### Backend
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload

```

### Frontend
```
cd frontend
npm install
npm run dev
```


### Access URL
```
Backend runs on http://localhost:8000
Frontend runs on http://localhost:3000

```

### 👤 Author
```
Pranav Aithal
```
