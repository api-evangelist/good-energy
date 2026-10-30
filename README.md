# Good Energy

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Good Energy is a British renewable energy supplier and green-technology installer founded in 1999 and headquartered in Chippenham, Wiltshire, acquired outright by Abu Dhabi based Esyasoft Investment Holding in March 2025 for GBP 99.4 million. It sits on the retail edge of the GB electricity value chain: a licensed supplier buying 100% renewable power directly from more than 2,000 British generators, the largest voluntary administrator of the Feed-in Tariff, an export/Smart Export Guarantee counterparty, and an installer of solar, batteries, heat pumps and EV chargers. Its API posture is honest and thin. The United Kingdom mandated smart-metering INFRASTRUCTURE, not a consumer data right: Good Energy is a Balancing and Settlement Code and Retail Energy Code party operating DCC-adopted SMETS2 smart meters — verified through an Ofgem regulatory-sandbox decision naming Good Energy Ltd and through Elexon BSC modification P459, which Good Energy itself raised to allow different supplier agents on import and export MSIDs where DCC-adopted smart meters are installed. That obligation produces no public API whatsoever. There is no UK equivalent of the Australian Consumer Data Right binding Good Energy, no Green Button, and no accredited-recipient scheme. No developer portal exists (developer., developers., docs. and data. subdomains do not resolve; /developers, /api and /docs return 404). Both sides are closed: consumer usage and billing data are reachable only by the account holder through the login-gated customer hub, and no open grid or market data is published — GB open energy data comes from NESO, Elexon and the DNOs, not from the supplier. The single machine-readable API artifact Good Energy exposes anonymously is the OpenID Connect discovery document of its customer-login identity provider.

**Areas:** Energy · United Kingdom · Utilities · Electricity · Gas · Renewables · Smart Metering · Solar · EV Charging · Energy Retail

## Good Energy on APIs.io

Everything profiled for Good Energy is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/good-energy/](https://apis.io/providers/good-energy/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Good Energy Customer Identity (OpenID Connect)](https://apis.io/apis/good-energy/good-energy-customer-identity-openid-connect/) — The OpenID Connect / OAuth 2.0 identity provider behind Good Energy's customer hub at account.goodenergy.co.uk. It is NOT a developer-facing API and Good…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Good Energy Authentication](https://apis.io/security/good-energy/good-energy-authentication/)
- [Good Energy Domain Security](https://apis.io/security/good-energy/good-energy-domain-security/)
- [Good Energy Vulnerability Disclosure](https://apis.io/security/good-energy/good-energy-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Good Energy Scopes](https://apis.io/scopes/good-energy/good-energy-scopes/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.goodenergy.co.uk/)
- [Pricing](https://www.goodenergy.co.uk/good-energy-tariffs/)
- [Sign up](https://www.goodenergy.co.uk/join/)
- [Support](https://www.goodenergy.co.uk/help/)
- [Blog](https://www.goodenergy.co.uk/blog/)
- [Security](https://www.goodenergy.co.uk/.well-known/security.txt)
- [Terms of service](https://www.goodenergy.co.uk/terms-conditions/)
- [Privacy policy](https://www.goodenergy.co.uk/privacy-policy/)

## API Evangelist rating

**Kin Score 25.9** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 0.0 |
| Contract governance | 4.5 |
| Operational transparency | 10.5 |
| Developer ergonomics | 19.0 |
| Access clarity | 44.7 |

**Agent readiness 2.5** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 39.3** — Energy & Utilities

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/good-energy/](https://apis.io/providers/good-energy/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Good Energy: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/good-energy/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
