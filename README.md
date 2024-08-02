# Dbank
A decentralized banking application built on the Internet Computer using Motoko and JavaScript. Features include balance top-up, withdrawals, and interest compounding based on seconds.

# DBank Application

## Overview

DBank is a decentralized banking application developed on the Internet Computer (IC) using Motoko and JavaScript. The application allows users to manage their virtual bank accounts with features for topping up balances, withdrawing funds, and earning interest.

## Features

- **Top-Up Balance**: Add funds to your account balance.
- **Withdraw Funds**: Withdraw funds from your account.
- **Compounding Interest**: Interest is compounded based on seconds, providing real-time growth of your balance.

## Technologies Used

- **Motoko**: Programming language used for writing smart contracts on the Internet Computer.
- **JavaScript**: Frontend and interaction logic for the application.
- **DFINITY**: The decentralized network that hosts the application.

## Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/dbank.git
   ```
   
2. **Install dependencies:**
   Navigate to the project directory and install any required dependencies.
   ```bash
   cd dbank
   npm install
   ```
   
4. **Configure the Application:**
   Set up your environment variables and configuration files as needed.
   Install DFINITY SDK:
   Follow the official installation guide if you haven’t installed dfx yet.
   Start the local Internet Computer network provided by dfx.
  ```bash
  dfx start
  ```
  Deploy the smart contracts and application to the local network. (On another terminal)
  ```bash
  dfx deploy
  ```

6. **Run the Application:**
   Start the development server or deploy the application to the Internet Computer. (On different terminal)
   ```bash
   npm start
   ```
   Open your web browser and navigate to the URL provided by npm start to interact with your application.

# Usage
**Top-Up Your Balance:**
Navigate to the top-up section and add funds to your account.

**Withdraw Funds:**
Use the withdrawal feature to remove funds from your balance.

**Compounding Interest:**
The application automatically compounds interest based on elapsed seconds.


