# HORIZON SHIELD

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

The HORIZ音s株式会社 (The HORIZONs Co., Ltd., Hiratsuka, Kanagawa) operates HORIZON SHIELD, a buyer-side, agent-native fair-price verification service for Japanese construction and renovation estimates, built by a 30-year master carpenter on the open JCCDB dataset (95,403 items, CC BY 4.0). Its flagship KIRA server at mcp.horizonshield.dev is a free, anonymous remote MCP server (15 tools, 5 prompts) and A2A agent that audits a quoted price against fair ranges, flags overcharge tactics, and issues SHA-256 receipts anchored to Bitcoin via OpenTimestamps; a FairPriceAttestation tool bridges to Google's AP2 Cart Mandate. Around it sit a public MCP Verification Gate (the family's one OpenAPI, plus MCP and A2A) that measures other people's MCP servers against an A2A Conduct Extension the company authors, the JIDEC append-only verification ledger with an RFC 9727 api-catalog, the Yakumo verified-contractor directory MCP, a WebMCP intake server and a femtech source registry — every card JWS-signed, every surface unauthenticated by design, and paid for by buyers rather than contractors.

**Areas:** Construction · Renovation · Cost Estimation · Fair Pricing · Consumer Protection · Verification · Transparency Ledger · Open Data · MCP · A2A · AP2 · Agents

## HORIZON SHIELD on APIs.io

Everything profiled for HORIZON SHIELD is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/horizonshield-dev/](https://apis.io/providers/horizonshield-dev/)** — or go straight to one of the APIs or properties below.

### APIs (28)

- [HORIZON SHIELD KIRA MCP Server](https://apis.io/apis/horizonshield-dev/horizon-shield-kira-mcp-server/) — Remote Model Context Protocol server at https://mcp.horizonshield.dev/ (Streamable HTTP, POST only, protocol 2025-06-18, serverInfo horizon-shield 1.0.9,…
- [HORIZON SHIELD KIRA A2A Agent](https://apis.io/apis/horizonshield-dev/horizon-shield-kira-a2a-agent/) — Agent2Agent surface of the same service: a JWS-signed agent card at https://mcp.horizonshield.dev/.well-known/agent-card.json (protocolVersion 0.3.0 with…
- [JIDEC Verification Ledger API](https://apis.io/apis/horizonshield-dev/jidec-verification-ledger-api/) — Append-only, Bitcoin-anchored (OpenTimestamps) public ledger of the verification process at https://ledger.horizonshield.dev: an index of anchored entries,…
- [Yakumo Verified-Contractor Directory MCP](https://apis.io/apis/horizonshield-dev/yakumo-verified-contractor-mcp/) — Remote MCP server at https://hearing.horizonshield.dev/mcp (serverInfo HORIZON SHIELD YAKUMO 2.3.1, protocol 2025-06-18) exposing six read-only tools over…
- [HORIZON SHIELD WebMCP Intake Server](https://apis.io/apis/horizonshield-dev/webmcp-intake-server/) — A second public MCP endpoint at https://web.horizonshield.dev/mcp (serverInfo hs-webmcp 1.0.4, protocol 2025-06-18; server.json published at…
- [HORIZON SHIELD Femtech Source Registry MCP](https://apis.io/apis/horizonshield-dev/femtech-source-registry-mcp/) — A separate product line by the same company: a neutral, verifiable registry of femtech information sources exposed as a remote MCP server at…
- [HORIZON SHIELD Badge API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-badge-api/) — The Badge API from HORIZON SHIELD — 2 operation(s) for badge.
- [HORIZON SHIELD Changes API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-changes-api/) — The Changes API from HORIZON SHIELD — 1 operation(s) for changes.
- [HORIZON SHIELD Check API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-check-api/) — The Check API from HORIZON SHIELD — 1 operation(s) for check.
- [HORIZON SHIELD E API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-e-api/) — The E API from HORIZON SHIELD — 1 operation(s) for e.
- [HORIZON SHIELD Embed API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-embed-api/) — The Embed API from HORIZON SHIELD — 1 operation(s) for embed.
- [HORIZON SHIELD Ext API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-ext-api/) — The Ext API from HORIZON SHIELD — 1 operation(s) for ext.
- [HORIZON SHIELD Feed.xml API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-feed-xml-api/) — The Feed.xml API from HORIZON SHIELD — 1 operation(s) for feed.xml.
- [HORIZON SHIELD Health API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-health-api/) — The Health API from HORIZON SHIELD — 1 operation(s) for health.
- [HORIZON SHIELD History API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-history-api/) — The History API from HORIZON SHIELD — 1 operation(s) for history.
- [HORIZON SHIELD MCP API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-mcp-api/) — The Mcp API from HORIZON SHIELD — 1 operation(s) for mcp.
- [HORIZON SHIELD Mould API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-mould-api/) — The Mould API from HORIZON SHIELD — 1 operation(s) for mould.
- [HORIZON SHIELD Nenrin API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-nenrin-api/) — The Nenrin API from HORIZON SHIELD — 1 operation(s) for nenrin.
- [HORIZON SHIELD Recompute API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-recompute-api/) — The Recompute API from HORIZON SHIELD — 1 operation(s) for recompute.
- [HORIZON SHIELD Register API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-register-api/) — The Register API from HORIZON SHIELD — 2 operation(s) for register.
- [HORIZON SHIELD Self API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-self-api/) — The Self API from HORIZON SHIELD — 1 operation(s) for self.
- [HORIZON SHIELD Sitemap.xml API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-sitemap-xml-api/) — The Sitemap.xml API from HORIZON SHIELD — 1 operation(s) for sitemap.xml.
- [HORIZON SHIELD Spec API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-spec-api/) — The Spec API from HORIZON SHIELD — 1 operation(s) for spec.
- [HORIZON SHIELD Sweep API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-sweep-api/) — The Sweep API from HORIZON SHIELD — 1 operation(s) for sweep.
- [HORIZON SHIELD Verified.json API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-verified-json-api/) — The Verified.json API from HORIZON SHIELD — 1 operation(s) for verified.json.
- [HORIZON SHIELD Verify Event API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-verify-event-api/) — The Verify Event API from HORIZON SHIELD — 1 operation(s) for verify event.
- [HORIZON SHIELD Watchlist API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-watchlist-api/) — The Watchlist API from HORIZON SHIELD — 1 operation(s) for watchlist.
- [HORIZON SHIELD .well Known API](https://apis.io/apis/horizonshield-dev/horizonshield-dev-well-known-api/) — The .well Known API from HORIZON SHIELD — 2 operation(s) for .well known.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (7)

Model Context Protocol servers that expose the API to agents.

- [Femtech registry MCP endpoint](https://apis.io/servers/horizonshield-dev/femtech-registry-mcp-endpoint/)
- [Moved to /providers/horizonshield-dev/](https://apis.io/servers/horizonshield-dev/gate-mcp-endpoint-streamable-http-post/)
- [horizonshield-dev-mcp.yml](https://apis.io/servers/horizonshield-dev/horizonshield-dev-mcp-yml/)
- [JIDEC read-only MCP endpoint](https://apis.io/servers/horizonshield-dev/jidec-read-only-mcp-endpoint/)
- [mcp](https://apis.io/servers/horizonshield-dev/mcp/)
- [WebMCP intake endpoint (Streamable HTTP, POST)](https://apis.io/servers/horizonshield-dev/webmcp-intake-endpoint-streamable-http-post/)
- [Yakumo MCP endpoint (Streamable HTTP, POST)](https://apis.io/servers/horizonshield-dev/yakumo-mcp-endpoint-streamable-http-post/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Horizonshield Dev Agentic Access](https://apis.io/agentic-access/horizonshield-dev/horizonshield-dev-agentic-access/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Horizonshield Dev Mcp Conduct Register Overlay](https://apis.io/overlays/horizonshield-dev/horizonshield-dev-mcp-conduct-register-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Horizonshield Dev Authentication](https://apis.io/security/horizonshield-dev/horizonshield-dev-authentication/)
- [Horizonshield Dev Domain Security](https://apis.io/security/horizonshield-dev/horizonshield-dev-domain-security/)
- [Horizonshield Dev Vulnerability Disclosure](https://apis.io/security/horizonshield-dev/horizonshield-dev-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Horizonshield Dev Plans Pricing](https://apis.io/plans/horizonshield-dev/horizonshield-dev-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Horizonshield Dev Rate Limits](https://apis.io/rate-limits/horizonshield-dev/horizonshield-dev-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://shield.the-horizons-innovation.com/)
- [Documentation](https://github.com/ogasurfproject-jpg/horizon-shield#readme)
- [Getting started](https://github.com/ogasurfproject-jpg/horizon-shield/blob/main/plugin/README.md)
- [API reference](https://gate.horizonshield.dev/openapi.json)
- [Pricing](https://shield.the-horizons-innovation.com/yakumo/plans/)
- [Support](https://shield.the-horizons-innovation.com/faq/)
- [Blog](https://shield.the-horizons-innovation.com/blog/)
- [Terms of service](https://shield.the-horizons-innovation.com/tos)
- [Privacy policy](https://shield.the-horizons-innovation.com/privacy)
- [GitHub](https://github.com/ogasurfproject-jpg)

## API Evangelist rating

**Kin Score 54.1** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 86.7 |
| Contract quality | 43.5 |
| Contract governance | 18.2 |
| Operational transparency | 31.6 |
| Developer ergonomics | 69.0 |
| Access clarity | 63.2 |

**Agent readiness 37.5** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/horizonshield-dev/](https://apis.io/providers/horizonshield-dev/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for HORIZON SHIELD: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/horizonshield-dev/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
