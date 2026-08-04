# ExecOnline

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

ExecOnline is a New York-based B2B leadership-development company that partners with top business schools — UC Berkeley Executive Education, Chicago Booth, Columbia, UVA Darden, Tuck at Dartmouth, Duke CE, IMD, Ivey, MIT Sloan, Stanford GSB, Wharton and Yale — to deliver executive education online at enterprise scale. Founded in 2012, it blends professor-led courses, coaching, cohort sessions and on-demand content into one connected learning journey, with an insights-and-reporting layer that ties learning outcomes to business goals. ExecOnline acquired Teamraderie in 2026.

## No public API

As of **2026-08-04**, ExecOnline publishes **no public API**: no developer portal, no API documentation, and no machine-readable contract. Full contract discovery was run against every live host (`www`, `platform`, `app`, `connect`, `status`, `support`, and the `api` subdomain) covering OpenAPI/Swagger paths, GraphQL introspection, MCP `tools/list`, and the A2A agent card at both the canonical and legacy well-known paths — all missed. `api.execonline.com` points at an unconfigured GitHub Pages site that returns HTTP 200 HTML for every path and is recorded as a rejected false positive.

The full probe record, including every host and path tried, is in [`conformance/execonline-conformance.yml`](conformance/execonline-conformance.yml).

## What is in this profile

| Artifact | What it holds |
|---|---|
| [`packages/`](packages/execonline-packages.yml) | 16 first-party `@execonline-inc` npm packages (the CooperTS TypeScript toolkit) — application utilities, **not** API client SDKs |
| [`well-known/`](well-known/execonline-well-known.yml) | `/.well-known/` probe record; zero first-party documents (the two `security.txt` hits belong to Atlassian and Intercom) |
| [`lifecycle/`](lifecycle/execonline-lifecycle.yml) | 99.5% quarterly SLA, Atlassian Statuspage, service-credit remedy |
| [`conformance/`](conformance/execonline-conformance.yml) | ISO/IEC 27001:2013 certification, EU-U.S. / UK / Swiss-U.S. Data Privacy Framework, GDPR, CCPA |
| [`security/`](security/) | Domain security probe (TLS/HSTS/SPF/DMARC/CAA/DNSSEC) and the vulnerability-disclosure posture |
| [`llms/`](llms/execonline-llms.txt) | Generated `llms.txt` for agents, leading with the fact that there is no API to call |

Links: [execonline.com](https://www.execonline.com/) · [GitHub org](https://github.com/execonline-inc) · [Status](https://status.execonline.com/) · [Secondary-market listing](https://forgeglobal.com/execonline_stock/)
