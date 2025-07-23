# Bitcoin Retirement Planner

A web-based calculator to help you plan your retirement using Bitcoin projections. Set your financial goals, simulate your future, and explore strategies to achieve your desired retirement lifestyle. Available in English and Portuguese.

## Features

- **Multi-language**: Switch between English and Portuguese.
- **Currency Support**: Calculate in BRL, USD, EUR, GBP, JPY, or AUD.
- **Personalized Inputs**:
  - Current age, retirement age, and life expectancy.
  - Desired monthly spending (with currency selection).
  - Current Bitcoin holdings and monthly investment.
- **Advanced Settings**:
  - Annual inflation rate (with historical IPCA data for BRL).
  - Annual Bitcoin growth rate (with historical BTC data).
- **Automatic Data Fetching**:
  - Real-time Bitcoin price (via CoinGecko).
  - Latest fiat exchange rates.
  - Historical inflation and Bitcoin growth rates.
- **Projection Results**:
  - Target capital needed for retirement.
  - Projected portfolio value at retirement.
  - Longevity of your reserve (how long your funds will last).
  - Gap analysis (surplus or shortfall).
  - Strategies to reach your goal (ideal monthly or single investment).
- **Responsive Design**: Mobile-friendly and visually appealing with Tailwind CSS.
- **Disclaimer**: Educational tool only; not investment advice.

## How It Works

1. **Enter your details**: Fill in your age, retirement target, desired monthly spending, current BTC, and monthly investment.
2. **Adjust assumptions**: Use advanced settings to set inflation and BTC growth rates, or select historical data.
3. **Calculate**: Click "Calculate" to see your retirement projection.
4. **Review results**: Analyze your goal, projection, reserve longevity, and strategies to close any gap.

## Technologies Used

- **HTML5 & JavaScript (ES6+)**
- **Tailwind CSS** for styling
- **CoinGecko API** for Bitcoin price
- **ExchangeRate-API** for fiat rates
- **IBGE API** for Brazilian inflation (IPCA)
- **CryptoCompare API** for historical BTC growth

## Getting Started

1. Clone or download this repository.
2. Open `index.html` in your web browser.
3. No build step or backend required.

## Disclaimer

This calculator is for educational and simulation purposes only. Results are based on projections and assumptions that may not materialize. Cryptocurrency markets are volatile and risky. This is not investment advice. Consult a financial professional.

## Author

Developed by [Aaron Lil](https://github.com/AaronLil)
