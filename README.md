# Auto Token Initverse Transaction Bot

This bot automatically performs token transactions between addresses stored in the `.env` file. Transactions are carried out randomly with the number of tokens specified by the user and can use a proxy for privacy. If no proxy is available, the bot will still run without it.

## Main Features

- Supports the use of proxies for each private key.
- Performs transactions between addresses without sending to the sender's address.
- Uses multi-threading for efficiency.
- Provides an option to run without a proxy if `proxy.txt` is empty.

## Requirements

- Python 3.8 or higher.
- Required Python modules (see below).

## Installation

1. **Clone the repository** or **Copy the code** and save it in a Python file named `gnit.py`.

2. **Create Configuration Files**:

   - **Create a `.env` file** to store private keys. Example file contents:
     ```plaintext
     0xPRIVATEKEY1
     0xPRIVATEKEY2
     0xPRIVATEKEY3
     ```

   - **Create a `proxy.txt` file** to store a list of proxies (optional). Example file contents:
     ```plaintext
     http://username:password@proxy1:port
     http://username:password@proxy2:port
     ```

     If there are no proxies, leave this file empty.

3. **Install Required Python Modules**: Run the following command to install the necessary modules:
   ```bash
   pip install web3 python-dotenv rich requests
4. **Address Configuration File**: On the first run of the bot, an `address.txt` file will be automatically created containing the addresses generated from the private keys in the `.env` file. This file is used as the list of destination addresses for transactions.

## Running the Bot

1. **Run the Bot**: Use the following command to run the bot:
   ```bash
   python gnit.py

## Join Telegram Channel
[Telegram Channel](https://t.me/dasarpemulung)

## Tutorial Video

[Tutorial With Video](https://youtu.be/i-87X0Zu_d8?si=dRZYh7zsO_1Eklot)
