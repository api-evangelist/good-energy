# Good Energy (good-energy)

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

Good Energy is a British renewable energy supplier and green-technology installer founded in 1999 and headquartered in Chippenham, Wiltshire, acquired outright by Abu Dhabi based Esyasoft Investment Holding in March 2025 for GBP 99.4 million. It sits on the retail edge of the GB electricity value chain: a licensed supplier buying 100% renewable power directly from more than 2,000 British generators, the largest voluntary administrator of the Feed-in Tariff, an export/Smart Export Guarantee counterparty, and an installer of solar, batteries, heat pumps and EV chargers. Its API posture is honest and thin. The United Kingdom mandated smart-metering INFRASTRUCTURE, not a consumer data right: Good Energy is a Balancing and Settlement Code and Retail Energy Code party operating DCC-adopted SMETS2 smart meters — verified through an Ofgem regulatory-sandbox decision naming Good Energy Ltd and through Elexon BSC modification P459, which Good Energy itself raised to allow different supplier agents on import and export MSIDs where DCC-adopted smart meters are installed. That obligation produces no public API whatsoever. There is no UK equivalent of the Australian Consumer Data Right binding Good Energy, no Green Button, and no accredited-recipient scheme. No developer portal exists. Both sides are closed: consumer usage and billing data are reachable only by the account holder through the login-gated customer hub, and no open grid or market data is published — GB open energy data comes from NESO, Elexon and the DNOs, not from the supplier.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/good-energy/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/good-energy/refs/heads/main/apis.yml)

## Tags

- Energy
- United Kingdom
- Utilities
- Electricity
- Gas
- Renewables
- Smart Metering
- Solar
- EV Charging
- Energy Retail

## Timestamps

- **Created:** 2026-07-27
- **Modified:** 2026-07-27

## APIs

### Good Energy Customer Identity (OpenID Connect)

The OpenID Connect / OAuth 2.0 identity provider behind Good Energy's customer hub at account.goodenergy.co.uk. It is NOT a developer-facing API and Good Energy publishes no documentation for it — it is listed here only because its discovery metadata is served anonymously and machine-readably, making it the only harvestable API contract the company exposes. The document advertises a Duende IdentityServer style surface with authorization, token, userinfo, introspection, revocation, device-authorization, CIBA and PAR endpoints, PKCE (S256), DPoP signing algorithms, and the scopes `openid`, `profile`, `email`, `offline_access`, `customer_portal` and `customer_portal_tariff_switch`. There is no `registration_endpoint`, so no third party can obtain a client; access is customer-account-required.

- **Human URL:** [https://account.goodenergy.co.uk/](https://account.goodenergy.co.uk/)
- **Base URL:** `https://login.goodenergy.co.uk`

#### Tags

- Energy
- United Kingdom
- Identity
- OpenID Connect
- OAuth
- Customer Portal

#### Properties

- [OpenID Connect Discovery](authentication/good-energy-openid-configuration.json) — [OpenID Connect Discovery 1.0](https://openid.net/specs/openid-connect-discovery-1_0.html)
- [JWKS](authentication/good-energy-openid-jwks.json) — [JSON Web Key Set (RFC 7517)](https://www.rfc-editor.org/rfc/rfc7517)
- [Authentication](https://login.goodenergy.co.uk/.well-known/openid-configuration)
- [Sign In](https://account.goodenergy.co.uk/)

## Common Properties

- [Website](https://www.goodenergy.co.uk/)
- [Blog](https://www.goodenergy.co.uk/blog/)
- [Blog RSS](https://www.goodenergy.co.uk/feed/)
- [LinkedIn](https://uk.linkedin.com/company/goodenergyuk)
- [Sign In](https://account.goodenergy.co.uk/)
- [Security.txt](https://www.goodenergy.co.uk/.well-known/security.txt)
- [Partners](https://www.goodenergy.co.uk/partners/)
- [Investor Relations](https://www.goodenergy.co.uk/investors/)
- [Support](https://www.goodenergy.co.uk/help/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
