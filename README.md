
Built by https://www.blackbox.ai

---

```markdown
# bitBalance | Bitcoin UTXO Explorer

## Project Overview

bitBalance is a web-based application designed to explore Bitcoin Testnet UTXOs (Unspent Transaction Outputs) in real-time. Built using modern web technologies, it provides users an interactive interface to input Bitcoin testnet addresses and retrieve their balances and UTXO details.

## Installation

To run the project locally, follow these steps:

1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:
   ```bash
   cd bitBalance
   ```

3. Open the `index.html` file in your web browser.

No installation of additional dependencies is necessary, as all required libraries are included via CDN in the HTML file.

## Usage

1. Open `index.html` in your web browser.
2. Enter a Bitcoin testnet address in the input field (for example, `tb1q...`).
3. Click the "Scan UTXOs" button.
4. The application will fetch the UTXO information from the Bitcoin Testnet and display your balance and UTXO details. If no UTXOs are found or an error occurs, an appropriate message will be displayed.

## Features

- **Real-Time UTXO Exploration**: Enter a Bitcoin Testnet address and get instant UTXO details.
- **User-Friendly Interface**: Designed with a clean and simple layout for ease of use.
- **Visual Feedback**: Includes visual indicators such as loading spinners and error messages for better user experience.
- **Clipboard Copy Functionality**: Easily copy the address to the clipboard with a click.

## Dependencies

This project relies on the following external libraries:

- **Tailwind CSS**: For styling and layout.
- **Font Awesome**: For icons.

Both are included from CDN links in the `index.html` file.

## Project Structure

```
/bitBalance
└── index.html                  # Main HTML file
```

The project consists of a single HTML file, which contains the entire application logic, styling, and structure.

## Credits

Developed by **Yankho Ngolleka**. The application leverages the Mempool.Space API to fetch blockchain data.

## License

This project is open-source and free to use. Please respect the original authors and their licenses when using the code.
```