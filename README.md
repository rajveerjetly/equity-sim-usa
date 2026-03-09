# Equity-Sim USA | Global Market Strategy Engine

# Live Demo: 
https://rajveerjetly.github.io/equity-sim-usa/
# Project Overview
1. Equity-Sim USA is a high-performance market simulator focused on the US Equity markets (NYSE/NASDAQ). Following the success of the India-market prototype, this version was engineered to handle the unique dynamics of the US market—specifically its high liquidity and global volatility.

2. This project demonstrates the ability to scale a technical solution across different geographic data structures while maintaining a consistent User Experience (UX).

# Technical Stack
1. Frontend: HTML5, CSS3 (Optimized for data-heavy dashboards)
2. Logic: JavaScript (ES6+)
3. Data API: Yahoo Finance (Real-time US Market Feed)
4. Persistence: Browser LocalStorage API (Secure, client-side data retention)

# Key Features & Business Logic: 
1. USD Currency Logic: Integrated arithmetic handlers for USD-based transactions and portfolio valuation.
2. High-Volatility Tracking: Specifically tested against high-volume tech stocks (TSLA, NVDA, AAPL) to ensure the JavaScript engine could process rapid price fluctuations.
3. Persistent Strategy Testing: Utilizes LocalStorage to allow users to build a "Long-Term" US portfolio simulation that survives browser restarts.
4. Zero-Latency UI: Optimized the DOM manipulation logic to ensure that even with multiple US tickers updating simultaneously, the interface remains fluid.

# The "Global Scaling" Challenge
The Problem: Moving from the Indian market to the US market required handling different API endpoint structures and ensuring the UI could accommodate the longer character lengths of US tickers and larger dollar valuations.

The Solution: I refactored the JavaScript data-parsing logic to be modular. This means the core engine can now theoretically be adapted to any global market by simply changing the API parameters, demonstrating a "Scalable Product" mindset.

Future Roadmap
1. Cross-Market Analytics: A unified dashboard to compare India vs. US portfolio performance.
2. Stop-Loss Automation: Implementing logic-based triggers to automatically "sell" positions when they hit a certain threshold.
