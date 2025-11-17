📊 Currency Portfolio Tracker (TRY-Based)

This project is a desktop application written in Python (Tkinter + SQLite) that allows you to track your foreign currency assets based on Turkish Lira (TRY).
It fetches live exchange rates from CurrencyLayer API, stores your assets locally, and visualizes historical performance.

✨ Features

Add & update currency assets
Track how much of each currency you own and its value in TRY.

Automatic daily exchange rate logging
Saves daily live rates into a local SQLite database.

Historical data viewer
Fetches missing historical exchange rates and displays change over time with matplotlib.

Portfolio profit/loss calculation
Calculates:

Total portfolio value

Profit/Loss

Percentage change

Wealth change graph
Shows the growth of your total wealth over time.

🛠️ Technologies Used

Python

Tkinter (GUI)

SQLite

Requests (API calls)

Matplotlib

CurrencyLayer API

📦 Database

The app automatically creates two tables:

myAssets — your currency holdings

log — historical exchange rates

▶️ How to Run
pip install requests matplotlib
python app.py

🔑 API Key Required

You must replace:

api_key = "API_KEY"


with your own CurrencyLayer API key.
