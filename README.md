
# Stock Market APIs - India 🌟

**Fetch data from the Bombay Stock Exchange (BSE) and National Stock Exchange (NSE) in India.**
Access all the stock market data you need with simple APIs! 🚀

---

## ✨ Features

### National Stock Exchange (NSE) APIs:
- 📈 **Market Status**: Check if the market is open or closed.
  ```
  http://localhost:3000/get_market_status
  ```
- 📊 **Indices Data**: Get all NSE indices with changes, highs, lows, and order.
  ```
  http://localhost:3000/nse/get_indices
  ```
- 🏢 **Company Quotes**: Fetch quotation data for individual companies or multiple companies.
  ```
  http://localhost:3000/nse/get_quote_info?companyName=TCS
  http://localhost:3000/nse/get_multiple_quote_info?companyNames=TCS,WIPRO,AND_MORE
  ```
- 💹 **Top Gainers/Losers**: Retrieve the top 10 gainers or losers.
  ```
  http://localhost:3000/nse/get_gainers
  http://localhost:3000/nse/get_losers
  ```
- 📉 **52 Week High/Low**: Discover the stocks with 52-week highs or lows.
  ```
  http://localhost:3000/nse/get_52_week_high
  http://localhost:3000/nse/get_52_week_low
  ```

### Bombay Stock Exchange (BSE) APIs:
- 🏦 **Indices**: Access details of all indices in the BSE.
  ```
  http://localhost:3000/bse/get_indices
  ```
- 📄 **Company Info**: Get historical data, chart data, and day charts.
  ```
  http://localhost:3000/bse/get_company_info?companyKey=500112
  ```
- 🚀 **Top Gainers/Losers/Turnovers**: Fetch top-performing stocks or turnovers.
  ```
  http://localhost:3000/bse/get_gainers
  http://localhost:3000/bse/get_losers
  ```

---

## 📦 Installation

### 1️⃣ Locate your Application Directory
Identify where your app lives. For example: `/home/user/your_app`.

### 2️⃣ Install Node.js
Do yo ureally want me to tell you this ? Seriously ?

### 3️⃣ Install Express
Navigate to your app directory and run:
```bash
npm install express
```

### 4️⃣ Start the Server
Start the server with:
```bash
node app.js 3000
```
Now you can access the APIs at `http://localhost:3000`! 🎉

---

## 🚨 Important Notes
- API calls from browsers may fail due to 'OPTIONS' preflight requests or headers. I recommend making calls from your server.
- For best results, use these APIs within your application or backend services.

---

## 🛠 Tech Stack
- **Node.js**
- **Express.js**
- **REST APIs**

---

## 📩 Contact

| Name              | Details                             |
|-------------------|-------------------------------------|
| **👨‍💻 Developer**  | Sachin Arora                      |
| **📧 Email**       | [sachnaror@gmail.com](mailto:sachnaror@gmail.com) |
| **📍 Location**    | Noida, India                       |
| **📂 GitHub**      | [github.com/sachinarora](https://github.com/sachinarora) |
| **🌐 Website**     | [https://about.me/sachin-arora](https://about.me/sachin-arora) |
| **📱 Phone**       | [+91 9560330483](tel:+919560330483) |

---

## 🚀 Let’s Make the Stock Market More Fun & Accessible! 🤑
Ready to track your stocks like a pro? Install the package and start exploring! 🌟

---
_Last updated on January 10, 2025_
