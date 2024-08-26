# Stock Tracker Application

## Description
This Stock Tracker Application is a real-time web application designed to track stock prices. Using Node.js, Express, and Socket.IO for the backend, coupled with a React-based frontend, it allows users to view live stock data by entering stock symbols.

## Features
- Real-time stock price tracking.
- Easy-to-use interface to enter stock symbols.
- Live display of stock data fetched from the Alpha Vantage API.

## Installation

Download and install node.js on your device

### Setting Up the Backend

1. Clone the repository to your local machine.
2. Go to the `stock-tracker` directory.
3. Install the modules:
   ```bash
   npm install
4. Create a .env file in the root of the backend directory. Add the line:
  ALPHA_VANTAGE_API_KEY=Your_API_Key_Here

Replace Your_API_Key_Here with your Alpha Vantage API key. You can get one from Alpha Vantage.

### Setting Up the Frontend

1. Go to the stock-tracker-frontend directory.
2. Install the modules:
  npm install
3. To start the frontend, run:
  npm start

### Usage
To use the application, first start the backend:
  cd path/to/stock-tracker
  node server.js
Then, open a new terminal window and start the frontend:  
  cd path/to/stock-tracker-frontend
  npm start


