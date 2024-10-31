# CS50 Finance - Stock Trading Web Application

## Description

This project is an implementation of the CS50 Finance problem set, creating a dynamic web application that allows users to simulate trading stocks. Users can register, log in, look up stock prices, buy and sell shares, and view transaction history. The app is built using Python and Flask for the backend, SQLite for the database, and HTML, CSS, and JavaScript for the frontend. The application pulls real-time stock data using the IEX Cloud API.

## Features

- **User Authentication**: Secure user registration and login with hashed passwords for safe storage.
- **Stock Lookup**: Allows users to check real-time stock prices using the IEX Cloud API.
- **Buying & Selling Stocks**: Users can buy shares with available balance or sell owned shares, updating their portfolio and account balance.
- **Portfolio Management**: Displays an overview of the user’s portfolio with information on stock holdings, cash balance, and total account value.
- **Transaction History**: Keeps a record of each trade made by the user, showing buy/sell actions with timestamps and prices.
- **Responsive Design**: Adapts for various screen sizes for an optimal user experience on desktops and mobile devices.

## Technologies Used

- **Python & Flask**: Backend server and routing
- **SQLite**: Database for storing user data, transactions, and account information
- **HTML, CSS, JavaScript**: Frontend structure and styling
- **Bootstrap**: UI framework for responsive design
- **Jinja2**: Template rendering within Flask
- **IEX Cloud API**: Real-time stock data retrieval for transactions and portfolio updates
