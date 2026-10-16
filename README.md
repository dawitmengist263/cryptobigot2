# CryptoBigot2 — Demo Exchange

CryptoBigot2 is a mobile-friendly, browser-based cryptocurrency exchange interface for learning and demonstration.

## Open the website

- Live GitHub Pages site: https://dawitmengist263.github.io/cryptobigot2/
- Main dashboard: https://dawitmengist263.github.io/cryptobigot2/
- Standalone demo login: https://dawitmengist263.github.io/cryptobigot2/login.html
- Support prototype: https://dawitmengist263.github.io/cryptobigot2/support.html
- Admin sandbox prototype: https://dawitmengist263.github.io/cryptobigot2/admin.html

## Demo sign-in

- Username: `demo`
- Password: `demo123`

These are public test credentials, not secure account authentication. The login check runs in the browser only.

## Exchange features

- Public Binance market-data feed for available spot pairs, with refresh about every 30 seconds when the API is reachable.
- Searchable market list, watchlist, Hot (highest 24-hour quote volume), Gainers, and Losers filters.
- Coin-specific colors/icons, price display, 24-hour change and volume.
- RSI (14) and EMA (9/21) technical indicator panel labelled as a rule-based signal assistant; it is not a predictive AI model.
- Simulated buy/sell orders, demo balance and activity history.
- Demo deposit/withdraw controls that only adjust practice balance in the browser; they do not move money or cryptocurrency.
- Responsive layout for desktop and mobile screens.

## Important limitations

- **Demo only:** no real trades, deposits, withdrawals, wallet transfers, or exchange account connection occurs.
- Market prices and signals depend on access to Binance's public API and may be unavailable due to network, browser, or regional restrictions.
- Demo balances and activity are local browser state and are not a real wallet or cloud account.
- Login is a client-side demo gate and is not secure authentication.
- GitHub Pages serves static files; it does not provide a secure database, server-side authentication, or private admin access.
- Never enter a real password, wallet recovery phrase, private key, or sensitive financial information into this demo.

## Deployment

GitHub Pages publishes the root of the `main` branch. After changes are committed, allow a short time for Pages to rebuild, then refresh the site. If the old version remains, use a hard refresh (Ctrl+F5 on Windows).
