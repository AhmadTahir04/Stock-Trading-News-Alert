# Stock Trading Alerts

This Python project is designed to monitor stock market movements and alert users to significant price changes. It uses various financial data APIs to retrieve stock information, tracks price changes, and sends notifications for substantial movements.

## Features

- Monitors stock prices in real time.
- Identifies significant stock price changes.
- Notifies users about important market movements.

## Getting Started

### Dependencies

- Python 3.x
- Requests library
- Twilio API for notifications
- dotenv for environment variable management
- Access to financial data APIs


### Setting up the environment

- pip install requests python-dotenv


### Executing the Program

Run `main.py` to start:

```bash
python main.py
```

The program will automatically track stock prices, identify significant changes, and send notifications if notable movements are detected.

### Modules

- `stock_data_manager.py`: Manages stock data and updates.
- `stock_notification_manager.py`: Responsible for sending out notifications.
- `stock_search.py`: Searches for stock data using external APIs.

### Authors

Ahmad Tahir

### Acknowledgments

hanks to the creators of the financial data APIs used in this project.
