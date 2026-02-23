# Go Finance API

Go Finance API provides comprehensive financial market data powered by Google Finance. Access stock details, market trends, currency exchange rates, cryptocurrency insights, and financial indicators through a high-performance REST API.

Optimized with a robust caching layer, our API delivers fast response times and reliable uptime, making it the ideal solution for building financial applications and market analysis tools.

---

## 🚀 API Endpoints

| Endpoint           | Method | Description                                                |
| :----------------- | :----- | :--------------------------------------------------------- |
| `/trends`          | `GET`  | Get market trends (indexes, gainers, losers, crypto, etc.) |
| `/stock-info`      | `GET`  | Get detailed real-time data for a specific stock ticker    |
| `/crypto-info`     | `GET`  | Get detailed real-time data for a specific cryptocurrency  |
| `/currencies-info` | `GET`  | Get real-time exchange rates for currency pairs            |

---

## 🛠 Input Parameters

### 1. `/trends`
Retrieve curated market movements.
- **category** (required): The type of trend data to fetch.
  - *Values:* `indexes`, `most-active`, `gainers`, `losers`, `climate-leaders`, `cryptocurrencies`, `currencies`.

### 2. `/stock-info`
Fetch in-depth data for stocks across global exchanges.
- **ticker** (required): Stock symbol (e.g., `AAPL`, `BBRI`, `ASII`).
- **exchange** (required): Exchange code (e.g., `NASDAQ`, `IDX`, `NYSE`).

### 3. `/crypto-info`
Get real-time price and stats for digital assets.
- **ticker** (required): Crypto symbol paired with USD (e.g., `BTC-USD`, `ETH-USD`).

### 4. `/currencies-info`
Monitor forex market movements.
- **ticker** (required): Currency pair (e.g., `USD-IDR`, `EUR-USD`, `GBP-JPY`).

---

## API Advantages

- **Global Coverage** - Access stocks from multiple exchanges worldwide
- **Fast Response** - Optimized for low latency queries
- **Easy Integration** - Simple REST API with JSON responses
- **Comprehensive** - Stock quotes, trends, company info in one place
-  **Detailed Documentation** - Clear examples and error handling

---

## Error Handling

| Status Code | Description                      |
| ----------- | -------------------------------- |
| 200         | Success                          |
| 400         | Bad request - Invalid parameters |
| 500         | Server error                     |

---

## Use Cases

- 📊 Build dashboards
- 📈 Create portfolio tracking applications
- 💼 Financial analytics tools
- 📱 Mobile finance apps
- 📰 Financial news aggregators

---

## Issues / Bug Reports

For issues, bugs, or technical inquiries:
- 💬 **Slack:** Direct Message to **Code Storm**

---

## Data Source

Powered by Google Finance