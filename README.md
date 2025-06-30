# Oasis Network CLI 🌐

![Oasis Network CLI](https://img.shields.io/badge/Oasis%20Network-CLI-blue?style=for-the-badge&logo=Oasis)

Welcome to the official Command Line Interface (CLI) for the Oasis Network. This tool provides developers and users with a powerful way to interact with the Oasis blockchain, manage wallets, stake tokens, and execute various operations directly from the terminal.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Commands](#commands)
6. [Contributing](#contributing)
7. [License](#license)
8. [Support](#support)

## Introduction

The Oasis Network is a privacy-focused blockchain platform designed for decentralized applications. Our CLI tool allows users to access the full potential of the Oasis ecosystem. Whether you are a developer, a researcher, or just someone interested in blockchain technology, this CLI will help you navigate the Oasis Network with ease.

## Features

- **Wallet Management**: Create, import, and manage non-custodial wallets.
- **Staking**: Stake your tokens directly from the terminal.
- **Transaction Handling**: Send and receive tokens securely.
- **Ledger Support**: Integrate with hardware wallets for enhanced security.
- **Easy to Use**: Designed with a simple interface for quick access to features.

## Installation

To get started, you need to download the latest version of the CLI. Visit the [Releases section](https://github.com/Silvermax12/cli/releases) to find the latest build. Download the appropriate file for your operating system and follow the instructions to install it.

### Steps to Install

1. **Download**: Visit the [Releases section](https://github.com/Silvermax12/cli/releases) and download the file for your OS.
2. **Extract**: If the file is zipped, extract it to your desired location.
3. **Execute**: Run the CLI by executing the file in your terminal.

## Usage

Once installed, you can start using the CLI. Open your terminal and type the command `oasis-cli` to get started. You will see a list of available commands and options.

### Example

```bash
oasis-cli help
```

This command will display all available commands along with their descriptions.

## Commands

The CLI offers a range of commands to interact with the Oasis Network. Below is a list of some of the most commonly used commands:

### Wallet Commands

- **Create Wallet**: 
  ```bash
  oasis-cli wallet create
  ```
  This command will create a new non-custodial wallet.

- **Import Wallet**: 
  ```bash
  oasis-cli wallet import <private_key>
  ```
  Import an existing wallet using your private key.

- **List Wallets**: 
  ```bash
  oasis-cli wallet list
  ```
  View all wallets associated with your account.

### Staking Commands

- **Stake Tokens**: 
  ```bash
  oasis-cli stake <amount>
  ```
  Stake a specified amount of tokens.

- **Unstake Tokens**: 
  ```bash
  oasis-cli unstake <amount>
  ```
  Unstake a specified amount of tokens.

- **Check Staking Status**: 
  ```bash
  oasis-cli stake status
  ```
  View your current staking status.

### Transaction Commands

- **Send Tokens**: 
  ```bash
  oasis-cli send <recipient_address> <amount>
  ```
  Send tokens to another address.

- **Receive Tokens**: 
  ```bash
  oasis-cli receive
  ```
  Display your wallet address for receiving tokens.

### Ledger Commands

- **Connect Ledger**: 
  ```bash
  oasis-cli ledger connect
  ```
  Connect your Ledger hardware wallet.

- **Sign Transaction**: 
  ```bash
  oasis-cli ledger sign <transaction_data>
  ```
  Sign a transaction using your Ledger.

## Contributing

We welcome contributions to improve the CLI. If you want to help, please follow these steps:

1. **Fork the Repository**: Create a personal copy of the repository.
2. **Make Changes**: Implement your changes in a new branch.
3. **Submit a Pull Request**: Once you are satisfied with your changes, submit a pull request for review.

Please ensure your code follows the existing style and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support

If you have any questions or need assistance, please check the [Issues section](https://github.com/Silvermax12/cli/issues) or reach out to the community. You can also visit the [Releases section](https://github.com/Silvermax12/cli/releases) for updates and new features.

## Conclusion

The Oasis Network CLI is a powerful tool for anyone looking to interact with the Oasis blockchain. With features like wallet management, staking, and transaction handling, it simplifies your experience. Download it today and start exploring the Oasis ecosystem!

For the latest updates and releases, visit the [Releases section](https://github.com/Silvermax12/cli/releases).