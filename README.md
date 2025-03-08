Tool for flash tokens generation on Ethereum network

Tool is a standalone Windows application developed for educational purposes to streamline the process of sending flash token transactions (USDT, USDC, DAI) on the Ethereum blockchain. Built using Python, with tkinter for the graphical user interface and web3.py for blockchain interaction, the tool is compiled into a portable .exe file, eliminating the need for a Python environment or additional dependencies.

Key Features

Portable Executable: No installation or Python setup required—download and run the .exe directly.
Intuitive User Interface: A clean and straightforward GUI for entering wallet private keys, recipient addresses, and transaction details.

Supported Tokens: Facilitates sending USDT, USDC, and DAI with automatic decimal precision handling.

Transaction Management: Enables sending transactions and canceling pending ones by overriding with a higher gas price.

Real-Time Feedback: Displays wallet address, ETH balance, and transaction status updates.

Infura Integration: Connects to the Ethereum mainnet via a customizable Infura API key.

Safety Mechanisms: Validates Ethereum addresses and provides warnings for insufficient gas funds.

Prerequisites

A Windows operating system (tested on Windows 10 and 11).
An active Infura account with an API key for Ethereum mainnet access.
An Ethereum wallet containing a private key and sufficient ETH to cover gas fees.

Installation and Usage

Download the latest release (EthereumFlashTool.exe) from the Releases section.
Launch the .exe file on your Windows machine.
Enter your Infura API key, wallet private key, and transaction details into the provided fields.
Execute flash token transactions and monitor their status within the application.

Source Code

The source code is available for review and modification. Developers interested in exploring the implementation details or contributing to the project can access it in the repository.

Disclaimer

This tool is designed exclusively for educational and testing purposes. Users are responsible for ensuring adequate ETH for gas fees and using the application appropriately. The developer bears no liability for any financial losses resulting from misuse, errors, or external factors.

Contributions

Contributions are encouraged! Feel free to fork the repository, report issues, or propose enhancements. Suggestions to improve security, add new features, or optimize the executable are particularly welcome.
