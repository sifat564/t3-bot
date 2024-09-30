# t3rn-airdrop-bot

A bot designed to automate transactions and bridge assets on the t3rn network, making the process seamless and efficient.

## Features

- Automates asset bridging and swapping on the t3rn network.
- Supports multiple wallets through a JSON file containing private keys.
- Robust error handling with retry mechanisms to ensure all transactions are completed.
- User-friendly and easy to set up.

## Requirements

- Node.js (v14 or later)
- NPM (v6 or later)
- Private keys for the wallets you intend to use (stored in `privateKeys.json`).

## Installation

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/FEdanish/t3rn-bot.git
   cd t3rn-bot
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Create `privateKeys.json`**:
   Create a file named `privateKeys.json` in the root directory with the following format:

   ```json
   [
     "your_private_key_1",
     "your_private_key_2"
   ]
   ```

4. **Run the Bot**:
   Start the bot by running:

   ```bash
   node index.js
   ```

## Usage

- When the bot starts, it will prompt you to enter the number of transactions you wish to perform.
- The bot will then automatically execute the transactions, handling any errors and retrying as needed.
