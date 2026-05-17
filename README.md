# ⚡ NovaTerminal Pro Terminal v5.2

NovaTerminal is a high-performance, real-time cryptocurrency dashboard and portfolio tracker. Designed with a "terminal" aesthetic, it provides traders and investors with live market data, technical analysis tools, and portfolio management—all within a single-page, privacy-focused application.

## ✨ Key Features

* Real-Time Data: Live price streaming via Binance WebSockets for minimal latency.  
* Advanced Portfolio Tracking:  
  * Track holdings across multiple assets.  
  * Dynamic portfolio value charts (USD/AUD support).  
  * Import/Export portfolio data as JSON for backup and privacy.  
* Technical Analysis (TA): Toggleable TA overlays including Simple Moving Averages (SMA) and Relative Strength Index (RSI).  
* Market Intelligence:  
  * Fear & Greed Index: Real-time market sentiment integration.  
  * Market Dominance: Interactive charts showing BTC/ETH vs. Altcoin dominance.  
  * Volatility Alerts: Live feed for assets moving \>3% in short windows.  
* Interactive UI/UX:  
  * Ambient Glow: The background color shifts based on portfolio performance (Green for up, Red for down).  
  * Grid & List Views: Flexible layouts to suit your monitoring style.  
  * News Ticker: A live breaking news stream for the crypto space.  
  * Themes: Fully responsive Dark and Light modes.  
* PWA Ready: Includes a Service Worker for offline caching and improved loading speeds.

## ⌨️ Keyboard Shortcuts

NovaTerminal is built for power users. Control the dashboard without leaving your keyboard:

| Key | Action | Key | Action |
| :---- | :---- | :---- | :---- |
| ? | Show Help Modal | T | Toggle Dark/Light Theme |
| G | Switch to Grid View | L | Switch to List View |
| A | Toggle TA Overlays | R | Reconnect WebSocket |
| U | Set Currency to USD | M | Set Currency to AUD |
| E | Export Portfolio | I | Import Portfolio |
| 1-4 | Change Performance Timeframe (1h, 24h, 7d, 30d) | Esc | Close Modals |

## 🚀 Getting Started

As a client-side application, NovaTerminal requires no backend installation.

1. Clone the repository:  
2. BASH  
3. git clone https://github.com/your-username/novaterminal.git  
4. Open the project:  
   Simply open index.html in any modern web browser.  
5. Local Storage:  
   Your portfolio data and settings are saved locally in your browser. No data is ever sent to a private server.

## 🛠️ Built With

* Vanilla JavaScript (ES6+): Core logic and state management.  
* CSS3: Custom variables, glassmorphism effects, and animations.  
* [Chart.js](https://www.chartjs.org/): For all price, portfolio, and dominance visualizations.  
* Binance API: For real-time price streaming.  
* CoinGecko API: For market metadata and historical data.  
* Alternative.me API: For the Fear & Greed Index.

## 🤖 The Origin Story

NovaTerminal is a debut project created by a first-time developer with no prior coding experience. It serves as a case study in human-AI collaboration, having been built from concept to deployment using generative AI tools and Google Antigravity. This project demonstrates how modern software engineering can be democratized through the use of advanced AI assistance.

## 📄 License

This project is open-source. Feel free to fork, modify, and use it for your own purposes.

