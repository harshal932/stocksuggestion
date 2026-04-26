# CandyStock - AI-Powered Stock Analytics

A modern Next.js application built with Tailwind CSS, featuring real-time Indian and US stock market data, a dynamic watchlist, AI sentiment insights, and a mock portfolio builder.

## Features
*   **Real-time Stock Data:** Uses `yahoo-finance2` to fetch live NSE/BSE and global stock quotes.
*   **Live Market News:** Fetches the latest 5 news articles per stock ticker.
*   **Simulated Portfolio:** LocalStorage-based state management allows you to "buy" stocks and view your total portfolio value in ₹ on the Profile page.
*   **Candy Pop UI:** Stunning, responsive mobile-first UI with custom animations and variables.

## Steps to Run Locally

1. **Open your terminal** (Command Prompt or PowerShell).
2. **Navigate to the project folder:**
   ```bash
   cd D:\Projects\stock
   ```
3. **Install the required dependencies:**
   Make sure to install dependencies (this installs `next`, `react`, `tailwindcss`, and `yahoo-finance2`):
   ```bash
   npm install
   ```
4. **Start the development server:**
   ```bash
   npm run dev
   ```
5. **Open the App:**
   Once the server starts, open your web browser and go to:
   [http://localhost:3000](http://localhost:3000)

## Available Routes
*   `/` - Market Dashboard (Trending stocks, Top gainers/losers)
*   `/watchlist` - Search and view your saved stocks
*   `/insights` - AI Sentiment predictions and Market Pulse
*   `/login` - Mock login page to simulate user sessions
*   `/profile` - View your active session and total **Portfolio Value**
*   `/stock/[ticker]` - Dynamic real-time data page (e.g. `/stock/reliance` or `/stock/tsla`)
