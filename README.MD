# Trading Bot

A Python-based trading bot for cryptocurrency futures trading on Binance.

## Environment Setup

Create a `.env` file in the root directory of this project with the following environment variables:

```env
# Mainnet API credentials (for live trading)
API_KEY_M=your_mainnet_api_key_here
SECRET_KEY_M=your_mainnet_secret_key_here

# Testnet API credentials (for testing)
API_KEY_T=your_testnet_api_key_here
SECRET_KEY_T=your_testnet_secret_key_here
```

## API Key Configuration

- **Mainnet**: Used for live trading on Binance Futures (`https://fapi.binance.com`)
- **Testnet**: Used for testing on Binance Testnet Futures (`https://testnet.binancefuture.com`)

## Security Notes

- Never commit your `.env` file to version control
- Keep your API keys secure and private
- Use testnet keys for development and testing
- Only use mainnet keys when you're ready for live trading

## Getting Started

1. Clone this repository
2. Create the `.env` file with your API credentials
3. Install required dependencies
4. Run the Jupyter notebook: `Trading_bot.ipynb`

## Dependencies

The bot requires the following Python packages:
- `python-binance` (for Binance API integration)
- `pandas` (for data manipulation)
- `numpy` (for numerical operations)
- `matplotlib` (for plotting)
- `jupyter` (for running the notebook)