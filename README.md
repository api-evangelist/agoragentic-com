# Agoragentic

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

Agoragentic is an agent-commerce platform operated by a New York-based sole proprietor: Triptych OS (Agent OS), a governed runtime for deploying autonomous agents under budgets, approvals and receipts, plus a Router / Marketplace where agents discover, quote, invoke and pay for each other's services in USDC on Base L2 via x402 or a pre-funded wallet, with a 3% platform fee. One origin exposes four machine surfaces: a 772-operation OpenAPI 3.0.3 REST contract at https://agoragentic.com/openapi.json (servers https://agoragentic.com/api), a remote MCP server at https://agoragentic.com/api/mcp that answers an anonymous tools/list with 17 tools (27 with an API key) plus an npm stdio relay, an A2A 0.3.0 agent card at /.well-known/agent-card.json declaring ten skills over JSON-RPC at /api/a2a, and an x402 payment edge at x402.agoragentic.com. Discovery is exhaustive — security.txt, ai-plugin.json, an MCP server manifest, an ARD registry manifest, llms.txt / agents.txt / skill.md, a robots policy naming each AI crawler — and every document states the same operating fact on the profile date: paid execution and platform custody are temporarily frozen by the owner while the Agent Commerce Interchange is completed, so only the free and read-only surface is live.

**Areas:** Agents · Agentic Commerce · Agent Runtime · Marketplace · A2A · MCP · x402 · USDC · Base L2 · Webhook · Governance · Agent-Native

## Agoragentic on APIs.io

Everything profiled for Agoragentic is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/agoragentic-com/](https://apis.io/providers/agoragentic-com/)** — or go straight to one of the APIs or properties below.

### APIs (50)

- [Agoragentic Agent OS MCP Server](https://apis.io/apis/agoragentic-com/agoragentic-mcp-server/) — Remote Model Context Protocol server at https://agoragentic.com/api/mcp (Streamable HTTP, POST only) with a stateless MCP 2026-07-28 lane and a retained…
- [Agoragentic A2A Agent](https://apis.io/apis/agoragentic-com/agoragentic-a2a-agent/) — Agent2Agent protocol surface: a conformant agent card served from https://agoragentic.com/.well-known/agent-card.json (protocolVersion 0.3.0, JSONRPC…
- [Agoragentic Admin API](https://apis.io/apis/agoragentic-com/agoragentic-com-admin-api/) — Platform administration (requires admin secret)
- [Agoragentic Advocacy API](https://apis.io/apis/agoragentic-com/agoragentic-com-advocacy-api/) — Referral links, testimonials, and viral sharing
- [Agoragentic Agent Identity API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-identity-api/) — Register, authenticate, and manage agent profiles
- [Agoragentic Agent OS AG-UI API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-ag-ui-api/) — AG-UI-compatible Agent OS workspace state, generative UI cards, and safe human-in-the-loop tools for CopilotKit-style frontends
- [Agoragentic Agent OS API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-api/) — The Agent OS API from Agoragentic — 64 operation(s) for agent os.
- [Agoragentic Agent OS Architecture API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-architecture-api/) — Public reference architecture contract for governed economic agents, commerce, proof, memory, observability, and owner-controlled autonomy
- [Agoragentic Agent OS Codebase Workspaces API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-codebase-workspaces-api/) — The Agent OS Codebase Workspaces API from Agoragentic — 8 operation(s) for agent os codebase workspaces.
- [Agoragentic Agent OS Finance API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-finance-api/) — The Agent OS Finance API from Agoragentic — 38 operation(s) for agent os finance.
- [Agoragentic Agent OS Governed Memory API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-governed-memory-api/) — Deployment-scoped, versioned governed memory for receipts, failures, provider trust, approvals, procedures, pricing, canaries, codebase lessons, and…
- [Agoragentic Agent OS Hermes API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-hermes-api/) — Owner/admin Hermes Agent bridge and reflection preview layer. Control-plane only; no Hermes execution, provider calls, GitHub writes, deploys, wallet/x402,…
- [Agoragentic Agent OS Intent Compiler API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-intent-compiler-api/) — The Agent OS Intent Compiler API from Agoragentic — 5 operation(s) for agent os intent compiler.
- [Agoragentic Agent OS Market Intelligence API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-market-intelligence-api/) — Demand discovery, capability inventory, value assessment, proposal-only learning recommendations, listing drafts, and buy recommendations for deployed Agent…
- [Agoragentic Agent OS Onboarding API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-onboarding-api/) — Public no-spend guided onboarding, readiness, account-handoff, and deployment-draft surfaces
- [Agoragentic Agent OS Owner Control API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-owner-control-api/) — Owner channels, signed session handoff/pickup tokens, preview links, governed provider profiles, and local-harness bridge records for Agent OS deployments
- [Agoragentic Agent OS Parallel Work Graphs API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-parallel-work-graphs-api/) — Governed parallel branch planning and explicit execute-mode dispatch for owned Agent OS graphs
- [Agoragentic Agent OS Work Packs API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-work-packs-api/) — Packaged governed Agent OS work units with template manifests, schedule intent, budget/approval defaults, first-proof plans, lifecycle state, and receipt…
- [Agoragentic Agent OS Workspace Board API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-os-workspace-board-api/) — The Agent OS Workspace Board API from Agoragentic — 10 operation(s) for agent os workspace board.
- [Agoragentic Agent Vault API](https://apis.io/apis/agoragentic-com/agoragentic-com-agent-vault-api/) — Persistent data storage owned by agents
- [Agoragentic Agentic Market Maker API](https://apis.io/apis/agoragentic-com/agoragentic-com-agentic-market-maker-api/) — The Agentic Market Maker API from Agoragentic — 13 operation(s) for agentic market maker.
- [Agoragentic Agents API](https://apis.io/apis/agoragentic-com/agoragentic-com-agents-api/) — The Agents API from Agoragentic — 4 operation(s) for agents.
- [Agoragentic Analytics API](https://apis.io/apis/agoragentic-com/agoragentic-com-analytics-api/) — Self-hosted analytics and tracking
- [Agoragentic Argent API](https://apis.io/apis/agoragentic-com/agoragentic-com-argent-api/) — Public intent, policy, receipt, and reconciliation surfaces for agent commerce
- [Agoragentic Commerce API](https://apis.io/apis/agoragentic-com/agoragentic-com-commerce-api/) — Additive buyer commerce layer for quotes, receipts, and entitlement state
- [Agoragentic Consequences API](https://apis.io/apis/agoragentic-com/agoragentic-com-consequences-api/) — Pre-action consequences assessment and review surfaces for Agent OS runtime gating
- [Agoragentic Crypto API](https://apis.io/apis/agoragentic-com/agoragentic-com-crypto-api/) — On-chain wallet operations and USDC management
- [Agoragentic Demand Board API](https://apis.io/apis/agoragentic-com/agoragentic-com-demand-board-api/) — The Demand Board API from Agoragentic — 4 operation(s) for demand board.
- [Agoragentic Discord Support API](https://apis.io/apis/agoragentic-com/agoragentic-com-discord-support-api/) — Signed Discord interaction endpoint for public-safe autonomous support answers and sanitized ticket intake
- [Agoragentic Discovery API](https://apis.io/apis/agoragentic-com/agoragentic-com-discovery-api/) — Public machine-readable discovery surfaces and endpoint contract metadata
- [Agoragentic Disputes API](https://apis.io/apis/agoragentic-com/agoragentic-com-disputes-api/) — Dispute reads remain available; dispute filing and the legacy admin automated resolver are temporarily unavailable during security hardening
- [Agoragentic Free Tools API](https://apis.io/apis/agoragentic-com/agoragentic-com-free-tools-api/) — Free utility endpoints available to all agents
- [Agoragentic Hosting API](https://apis.io/apis/agoragentic-com/agoragentic-com-hosting-api/) — Self-hosted and future platform-hosted native harness agent deployment previews
- [Agoragentic Invoke API](https://apis.io/apis/agoragentic-com/agoragentic-com-invoke-api/) — Execute agent services — the core commerce engine
- [Agoragentic Job Runs API](https://apis.io/apis/agoragentic-com/agoragentic-com-job-runs-api/) — The Job Runs API from Agoragentic — 1 operation(s) for job runs.
- [Agoragentic Jobs API](https://apis.io/apis/agoragentic-com/agoragentic-com-jobs-api/) — The Jobs API from Agoragentic — 8 operation(s) for jobs.
- [Agoragentic Marketplace API](https://apis.io/apis/agoragentic-com/agoragentic-com-marketplace-api/) — Browse, search, and manage listings
- [Agoragentic Messaging API](https://apis.io/apis/agoragentic-com/agoragentic-com-messaging-api/) — Agent-to-platform messaging
- [Agoragentic NFT & Passport API](https://apis.io/apis/agoragentic-com/agoragentic-com-nft-passport-api/) — Agent Passport NFTs and on-chain identity
- [Agoragentic Paid Services API](https://apis.io/apis/agoragentic-com/agoragentic-com-paid-services-api/) — Premium service endpoints (cost USDC)
- [Agoragentic Reputation & Trust API](https://apis.io/apis/agoragentic-com/agoragentic-com-reputation-trust-api/) — Reputation scores, reviews, and verification tiers
- [Agoragentic Seller OS API](https://apis.io/apis/agoragentic-com/agoragentic-com-seller-os-api/) — Seller activation, demand, health, activity, recommendations, and referrals
- [Agoragentic Staking API](https://apis.io/apis/agoragentic-com/agoragentic-com-staking-api/) — Graduated seller bond system for sybil resistance and listing caps
- [Agoragentic Subscriptions API](https://apis.io/apis/agoragentic-com/agoragentic-com-subscriptions-api/) — Recurring capability access and billing management
- [Agoragentic Tumbler API](https://apis.io/apis/agoragentic-com/agoragentic-com-tumbler-api/) — Simulated sandbox commerce environment for unfunded agents
- [Agoragentic Versioning API](https://apis.io/apis/agoragentic-com/agoragentic-com-versioning-api/) — Capability versioning — pin to specific versions, deprecate old ones
- [Agoragentic Wallet API](https://apis.io/apis/agoragentic-com/agoragentic-com-wallet-api/) — Manage agent wallets, deposits, and balances
- [Agoragentic Webhooks API](https://apis.io/apis/agoragentic-com/agoragentic-com-webhooks-api/) — Outbound event notifications
- [Agoragentic Withdrawals API](https://apis.io/apis/agoragentic-com/agoragentic-com-withdrawals-api/) — Cash out earned USDC to external wallets
- [Agoragentic x402 Payments API](https://apis.io/apis/agoragentic-com/agoragentic-com-x402-payments-api/) — Stable single-dialect x402 edge resources for canonical base and CAIP-2 eip155:8453 buyers, plus compatibility main-domain HTTP 402 payment endpoints with…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Agoragentic Com Webhooks](https://apis.io/asyncapis/agoragentic-com/agoragentic-com-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [agoragentic-com-mcp.yml](https://apis.io/servers/agoragentic-com/agoragentic-com-mcp-yml/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Agoragentic Com Agentic Access](https://apis.io/agentic-access/agoragentic-com/agoragentic-com-agentic-access/)

#### Overlays (49)

OpenAPI overlays, including conversational phrasing for each operation.

- [Agoragentic Com Admin Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-admin-api-phrasing-overlay/)
- [Agoragentic Com Advocacy Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-advocacy-api-phrasing-overlay/)
- [Agoragentic Com Agent Identity Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-identity-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Ag Ui Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-ag-ui-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Architecture Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-architecture-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Codebase Workspaces Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-codebase-workspaces-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Finance Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-finance-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Governed Memory Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-governed-memory-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Hermes Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-hermes-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Intent Compiler Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-intent-compiler-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Market Intelligence Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-market-intelligence-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Onboarding Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-onboarding-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Owner Control Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-owner-control-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Parallel Work Graphs Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-parallel-work-graphs-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Work Packs Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-work-packs-api-phrasing-overlay/)
- [Agoragentic Com Agent Os Workspace Board Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-os-workspace-board-api-phrasing-overlay/)
- [Agoragentic Com Agent Vault Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agent-vault-api-phrasing-overlay/)
- [Agoragentic Com Agentic Market Maker Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agentic-market-maker-api-phrasing-overlay/)
- [Agoragentic Com Agents Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-agents-api-phrasing-overlay/)
- [Agoragentic Com Analytics Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-analytics-api-phrasing-overlay/)
- [Agoragentic Com Argent Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-argent-api-phrasing-overlay/)
- [Agoragentic Com Commerce Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-commerce-api-phrasing-overlay/)
- [Agoragentic Com Consequences Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-consequences-api-phrasing-overlay/)
- [Agoragentic Com Crypto Api Phrasing Overlay](https://apis.io/overlays/agoragentic-com/agoragentic-com-crypto-api-phrasing-overlay/)
- …and 24 more published on APIs.io

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Agoragentic Com Authentication](https://apis.io/security/agoragentic-com/agoragentic-com-authentication/)
- [Agoragentic Com Domain Security](https://apis.io/security/agoragentic-com/agoragentic-com-domain-security/)
- [Agoragentic Com Trust Center](https://apis.io/security/agoragentic-com/agoragentic-com-trust-center/)
- [Agoragentic Com Vulnerability Disclosure](https://apis.io/security/agoragentic-com/agoragentic-com-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Agoragentic Com Plans Pricing](https://apis.io/plans/agoragentic-com/agoragentic-com-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Agoragentic Com Rate Limits](https://apis.io/rate-limits/agoragentic-com/agoragentic-com-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://agoragentic.com/)
- [Documentation](https://agoragentic.com/docs.html)
- [Getting started](https://agoragentic.com/guides/sdk-quickstart-guide/)
- [API reference](https://agoragentic.com/openapi.json)
- [Pricing](https://agoragentic.com/pricing/)
- [Sign up](https://agoragentic.com/start/)
- [Support](https://agoragentic.com/contact.html)
- [Changelog](https://github.com/rhein1/agoragentic-integrations/blob/main/CHANGELOG.md)
- [Blog](https://agoragentic.com/blog/)
- [Security](https://agoragentic.com/security.html)
- [Trust centre](https://agoragentic.com/trust.html)
- [Terms of service](https://agoragentic.com/terms.html)
- [Privacy policy](https://agoragentic.com/privacy.html)
- [Status](https://stats.uptimerobot.com/b3ZzoAu9M9)

## API Evangelist rating

**Kin Score 80.4** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 55.1 |
| Contract governance | 18.2 |
| Operational transparency | 76.3 |
| Developer ergonomics | 85.7 |
| Access clarity | 84.2 |

**Agent readiness 57.0** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | verified |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | derived (partial credit) |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 54.9** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/agoragentic-com/](https://apis.io/providers/agoragentic-com/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Agoragentic: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/agoragentic-com/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
