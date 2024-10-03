# Stock Tracker Using Flask

This project demonstrates a simple web application that uses Python, Flask, jQuery, and Bootstrap to display stock quotes and historical data. It pulls stock information from Yahoo Finance via the `yFinance` module and presents it in an interactive chart using Highcharts.

The web page allows users to view a stock's performance over the past 12 months, leveraging Flask's Jinja template system to create a responsive Bootstrap-based UI. The backend interacts with the Yahoo Finance API to fetch both real-time stock quotes and historical data.

## Features:
- Flask-based microservice for fetching and displaying stock data.
- Integration with Yahoo Finance for real-time quotes and historical performance.
- A clean, responsive user interface using Bootstrap 4.
- Visual representation of stock performance using Highcharts.

## Setup Instructions:
1. Clone the repository:
    ```
    git clone https://github.com/your-repo/Flask-Stock-Tracker
    ```

2. Navigate to the project directory:
    ```
    cd Flask-Stock-Tracker
    ```

3. Create and activate a virtual environment:
    ```
    virtualenv -p python3 venv
    source venv/bin/activate
    ```

4. Install dependencies:
    ```
    pip install flask yfinance lxml html5lib
    ```

5. Run the application:
    ```
    python app.py
    ```

6. Access the website at:
    ```
    http://127.0.0.1:5000/
    ```
