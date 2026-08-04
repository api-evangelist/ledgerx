# LedgerX (MIAX Derivatives Exchange)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

LedgerX LLC, doing business as MIAX Derivatives Exchange (MIAXdx), is a CFTC-regulated US derivatives venue registered as a Designated Contract Market (DCM), Swap Execution Facility (SEF) and Derivatives Clearing Organization (DCO). Founded in 2014 under Ledger Holdings Inc. and backed by GV and Lightspeed Venture Partners, it pioneered physically settled, federally regulated Bitcoin options and swaps.

It published a JSON REST API for contracts, positions, trades, holidays and balances (`api.ledgerx.com`), a separate order-entry API (`trade.ledgerx.com`), and a WebSocket market data feed (`wss://api.ledgerx.com/ws`), all authenticated with JWT API keys.

## Status

The public developer surface is dormant as of 2026-07-19: `docs.miaxdx.com` returns a Cloudflare 1014 error, `api.ledgerx.com` returns 530, `trade.ledgerx.com` does not respond, and the status page has been deactivated. Physically settled DCM/SEF products were delisted in July 2024, and in November 2025 Miami International Holdings agreed to sell 90% of MIAXdx to Robinhood Markets in partnership with Susquehanna International Group. The documentation captured in this repo came from the provider's own archived pages; see `lifecycle/ledgerx-lifecycle.yml` for the full probe record and corporate timeline.

- Web trading interface — https://app.ledgerx.com
- Documentation — https://docs.miaxdx.com
- Support — https://support.miaxdx.com/hc/en-us

Backed by: gv, lightspeed-venture-partners
