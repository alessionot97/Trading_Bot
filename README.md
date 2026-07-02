# Trading Bot XAUUSD

## Version 1.2

### Overview

Trading Bot XAUUSD is an algorithmic trading system written in Python
for MetaTrader 5. It is currently designed exclusively for **XAUUSD
(Gold)** and follows a conservative trading strategy focused on
consistency, risk management and modularity.

### Core Strategy

-   EMA 5 / 21 / 200 trend filtering
-   RSI confirmation
-   Pending BUY LIMIT / SELL LIMIT orders
-   Configurable number of Take Profit levels
-   Automatic Break-even after a configurable TP
-   Configurable Stop Loss
-   Centralized configuration through `config.json`

------------------------------------------------------------------------

# Project Goals

-   Prioritize capital preservation over aggressive growth.
-   Keep every trading parameter configurable.
-   Build a modular architecture that is easy to maintain and extend.
-   Continuously improve entry quality through real-world testing.

------------------------------------------------------------------------

# Project Structure

``` text
TradingBot/
│
├── trading_bot.py
├── dashboard.py
├── notifier.py
├── config.json
├── README.md
├── CHANGELOG.md
│
├── logs/
├── docs/
├── backups/
└── releases/
```

------------------------------------------------------------------------

# Main Features

## Trading Engine

-   XAUUSD only
-   M15 strategy
-   Configurable number of positions
-   Configurable Take Profit levels
-   Pending Orders
-   Automatic Break-even
-   Cooldown management
-   Spread filtering
-   Market status detection

## Dashboard

-   Live account information
-   Market status
-   Open positions
-   Pending orders
-   EMA / RSI monitoring
-   Live chart
-   Full configuration editor

## Telegram Notifications

-   Startup
-   Trading signals
-   Order execution
-   Position close
-   Stop Loss updates
-   Errors
-   Configurable anti-spam cooldown

## Risk Management

-   Market closed protection
-   Pending order expiration
-   Retry mechanism for SL updates
-   Configurable risk parameters

------------------------------------------------------------------------

# Current Release

## Version 1.2

Current stable release.

Highlights:

-   Parametric Take Profit management
-   Parametric Break-even
-   Candle-close based pending entries
-   Professional dashboard
-   Weekly trading logs
-   Modular notification system
-   Simplified configuration

------------------------------------------------------------------------

# Roadmap

## Version 2.0

Planned features:

-   Desktop application
-   Automatic installer
-   Integrated launcher
-   Advanced statistics
-   Equity curve
-   Built-in backtesting
-   Automatic update system
-   Multi-symbol support

------------------------------------------------------------------------

# License

Private project under active development.
Stay tuned for the pubblication!
