# Stock Tracker Application

## Description
Thia Stock Tracker Application is a real-time web application designed to track stock prices. Using Node.js, Express, and Socket.IO for the backend, coupled with a React-based frontend, it allows users to view live stock data by entering stock symbols.

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


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
