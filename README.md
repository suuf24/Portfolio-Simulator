# Portfolio Simulator

A flat-design web-based trading simulator that calculates net PnL, maker/taker fees, and portfolio balance growth with leverage simulation.

## Features

- **Initial Margin Setup**: Set your starting balance before trading
- **Flexible Sizing Modes**:
  - 100% Total Balance (All-in)
  - Custom Percentage Allocation
- **Leverage Trading**: Simulate trades with leverage up to 125x
- **Fee Calculation**: Automatic calculation of both taker (0.05%) and maker (0.02%) fees
- **Real-time PnL Tracking**: View gross PnL, net PnL after fees, and ROI per trade
- **Ledger History**: Complete trade history with balance progression
- **Performance Metrics**:
  - Net balance display
  - Total return (absolute and percentage)
  - Per-trade ROI

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- Google Fonts (Inter)

## Usage

1. **Set Initial Balance**: Click the `+` icon on the Net Balance card and enter your starting capital

2. **Configure Trade Parameters**:
   - Choose sizing mode (All-in or Custom %)
   - Set leverage (1-125x)
   - Enter expected price movement percentage

3. **Execute Order**: Click "Execute Order" to simulate the trade

4. **Monitor Results**:
   - View updated balance and total return
   - Check detailed trade information in the ledger table

## Fee Structure

| Fee Type | Rate |
|----------|------|
| Taker Fee | 0.05% |
| Maker Fee | 0.02% |

## License

© 2026 Portfolio Simulator

## Credits

Developed by [suuf24](https://github.com/suuf24)

## Live Demo

Access the simulator directly in any modern web browser - no installation required!
