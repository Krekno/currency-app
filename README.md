## 📊 Currency Portfolio Tracker

A Python desktop application that tracks your foreign currency assets based on Turkish Lira (TRY).  
The app fetches live exchange rates, logs daily data, and visualizes portfolio performance.

### ✨ Features
- Add and update currency assets
- Automatically logs daily exchange rates
- View historical currency data
- Fetches missing historical rates automatically
- Calculates profit/loss and percentage change
- Displays total portfolio value
- Wealth change graph using matplotlib
- Local data storage with SQLite

### 🛠️ Technologies Used
- Python
- Tkinter (GUI)
- SQLite
- Requests
- Matplotlib
- CurrencyLayer API

### 📦 Database Structure
- `myAssets` — user currency holdings  
- `log` — daily exchange rates

### ▶️ How to Run
```bash
pip install requests matplotlib
python app.py
```
### 🔑 API Key

Replace the placeholder:
```
api_key = "API_KEY"
```
with your own CurrencyLayer API key.
