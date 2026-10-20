# WhatsApp Stock Market Bot

A planned WhatsApp chatbot that acts as a personal finance assistant, using Python, Flask, Twilio and the MarketStack API.

> **Status:** work in progress. `main.py` is currently empty, so the bot doesn't run yet. The repo has the dependency list and a screenshot.

![Chatbot screenshot](Screenshot%20of%20chatbot.png)

## Planned design
- WhatsApp conversations through the Twilio WhatsApp API
- A Flask app that handles incoming messages, exposed locally over HTTPS with ngrok
- Stock data from [MarketStack](https://marketstack.com/), which covers 70+ exchanges

## Tech stack
Python, Flask 1.1, Twilio 6.50, requests (see `requirements.txt`).

## Setup
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
Keep your Twilio and MarketStack credentials in environment variables and never commit them.

## Credits
Based on the Udemy course [WhatsApp Stock Market Bot with Python, Twilio & MarketStack](https://www.udemy.com/course/whatsapp-stock-market-bot-with-python-twilio-marketstack/).
