# The Real-Time Financial Assets Price Tracker
This is a versatile financial asset monitoring tool built with Python's web framework Flask, allowing the users to track prices of various assets, including stocks and cryptocurrencies, in real time.
## Installation
1. Clone the repository:
    ```
    git clone https://github.com/stanleytengg/PriceTracker.git
    cd PriceTracker
    ```
2. Create and activate virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate

   # For Window users, use this instead
   venv\Scripts\activate
   ```
3. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```
4. Run the application:
   ```
   python run.py
   ```
5. Open the web browser and navigate to `http://localhost:5000` (or the appropriate port if different)
## Features
- Add and monitor multiple financial assets at once
- Real-time price tracking using Yahoo Finance data
- User authentication and session management
- User-friendly interface
# How It Works
1. Data Fetching: The application uses the `yfinance` python library to fetch real-time price data from Yahoo Finance. I've created custom API endpoints within the Flask application to fetch the data.
2. Data Processing: Once the data is fetched, it's processed and prepared for display.
3. Frontend Display: The processed data is then sent from the backend to the frontend, displaying it to the user in a user-friendly format.
