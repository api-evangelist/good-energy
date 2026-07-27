# Good Energy (good-energy)

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
