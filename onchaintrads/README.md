# OnChainTrads — Demo Trading Milestone

This folder contains the first browser-based OnChainTrads prototype.

## Run it
- Open `index.html` in a browser, or publish the repository with GitHub Pages.
- If GitHub Pages publishes the repository root, the page path is:
  `https://dawitmengist263.github.io/cryptobigot2/onchaintrads/`
- No custom domain is needed.

## Current prototype
- Responsive dark trading dashboard
- Public Binance ticker and candlestick fetches where browser/network access permits
- Demo-only balances, basic paper buy/sell orders, order history
- Demo convert and wallet controls
- Level settings and browser-only interval lock
- Admin network display configuration stored only in page memory

## Important limitations
This is a UI prototype, not a production exchange. Balances are stored in JavaScript memory and reset on reload. The transfer page is explanatory only; there are no separate ledgers. Short positions, futures margin, liquidation, stop-loss/take-profit, real deposits, withdrawals, customer accounts, secure admin roles, persistent databases, and blockchain transactions are not implemented. The admin panel does not configure actual networks. Browser interval locks can be bypassed.

Never add exchange API secrets, seed phrases, private keys, or customer credentials to this static site or a public GitHub repository. Real-money features require a secure backend, persistent accounting ledger, rigorous testing, access controls, and legal/compliance review.
