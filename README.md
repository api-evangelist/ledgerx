# LedgerX (MIAX Derivatives Exchange)

LedgerX LLC, doing business as MIAX Derivatives Exchange (MIAXdx), is a CFTC-regulated US derivatives venue registered as a Designated Contract Market (DCM), Swap Execution Facility (SEF) and Derivatives Clearing Organization (DCO). Founded in 2014 under Ledger Holdings Inc. and backed by GV and Lightspeed Venture Partners, it pioneered physically settled, federally regulated Bitcoin options and swaps.

It published a JSON REST API for contracts, positions, trades, holidays and balances (`api.ledgerx.com`), a separate order-entry API (`trade.ledgerx.com`), and a WebSocket market data feed (`wss://api.ledgerx.com/ws`), all authenticated with JWT API keys.

## Status

The public developer surface is dormant as of 2026-07-19: `docs.miaxdx.com` returns a Cloudflare 1014 error, `api.ledgerx.com` returns 530, `trade.ledgerx.com` does not respond, and the status page has been deactivated. Physically settled DCM/SEF products were delisted in July 2024, and in November 2025 Miami International Holdings agreed to sell 90% of MIAXdx to Robinhood Markets in partnership with Susquehanna International Group. The documentation captured in this repo came from the provider's own archived pages; see `lifecycle/ledgerx-lifecycle.yml` for the full probe record and corporate timeline.

- Web trading interface — https://app.ledgerx.com
- Documentation — https://docs.miaxdx.com
- Support — https://support.miaxdx.com/hc/en-us

Backed by: gv, lightspeed-venture-partners
