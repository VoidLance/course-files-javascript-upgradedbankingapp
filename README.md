# Upgraded Banking App

A small, browser-based banking app built with vanilla JavaScript, HTML, and CSS. It lets you create or sign in to sample accounts, view a balance, and record deposits and withdrawals in a transaction history.

> **Demo only:** Account data is kept in memory and is lost when the page is refreshed. This project does not connect to a bank and is not suitable for real financial information or transactions.

## Features

- Create an account with a holder name and optional starting balance.
- Sign in to one of the sample accounts or an account created during the current session.
- Make deposits and withdrawals, with withdrawals checked against the available balance.
- View account details and the current session's transaction history.
- Use a responsive interface that works on desktop and mobile screens.

## Getting started

### Requirements

A modern web browser. No package manager, dependencies, or build step are required.

### Run locally

1. Clone or download this repository.
2. From the project directory, start a local web server:

   ```sh
   python3 -m http.server 8000
   ```

3. Open [http://localhost:8000](http://localhost:8000) in your browser.

You can also open `index.html` directly in a browser.

### Try the app

- Sign in with a sample account number: `001`, `002`, `003`, `004`, or `005`.
- Or enter an account holder name and optional initial balance, then select **Create Account**.
- Enter an amount and choose **Deposit** or **Withdraw**, then select **Submit**.
- Select **Check Account Info** to view the account number and holder details, or **Logout** to return to the sign-in form.

## Project files

- [`index.html`](index.html) — app structure and forms.
- [`app.js`](app.js) — account model, sample data, and browser interactions.
- [`styles.css`](styles.css) — layout and responsive styling.

## Help

For questions or to report a problem, [open an issue](https://github.com/VoidLance/course-files-javascript-upgradedbankingapp/issues).

## Contributing and maintenance

The project is maintained by [VoidLance](https://github.com/VoidLance). Contributions are welcome: open an issue to discuss a change, then submit a pull request with a focused description of what it changes. There is no separate contribution guide in this repository.

## License

There is no `LICENSE` file in this repository, so the project's licensing terms are not specified.
