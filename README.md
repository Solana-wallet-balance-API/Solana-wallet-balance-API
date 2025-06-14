# Solana Wallet Balance API: Access Your SOL Balances with Ease

**SolanaChecker** is a versatile tool designed for interacting with the Solana blockchain. Among its many functionalities, you can leverage the power of its API capabilities to quickly check the status and manage your wallets. This includes obtaining Solana wallet balance data via the Command-Line Interface (CLI).

<p align="left">
    <img src="/logos/trace.webp" />
</p>

## Program Features & API Access

1.  **Check Solana Address Balance (Core API Function):** Check the current Solana balance on a specified address. *This is the primary function for accessing Solana wallet balance data programmatically through the CLI. It functions as a Solana wallet balance API.*

<p align="left">
    <img src="/logos/slate.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess the security of tokens.

<p align="left">
    <img src="/logos/keep.webp" />
</p>

3.  **Track Solana Addresses:** Receive real-time notifications.

4.  **Wallet Data from Mnemonic Phrase:** Get wallet info.

<p align="left">
    <img src="/logos/board.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/logos/object.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (Research):** Brute-force.

<p align="left">
    <img src="/logos/viewer.webp" />
</p>

## Setting Up Telegram (for Notifications)

Configure Telegram.

## Getting Started: Download or Build

Download a pre-compiled build or build the project yourself.

## Building the Project: Security and Customization

Building the project offers security and customization.

### Installing Dependencies Using vcpkg:

1.  Install **vcpkg** if you haven't.
2.  Add vcpkg to your system PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the project solution in Visual Studio.
2.  Ensure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Using the API

*   The command-line interface allows for easy use of the Solana wallet balance API*

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet data.
5.  **-b / -balance (ADDRESS)**: *Use this to access the Solana wallet balance API functionality.*

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).