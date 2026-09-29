# Upgraded Banking App

A small, browser-based banking app built with HTML, CSS, and vanilla JavaScript. Use it to explore basic account creation, login, balances, deposits, withdrawals, and transaction history.

> **Demo only:** This project is an educational example, not a real banking service. Account data exists only in the current page session and is not secure or persistent. Do not enter real personal or financial information.

## Features

- Log in to sample accounts or create a new account.
- View an account balance and transaction history.
- Deposit money and withdraw available funds.
- See account details, including the generated account number.
- Responsive interface that works on desktop and mobile.

## Getting Started

### Requirements

A modern web browser. No package installation or build step is required.

### Run the app

Clone or download this repository, then open `index.html` in your browser. Alternatively, serve the project directory with any static file server and visit its local URL.

### Try a sample account

Enter one of these account numbers in the login form:

| Account number | Account holder | Starting balance |
| --- | --- | ---: |
| `001` | Alice | $500 |
| `002` | Bob | $300 |
| `003` | Charlie | $700 |
| `004` | Negative Balance | -$500 |
| `005` | Richie Rich | $1,000,000 |

To create an account, enter an account holder name and optionally an initial balance, then select **Create Account**. After logging in, use the transaction form to deposit or withdraw funds. Select **Check Account Info** to see the account number for a newly created account.

Accounts and transactions are stored in browser memory only; refreshing or closing the page resets them.

## Project Files

- `index.html` — page structure and forms
- `styles.css` — responsive app styling
- `app.js` — account logic and browser interactions

## Help

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-javascript-upgradedbankingapp/issues).

## Maintainers and Contributions

This project is maintained by [VoidLance](https://github.com/VoidLance). Contributions are welcome: open an issue to discuss a change, then submit a pull request with a clear summary and steps to verify it in a browser.
