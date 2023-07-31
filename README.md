📝 Description:

This Python project showcases a trade bot for EUR/USD using a simple candlestick-based strategy. The bot leverages the OANDA API to execute trades with take-profit and stop-loss levels.

📊 Strategy:

The trade bot analyzes recent candlestick patterns and generates buy/sell signals based on the following conditions:

Bullish Pattern: When a green candle follows a red candle with higher highs and higher lows.
Bearish Pattern: When a red candle follows a green candle with lower highs and lower lows.
💡 Disclaimer:

⚠️ Trading in financial markets involves risks and uncertainties. The trade bot's performance in a simulated environment does not guarantee similar outcomes in real-world scenarios. This project is for educational purposes only and should not be considered financial advice. Always consult with a qualified financial advisor before making any investment decisions.

🚀 Getting Started:

Install required Python packages using pip install -r requirements.txt.
Obtain an OANDA API access token and replace YOUR_ACCESS_TOKEN and YOUR_ACCOUNT_ID in the code.
Run the bot using python trade_bot.py and watch it in action!
📊 Results:

The bot's performance can be monitored through the console output and the generated dataF DataFrame. However, always remember to validate the strategy with extensive testing before using it for real trading.

🔒 License:

This project is licensed under the MIT License - see the LICENSE file for details.

📚 Resources:

OANDA API: https://developer.oanda.com/
Candlestick Patterns: https://www.investopedia.com/trading/candlestick-charting-what-is-it/
📧 Contact:

Feel free to reach out with any questions or suggestions via email: dave38@purdue.edu

🌟 Enjoy Trading! 🌟
