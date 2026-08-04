# CyberArk Identity (cyberark-identity)

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

CyberArk Identity is a SaaS identity and access management platform offering single sign-on (SSO), multi-factor authentication (MFA), adaptive access, lifecycle management, directory services, and privileged access controls for workforce and customer identities. The platform integrates with thousands of applications and supports enterprise zero-trust strategies. CyberArk Identity exposes REST APIs for authentication, authorization, user and role management, and policy operations, authenticated via OAuth 2.0 (including client_credentials) or session tokens obtained via /Security/StartAuthentication and /Security/AdvanceAuthentication.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/cyberark-identity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/cyberark-identity/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Identity
- Access Management
- IAM
- Single Sign-On
- SSO
- Multi-Factor Authentication
- OAuth
- Zero Trust

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### CyberArk Identity API

REST API for CyberArk Identity covering authentication, authorization, OAuth 2.0 token endpoints, user and role management, directory services, application provisioning, and policy operations. Supports OAuth 2.0 flows including client_credentials for non-interactive API access, plus session-based authentication via /Security/StartAuthentication and /Security/AdvanceAuthentication.

- **Human URL:** [https://api-docs-identity.cyberark.com/docs/identity-api-reference/before-you-begin](https://api-docs-identity.cyberark.com/docs/identity-api-reference/before-you-begin)
- **Base URL:** `https://<tenant>.id.cyberark.cloud`

#### Tags

- Identity
- OAuth
- Authentication
- Authorization
- User Management

#### Properties

- [Documentation](https://api-docs-identity.cyberark.com/docs/identity-api-reference/before-you-begin)
- [O Auth 2.0  Overview](https://docs.cyberark.com/identity/latest/en/content/developer/oauth/about-oauth.htm)
- [I S P S S  A P I  Authentication](https://docs.cyberark.com/ispss-access/latest/en/content/ispss/ispss-api-authentication.htm)
- [Developer  Overview](https://docs.cyberark.com/identity/Latest/en/Content/Developer/OverviewofAPIs.htm)
- [Postman Collection](collections/cyberark-identity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/cyberark-identity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.cyberark.com/products/identity-management/)
- [Documentation](https://docs.cyberark.com/identity/latest/en/)
- [A P I  Docs](https://api-docs-identity.cyberark.com/)
- [Pricing](https://www.cyberark.com/contact-us/)
- [Sign Up](https://www.cyberark.com/try-buy/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
